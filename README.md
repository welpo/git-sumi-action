<p align="center">
    <a href="https://sumi.rs">
        <img src="https://raw.githubusercontent.com/welpo/git-sumi/main/website/static/img/logo.png" width="300" alt="git-sumi logo: a lantern held on a bamboo stick over the sea">
    </a>
    <br><br>
    <a href="https://github.com/welpo/git-sumi-action/releases"><img src="https://img.shields.io/github/v/release/welpo/git-sumi-action?style=flat-square&labelColor=202b2d&color=b05275" alt="GitHub version"></a>
    <a href="https://sumi.rs/docs">
        <img src="https://img.shields.io/website?url=https%3A%2F%2Fsumi.rs&style=flat-square&label=docs&labelColor=202b2d&color=b05275" alt="Documentation"></a>
    <a href="https://github.com/welpo/git-sumi">
      <img src="https://img.shields.io/badge/clean_commits-git--sumi-0?style=flat-square&labelColor=202b2d&color=b05275" alt="Clean commits"></a>
</p>

# 🏮 Run git-sumi Action

This GitHub action runs [git-**sumi**](https://sumi.rs) to validate a Pull Request title using the `sumi.toml` configuration set up in the root of your repository.

## Usage

1. Add a `sumi.toml` file to the root of your repository, enabling the rules you want to use (see the [configuration](https://sumi.rs/docs/configuration/) and [rules](https://sumi.rs/docs/rules/) documentation).

2. In your repository, create the workflow file `.github/workflows/git-sumi.yaml` with the following content:

```yaml
name: Lint pull request title

on:
  pull_request:
    types:
      - opened
      - edited
      - synchronize
      - ready_for_review

permissions:
  pull-requests: read

jobs:
  main:
    name: Run git-sumi
    runs-on: ubuntu-latest
    steps:
      - uses: welpo/git-sumi-action@main
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

This workflow will run on every pull request event, checking the title against the rules defined in `sumi.toml`.

3. Commit and push the workflow file to your repository.

4. That's it! The action will run automatically on every pull request event. If the title doesn't meet the rules, the action will fail and the pull request will be marked as "failing".

## Questions?

Don't hesitate to reach out via the [issue tracker](https://github.com/welpo/git-sumi-action/issues), [discussions](https://github.com/welpo/git-sumi-action/discussions), or [email](mailto:osc@osc.garden?subject=[GitHub]%20git-sumi-action).

## License

This project is licensed under the terms of both the [MIT license](/LICENSE-MIT) and the [Apache License (Version 2.0)](/LICENSE-APACHE), at your option.
