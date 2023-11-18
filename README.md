# SemanticReleaseHexTest

This is a test project to showcase version management of an Elixir project with [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) using [`semantic-release`](https://github.com/semantic-release/semantic-release/) and [`semantic-release-hex`](https://github.com/talent-ideal/semantic-release-hex).

## Releasing from the CLI

```shell
GH_TOKEN=$(gh auth token) npm run release -- --no-ci
```

## Setting up

Take a look at the [setup commit](https://github.com/sheerlox/semantic-release-hex-test/commit/016e53cc58755932a6b7b7b9cee4edeec63c0321) for this repository.

You should also add Node.js to your [`.tool-versions`](./.tool-versions) if you're using the [`asdf`](https://asdf-vm.com/) version manager.
