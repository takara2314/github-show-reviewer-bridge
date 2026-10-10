# Contributing

Thank you for taking the time to improve GitHub Show Reviewer Bridge.

This project is a fork of [araitaiga/github_show_reviewer](https://github.com/araitaiga/github_show_reviewer) and aims to preserve the original extension's UI and behavior as much as possible. Please keep changes focused and preserve the existing reviewer display and default layout.

## Discuss UI and behavior changes first

Before implementing a larger UI or behavior change, open an issue so we can discuss its scope and direction. An avatar-focused layout or a new filtering bar, for example, changes more than this project would accept as a replacement for the current default UI.

Possible directions for discussion include:

- Keeping the current layout as the default and offering an avatar layout as an optional setting.
- Making a smaller fix for GitHub's compact list layout while preserving the existing reviewer display.

These are ideas to discuss, not preapproved features. Opening an issue before implementation helps establish what fits the project, but does not guarantee that a pull request will be accepted.

## Keep pull requests focused

Describe the problem, the resulting behavior, and how you verified the change. For code changes, run `npm test`, which includes type checking and compilation. See the [README](README.md#-development) for build and development installation instructions.
