# Contributing to todo.txt

This repository documents the todo.txt plain-text task format. Start with the [README](README.md), which is the format reference, and preserve the distinction between core rules, examples, and optional conventions.

## Before you start

Search existing issues and pull requests before starting, and discuss substantial changes or new dependencies in an issue. Use an issue template when one is offered. For a bug, include the affected commit or version, environment, a minimal reproduction, and expected versus observed behavior; remove sensitive information from logs and screenshots.

## Development and validation

There is no application build or automated test command in this documentation repository. Validate changes by checking the rendered Markdown and by walking through the affected task examples against every relevant format rule.

For a format proposal, explain how existing clients and files would interpret it. Include valid and invalid examples covering priority, creation and completion dates, completion markers, projects, contexts, and key/value metadata as appropriate. Preserve whitespace-sensitive examples and distinguish a suggested extension from an established rule. Check links and the supplied diagram where a documentation change affects them.

Use fictional task descriptions. Avoid real schedules, private contacts, credentials, or personal reminders in examples. A clarification should identify the ambiguity it resolves and the expected interpretation.

## Pull requests

Work on a focused branch from the current default branch. Open a pull request explaining the problem, the resulting behavior, and any compatibility or data-format changes. Link the relevant issue and complete any existing PR template.

Add focused regression coverage for changed behavior and update affected examples or documentation. Describe the checks actually run, their results, and any checks you could not run. For documentation-only changes, verify links, examples, and rendered formatting. Use the repository's existing checks and review/merge process; preserve required checks and resolve actionable feedback without weakening the checks.

## Security and sensitive information

Follow the [account security policy](https://github.com/edithatogo/.github/blob/main/SECURITY.md). Report vulnerabilities privately through the repository's **Report a vulnerability** option if available; otherwise request a private reporting contact without posting exploit details. Never include credentials, personal information, restricted datasets, or confidential records in issues, commits, fixtures, or diagnostic output.

## Licensing and conduct

The repository's [license](LICENSE) continues to apply. Be respectful and constructive, and follow the [account code of conduct](https://github.com/edithatogo/.github/blob/main/CODE_OF_CONDUCT.md). Preserve attribution and third-party notices. Contribute only material you are entitled to share; resolve unclear permissions before adding third-party content. This guide does not change licensing terms or introduce a CLA or DCO requirement.

## References

- [GitHub contribution guideline conventions](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors)
- [OpenSSF contribution and quality criteria](https://www.bestpractices.dev/en/criteria)
