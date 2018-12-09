# Contributing

This document contains a set of guidelines to help you during the contribution
process. Please review it in order to ensure a fast and effective response from
the maintainers and volunteers.

We are happy to welcome all contributions from anyone willing to improve this
project. Thank you for helping out and remember, no contribution is too small.

## Step by step contribution guide

You need to install and configure your environment before contributing.

1. [**Install**](#prerequisites) prerequisites
2. [**Fork**] the repository on GitHub
3. [**Clone**] the project to your own machine
4. [**Activate**](#pre-commit) pre-commit hooks
5. **Start working** on your fix, feature and etc.
6. **Commit** changes to your own branch according to
   [**Commit Message Guidelines**](#commit-message-guidelines)
7. **Push** your work back up to your fork
8. Submit a [**Pull Request**] so that we can review your changes

NOTE: Be sure to merge the latest from "**upstream**" before making a pull
request!

### Prerequisites

- [Git](https://git-scm.com/downloads)
- [Python](https://www.python.org/downloads/)
- [pre-commit](https://pre-commit.com/#install)

### Pre-commit

Run `pre-commit install` to install pre-commit into your git hooks. pre-commit
will now run on every commit. Running `pre-commit install` should always be the
first thing you do whenever you clone a project that uses pre-commit.

```sh
cd /go/to/project/folder
pre-commit install
```

## Commit Message Guidelines

We have strict rules over how our **git commit messages** can be formatted. This
leads to **more readable messages** that are easy to follow when looking through
the **project history**.

### Commit Message Format

Each commit message consists of a **header**, a **body** and a **footer**. The
header has a special format that includes a **type**, a **scope** and a
**subject**. The body and footer include a **type**;

```sh
<type>: (<scope>) <subject>
<BLANK LINE>
<type>: <body>
<BLANK LINE>
<type>: <footer>
```

The **header** is mandatory and the **scope** of the header is optional.

### Template

We use a base commit message template from [dotfiles]. You may find any
other additional *type*, *scope*, and more information below.

[dotfiles]: https://github.com/erdtsksn/dotfiles/blob/master/git/.gittemplate

### Additional Types

### Scopes

The following is the list of supported scopes:

- **git** e.g. gitignore, gitattributes, .github and etc.
- **cid** e.g. travis, pre-commit, netlify, heroku, and etc.
- **readme** e.g. readme, getting started, changelog, code of conduct, license
  and etc.

### Revert and Merge

We use default GIT templates for revert and merge.

## General questions

The main function of the issue tracker is to record bug reports and feature
requests.

## Issues and bugs

Before creating a new issue, please search for similar issues, open or closed,
to see if someone else has already noticed the same problem and possible
solutions.

Do not comment on open issues unless you can provide more information to resolve
it. Use the subscribe function to keep up-to-date with the issue or the voting
system to support it.

When you can't find a previous issue or bug, open an issue keeping in mind the
following considerations:

- Try to reproduce the bug using the code found on the master branch
- Copy and paste the full error message, including the backtrace
- Be as detailed as possible and include any additional information

## Feature requests

If you want to request or implement a new feature please submit an issue
describing the details and possible use cases.

Features that break backward compatibility must provide good reasons to do it
and a deprecation note when applicable.

## Thanks

Thank you to all who have contributed in this great project.
