# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [5.0.0](https://github.com/conventional-changelog/conventional-changelog/compare/conventional-commits-filter-v4.0.0...conventional-commits-filter-v5.0.0) (2023-10-14)


### ⚠ BREAKING CHANGES

* Now all packages, except gulp-conventional-changelog, are ESM-only.
* Now package exports CommitParser class and parseCommitsStream method for backward compatability. Options has minor changes in types, please read the docs.

### Features

* move from CommonJS to ESM ([#1144](https://github.com/conventional-changelog/conventional-changelog/issues/1144)) ([c5b859d](https://github.com/conventional-changelog/conventional-changelog/commit/c5b859d201e124822002eb54574f003f074216e2))
* **conventional-commits-parser** rewrite to TypeScript ([#1126](https://github.com/conventional-changelog/conventional-changelog/issues/1126)) ([9e280d8](https://github.com/conventional-changelog/conventional-changelog/commit/9e280d89f33e2185643e2531edb668bd0e0df22c))

## [4.0.0](https://github.com/conventional-changelog/conventional-changelog/compare/conventional-commits-filter-v3.0.0...conventional-commits-filter-v4.0.0) (2023-08-26)


### ⚠ BREAKING CHANGES

* Node >= 16 is required

### Features

* drop node 14 support ([#1085](https://github.com/conventional-changelog/conventional-changelog/issues/1085)) ([1bce036](https://github.com/conventional-changelog/conventional-changelog/commit/1bce0362dbb624a869eb01fd7724ab7f81d337e6))

## [3.0.0](https://github.com/conventional-changelog/conventional-changelog/compare/conventional-commits-filter-v2.0.7...conventional-commits-filter-v3.0.0) (2023-06-06)


### ⚠ BREAKING CHANGES

* Node >= 14 is required

### Bug Fixes

* align lodash dependency across packages ([#737](https://github.com/conventional-changelog/conventional-changelog/issues/737)) ([d9feeb6](https://github.com/conventional-changelog/conventional-changelog/commit/d9feeb605de28c00ef55b5c8e229efd1289dd6e8))
* **filter:** only remove commits that reverted commits in the scope ([#226](https://github.com/conventional-changelog/conventional-changelog/issues/226)) ([461dae6](https://github.com/conventional-changelog/conventional-changelog/commit/461dae6fa3f8566cca6049bfb7237932d95773b2))
* **filter:** replace `is-subset` with `lodash.ismatch` ([#377](https://github.com/conventional-changelog/conventional-changelog/issues/377)) ([fbcc92e](https://github.com/conventional-changelog/conventional-changelog/commit/fbcc92ec0f480c089f9ee45cc824ab6e628a01f0))


### Code Refactoring

* drop lodash from dependencies where it possible ([#959](https://github.com/conventional-changelog/conventional-changelog/issues/959)) ([a8b4e12](https://github.com/conventional-changelog/conventional-changelog/commit/a8b4e12883021231befc6bdfeb95a9b50637f361))

## [2.0.7](https://github.com/conventional-changelog/conventional-changelog/compare/conventional-commits-filter@2.0.6...conventional-commits-filter@2.0.7) (2020-11-05)

**Note:** Version bump only for package conventional-commits-filter





## [2.0.6](https://github.com/conventional-changelog/conventional-changelog/compare/conventional-commits-filter@2.0.2...conventional-commits-filter@2.0.6) (2020-05-08)

**Note:** Version bump only for package conventional-commits-filter





## [2.0.2](https://github.com/conventional-changelog/conventional-changelog/compare/conventional-commits-filter@2.0.1...conventional-commits-filter@2.0.2) (2019-04-10)


### Bug Fixes

* **filter:** replace `is-subset` with `lodash.ismatch` ([#377](https://github.com/conventional-changelog/conventional-changelog/issues/377)) ([fbcc92e](https://github.com/conventional-changelog/conventional-changelog/commit/fbcc92e))





## [2.0.1](https://github.com/conventional-changelog/conventional-changelog/compare/conventional-commits-filter@2.0.0...conventional-commits-filter@2.0.1) (2018-11-01)


### Bug Fixes

* Upgrade to Lerna 3, fix Node.js v11 error ([#385](https://github.com/conventional-changelog/conventional-changelog/issues/385)) ([cdef282](https://github.com/conventional-changelog/conventional-changelog/commit/cdef282))





<a name="2.0.0"></a>
# [2.0.0](https://github.com/conventional-changelog/conventional-changelog/compare/conventional-commits-filter@1.1.6...conventional-commits-filter@2.0.0) (2018-05-29)


### Chores

* **package:** set Node requirement to oldest supported LTS ([#329](https://github.com/conventional-changelog/conventional-changelog/issues/329)) ([cae2fe0](https://github.com/conventional-changelog/conventional-changelog/commit/cae2fe0))


### BREAKING CHANGES

* **package:** Set the package's minimum required Node version to be the oldest LTS
currently supported by the Node Release working group. At this time,
that is Node 6 (which is in its Maintenance LTS phase).




<a name="1.1.6"></a>
## [1.1.6](https://github.com/conventional-changelog/conventional-changelog/compare/conventional-commits-filter@1.1.5...conventional-commits-filter@1.1.6) (2018-03-22)




**Note:** Version bump only for package conventional-commits-filter

<a name="1.1.5"></a>
## [1.1.5](https://github.com/conventional-changelog/conventional-changelog/compare/conventional-commits-filter@1.1.4...conventional-commits-filter@1.1.5) (2018-02-24)




**Note:** Version bump only for package conventional-commits-filter

<a name="1.1.4"></a>
## [1.1.4](https://github.com/conventional-changelog/conventional-changelog/compare/conventional-commits-filter@1.1.3...conventional-commits-filter@1.1.4) (2018-02-20)




**Note:** Version bump only for package conventional-commits-filter

<a name="1.1.3"></a>
## [1.1.3](https://github.com/stevemao/conventional-commits-filter/compare/conventional-commits-filter@1.1.2...conventional-commits-filter@1.1.3) (2018-02-13)




**Note:** Version bump only for package conventional-commits-filter

<a name="1.1.2"></a>
## [1.1.2](https://github.com/stevemao/conventional-commits-filter/compare/conventional-commits-filter@1.1.1...conventional-commits-filter@1.1.2) (2018-02-13)




**Note:** Version bump only for package conventional-commits-filter

<a name="1.1.1"></a>
## [1.1.1](https://github.com/stevemao/conventional-commits-filter/compare/conventional-commits-filter@1.1.0...conventional-commits-filter@1.1.1) (2017-12-08)


### Bug Fixes

* **filter:** only remove commits that reverted commits in the scope ([#226](https://github.com/stevemao/conventional-commits-filter/issues/226)) ([461dae6](https://github.com/stevemao/conventional-commits-filter/commit/461dae6))




<a name="1.1.0"></a>
# 1.1.0 (2017-11-13)


### Features

* migrate repo to lerna mono-repo ([793e823](https://github.com/stevemao/conventional-commits-filter/commit/793e823))
