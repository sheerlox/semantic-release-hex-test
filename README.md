# SemanticReleaseHexDemo

This is a demo project to showcase version management of an Elixir project with [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) using [`semantic-release`](https://github.com/semantic-release/semantic-release/) and [`semantic-release-hex`](https://github.com/talent-ideal/semantic-release-hex).

Feel free to explore its content, commit history, or even fork it to test things out, as it's what it's meant for.

If you have any question or feedback, feel free to reply on the [Elixir Forum thread](https://elixirforum.com/t/semanticreleasehex-fully-automated-version-management-and-release-processes/59837) or create a new [GitHub Discussion](https://github.com/sheerlox/semantic-release-hex-demo/discussions), I'll be happy to read and reply to you :heart:

## Learn more

- [`semantic-release` documentation](https://semantic-release.gitbook.io/semantic-release/)
- [`semantic-release-hex` documentation](https://github.com/talent-ideal/semantic-release-hex#readme)

## Try it out in your project

See [**Setting up an existing Elixir project**](https://github.com/talent-ideal/semantic-release-hex/blob/main/docs/SETTING_UP.md) on the main repo.

## Example auto-updating "Installation" section

```elixir
def deps do
  [{:semantic_release_hex_demo, "~> 1.0.5"}]
end
```

_Note: this also works when pointing to a git tag._
