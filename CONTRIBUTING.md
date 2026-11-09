# Contributing to DevPrax

DevPrax builds practical, extensible, and reliable tools for developers and engineering teams. We welcome bug reports, documentation improvements, tests, ideas, and code contributions from people of all experience levels.

These are the default guidelines for DevPrax repositories. Follow a project's own contribution guide and development documentation when it provides more specific instructions. Please follow our [Code of Conduct](https://github.com/devprax/.github/blob/main/CODE_OF_CONDUCT.md) in all community interactions.

## Before proposing a change

- Read the project's README and relevant documentation.
- Search existing issues and pull requests to avoid duplicating work.
- For a bug, open an issue in the affected repository using the bug report form. Include a minimal reproduction, the affected version, and expected and actual behavior.
- For a new feature or a substantial design change, open a feature request first. Describe the problem, who it affects, and alternatives you considered so maintainers can discuss the scope before implementation.
- Small, focused fixes and documentation improvements can go straight to a pull request.

For usage questions, see [Support](https://github.com/devprax/.github/blob/main/SUPPORT.md). Report suspected vulnerabilities through the [Security Policy](https://github.com/devprax/.github/blob/main/SECURITY.md); do not include vulnerability details in public issues or pull requests.

## Develop and test your change

1. Fork the affected repository, or use a branch if you have write access, and create a focused working branch from its default branch.
2. Follow that repository's setup instructions, supported runtime versions, and dependency management conventions.
3. Keep the change scoped to one problem. Follow existing code style and avoid unrelated formatting or dependency changes.
4. Add or update tests when behavior changes. For bug fixes, include a regression test where practical.
5. Run the relevant tests, formatting, linting, type checks, and build checks documented by the project or used in its CI workflows. Commands vary by repository; there is no organization-wide test command.
6. Update documentation and examples when usage changes. Describe changes to APIs, configuration, stored data, dependencies, or supported environments, including migration steps when needed.

Use synthetic or sanitized data in tests and examples. Do not commit credentials, tokens, private customer data, or confidential logs.

For changes to this `.github` repository, review Markdown rendering and links, validate issue-form YAML, and check that templates remain useful across projects. There is no application test suite here.

## Submit a pull request

- Give the PR a descriptive title and fill out the PR template.
- Explain the problem, the change, and any relevant tradeoffs. Link related issues; use `Fixes #123` only when the PR fully resolves that issue in the same repository.
- List the checks you ran and their results. If a check could not be run, say why and describe any manual verification.
- Call out breaking changes, compatibility risks, and migration requirements explicitly.
- Open a draft PR if you want feedback before the work is ready for review.
- Respond constructively to feedback and keep the PR description current as the implementation changes.

Maintainers review contributions for usefulness, correctness, compatibility, and maintenance cost. A proposal may need revision or may be declined. Review times depend on maintainer availability.

## Licensing

Check the license in the repository you are contributing to. Submit only work you have the right to contribute, and identify any third-party code or assets and their licenses. Ask maintainers if licensing is unclear.
