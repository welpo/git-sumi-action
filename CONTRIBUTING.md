# Contributing to git-sumi

Halló!

Thanks for contributing to [git-sumi-action](https://github.com/welpo/git-sumi-action). Before implementing new features and changes, please [submit an issue](https://github.com/welpo/git-sumi-action/issues/new) so that we can discuss it.

We welcome contributions in many forms, including:

- Bug reports
- Bug fixes
- Improvements to the codebase
- Documentation improvements

If you're not sure how to contribute or need help with something, please don't hesitate to reach out via the [issue tracker](https://github.com/welpo/git-sumi-action/issues) or [email](mailto:osc@osc.garden?subject=[GitHub]%20git-sumi-action).

## Pull Requests

Working on your first Pull Request? You can learn how from this free video series:

[**How to Contribute to an Open Source Project on GitHub**](https://egghead.io/courses/how-to-contribute-to-an-open-source-project-on-github)

Please make sure the following is done when submitting a pull request:

- **Keep your PR small**. Small pull requests (~300 lines of diff) are much easier to review and more likely to get merged. Make sure the PR does only one thing, otherwise please split it.
- **Use descriptive titles**. It is recommended to follow this [commit message style](#conventional-commit-messages).

### Conventional Commit Messages with Gitmoji

See how a minor change to your commit message style can make you a better programmer.

Format: `<gitmoji> <type>(<scope>): <description>`

`<gitmoji>` is an emoji from the [gitmoji](https://gitmoji.dev/) list. It makes it easier to visually scan the commit history and quickly grasp the purpose of changes.

`<scope>` is optional. If your change affects a specific part of the codebase, consider adding the scope. Scopes should be brief but recognizable, e.g. `config`, `gitmoji`, or `cli`.

The various types of commits:

- `feat`: a new API or behavior **for the end user**.
- `fix`: a bug fix **for the end user**.
- `docs`: a change to the website or other Markdown documents.
- `refactor`: a change to code that doesn't change behavior, e.g. splitting files, renaming internal variables, improving code style…
- `test`: adding missing tests, refactoring tests; no production code change.
- `chore`: upgrading dependencies, releasing new versions… Chores that are **regularly done** for maintenance purposes.
- `misc`: anything else that doesn't change production code, yet is not `test` or `chore`. e.g. updating GitHub actions workflow.

The commits within your PR don't need to follow this convention (we'll [squash them](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/configuring-pull-request-merges/configuring-commit-squashing-for-pull-requests)). However, the PR title should be in this format. If you're not sure about the title, don't worry, we'll help you fix it. Your code is more important than conventions!

Example:

```
✨ feat(rules): add custom header pattern
^  ^--^^-----^  ^------------^
|  |   |        |
|  |   |        +-> Description in imperative and lowercase.
|  |   |
|  |   +-> The scope of the change.
|  |
|  +-------> Type: see above for the list we use.
|
+----------> A valid gitmoji.
```

## Code of conduct

We expect all contributors to follow our [Code of Conduct](./CODE_OF_CONDUCT.md). Please be respectful and professional when interacting with other contributors.

Thank you for your contributions!
