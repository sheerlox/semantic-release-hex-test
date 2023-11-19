# SemanticReleaseHexTest

This is a test project to showcase version management of an Elixir project with [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) using [`semantic-release`](https://github.com/semantic-release/semantic-release/) and [`semantic-release-hex`](https://github.com/talent-ideal/semantic-release-hex).

## Setting up

### Installing the tools

Take a look at the [setup commit](https://github.com/sheerlox/semantic-release-hex-demo/commit/016e53cc58755932a6b7b7b9cee4edeec63c0321) for this repository.

You should also add Node.js to your [`.tool-versions`](./.tool-versions) if you're using the [`asdf`](https://asdf-vm.com/) version manager.

### CI configuration (GitHub Actions)

See [`release.yml`](./.github/workflows/release.yml).

For the `CI_GITHUB_TOKEN` secret needed to bypass branch protection when pushing the release commit, see [this StackOverflow answer](https://stackoverflow.com/questions/74744498/github-pushing-to-protected-branches-with-fine-grained-token/76550826#76550826) (I know, I really need to [update the docs](https://github.com/semantic-release/semantic-release/issues/2883)).

## Releasing from the CLI

```shell
GH_TOKEN=$(gh auth token) npm run release -- --no-ci
```

_If you're concerned about security, you can run `gh auth refresh` after using `gh auth token` to regenerate [`gh`](https://cli.github.com/)'s token and invalidate the previous one (or you can create a fine-grained token by visiting the StackOverflow link in [CI configuration](#ci-configuration-github-actions))._

## Learn more

- [`semantic-release` documentation](https://semantic-release.gitbook.io/semantic-release/)
- [`semantic-release-hex` documentation](https://github.com/talent-ideal/semantic-release-hex#readme)
