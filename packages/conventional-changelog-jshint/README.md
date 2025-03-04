# conventional-changelog-jshint

[![NPM version][npm]][npm-url]
[![Node version][node]][node-url]
[![Dependencies status][deps]][deps-url]
[![Build status][build]][build-url]
[![Coverage status][coverage]][coverage-url]

[npm]: https://img.shields.io/npm/v/conventional-changelog-jshint.svg
[npm-url]: https://npmjs.com/package/conventional-changelog-jshint

[node]: https://img.shields.io/node/v/conventional-changelog-jshint.svg
[node-url]: https://nodejs.org

[deps]: https://img.shields.io/librariesio/release/npm/conventional-changelog-jshint
[deps-url]: https://libraries.io/npm/conventional-changelog-jshint/tree

[build]: https://img.shields.io/github/actions/workflow/status/conventional-changelog/conventional-changelog/ci.yaml?branch=master
[build-url]: https://github.com/conventional-changelog/conventional-changelog/actions

[coverage]: https://coveralls.io/repos/github/conventional-changelog/conventional-changelog/badge.svg?branch=master
[coverage-url]: https://coveralls.io/github/conventional-changelog/conventional-changelog?branch=master

[conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) [jshint](https://github.com/jshint/jshint) preset.

**Issues with the convention itself should be reported on the JSHint issue tracker.**

## Install

```bash
# yarn
yarn add -D conventional-changelog-jshint
# pnpm
pnpm add -D conventional-changelog-jshint
# npm
npm i -D conventional-changelog-jshint
```

## JSHint Convention

### Overview

Commit messages are written in a simple format which clearly describes the purpose of a change.

The format in general should look like this:

```
[[TYPE]] <Short description>
<Blank line>

<Body / Detailed description>

<Footer>
```

Line lengths in commit messages are not strict, but good commit messages should have headers of no
more than 60 characters, and bodies/footers wrapped at 100 columns. This renders nicely on Github's
UI.

### Header

The first line is the commit message header, which will indicate the type of change, and a general
description of the change. This should fit within 60 characters, ideally. For instance:

```
[[FIX]] Ignore "nocomma" when parsing object literals
```

The title `[[FIX]]` indicates that the change is a bugfix, while the remainder clarifies what the
change actually contains.

Several commit types are used by jshint:

1. `[[FIX]]` --- Commit fixes a bug or regression
2. `[[FEAT]]` --- Commit introduces new functionality
3. `[[DOCS]]` --- Commit modifies documentation. Docs commits should only touch comments in source code, or scripts and assets which are used to generate the documentation.
4. `[[TEST]]` --- Commit modifies tests or test infrastructure only
5. `[[CHORE]]` --- Commit affects dev-ops, CI, or package dependencies

### Body

`<Body>` is a detailed commit message explaining exactly what has changed, and a summary of the
reason why. Lines in the body should be wrapped to 100 characters for best rendering.

For a historical example, see this [example](https://github.com/jshint/jshint/commit/5751c5ed249b7a035758a3ae876cfa1a360fd144)

### Footer

`<Footer>` contains a description of any breaking changes, no matter how subtle, as well as a list
of issues affected or fixed by this commit. Lines in the footer should be wrapped to 100 characters
for best rendering.

For instance:

```
[[FEAT]] Enable `norecurs` option by default

Commit 124124a7f introduced an option which forbids recursion. We liked it so much, we've enabled
it by default.

BREAKING CHANGE:

This change will break the CI builds of many applications and frameworks.

In order to work around this issue, you will need to re-engineer your applications and frameworks
to avoid making recursive calls. Use Arrays as stacks rather than relying on the VM call stack.

Fixes #1000009
Closes #888888
Closes #77777
```

Based on https://github.com/jshint/jshint/blob/master/CONTRIBUTING.md#commit-message-guidelines
