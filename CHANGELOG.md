# Changelog

Welcome to the changelog for git-sumi-action. This document aims to provide a comprehensive list of all notable changes made to the project, organised chronologically by release version.

We use Semantic Versioning (SemVer) for our version numbers, formatted as MAJOR.MINOR.PATCH. Major version changes involve significant (breaking) changes, minor versions introduce features and improvements in a backward compatible manner, and patch versions are for bug fixes and minor tweaks.

## [0.1.0](https://github.com/welpo/git-sumi-action/compare/v0.0.9..v0.1.0) - 2025-07-05

### ✨ Features

- Update git-sumi to 0.1.0 ([d91d895](https://github.com/welpo/git-sumi-action/commit/d91d8953e7036152ac50ce23616283741e79d487))

### 🔧 Miscellaneous tasks

- *(CI)* Add concurrency control to sumi action ([6debf44](https://github.com/welpo/git-sumi-action/commit/6debf448ec10a2a910c5d70f7dab5009422db0d7)) by [@welpo](https://github.com/welpo)
- *(CI)* Fix 'contains' not 'starts with' for PR titles ([0f4c117](https://github.com/welpo/git-sumi-action/commit/0f4c11736ee4f0a80bbefc79a0ecd3a89b5a0f31)) by [@welpo](https://github.com/welpo)
- *(deps)* Remove local release script ([b9916a6](https://github.com/welpo/git-sumi-action/commit/b9916a62b61461de652f14c41d2ad6149f93141f)) by [@welpo](https://github.com/welpo)
- *(deps)* Replace local release script w/ git submodule ([f1eb7e8](https://github.com/welpo/git-sumi-action/commit/f1eb7e88dd622ddb540b722ad6d399b3b47046ba)) by [@welpo](https://github.com/welpo)
- *(release)* Improve script robustness ([4d7477d](https://github.com/welpo/git-sumi-action/commit/4d7477d8603a275450b65ca14ced3c610423ca7e)) by [@welpo](https://github.com/welpo)
- Update git-cliff variables to `commit.remote` ([d0db8c9](https://github.com/welpo/git-sumi-action/commit/d0db8c94afa966c80d15e54421e91203e443598c)) by [@welpo](https://github.com/welpo)

### 👥 New contributors

🫶 [@renovate](https://github.com/renovate)[bot] made their first contribution in [#3](https://github.com/welpo/git-sumi-action/pull/3)

🫶 [@welpo](https://github.com/welpo) made their first contribution

## [0.0.9](https://github.com/welpo/git-sumi-action/compare/v0.0.6..v0.0.9) - 2024-05-08

### ✨ Features

- Update git-sumi to 0.0.9 ([765bc1d](https://github.com/welpo/git-sumi-action/commit/765bc1d41652507083651cca0275996b2bec2f99)) by [@welpo](https://github.com/welpo)

### 📝 Documentation

- *(README)* Add git-sumi badge ([cb61b0a](https://github.com/welpo/git-sumi-action/commit/cb61b0a03c4ad60e248bccd6de5480c42349191b)) by [@welpo](https://github.com/welpo)

### 🔧 Miscellaneous tasks

- *(CHANGELOG)* Improve emoji pattern ([45c400b](https://github.com/welpo/git-sumi-action/commit/45c400bff7868b329e52d65f8b42bf10986a0e95)) by [@welpo](https://github.com/welpo)
- *(CI)* Use CHANGES.md for GitHub release notes ([24bd379](https://github.com/welpo/git-sumi-action/commit/24bd379fa70392a05b2dd5ccdfbf5bc62e59c338)) by [@welpo](https://github.com/welpo)
- *(CI)* Update git-sumi config ([0ae017a](https://github.com/welpo/git-sumi-action/commit/0ae017a2add329cdf80fa7944a011740b92e468b)) by [@welpo](https://github.com/welpo)
- *(git-sumi)* Improve emoji matching ([3c27955](https://github.com/welpo/git-sumi-action/commit/3c27955270954ce3877b3603a04db544e16d9081)) by [@welpo](https://github.com/welpo)
- *(git-sumi)* Require a space after the gitmoji ([2157294](https://github.com/welpo/git-sumi-action/commit/2157294709714d03eb4632c2f02dbffbcdad98aa)) by [@welpo](https://github.com/welpo)
- *(release)* Replace both pull and issue links ([ed0c46d](https://github.com/welpo/git-sumi-action/commit/ed0c46d0fd7f6acc323f991465ecc5a7afa44d24)) by [@welpo](https://github.com/welpo)
- *(release)* Update CHANGELOG format ([8c7966b](https://github.com/welpo/git-sumi-action/commit/8c7966b1096f6a6de9d5a2410854248c29780d05)) by [@welpo](https://github.com/welpo)
- *(release)* Verify version tag format on release ([ab926c9](https://github.com/welpo/git-sumi-action/commit/ab926c98f6563868537f03f5aa870113973672c8)) by [@welpo](https://github.com/welpo)
- Add continuous deployment workflow ([92c719b](https://github.com/welpo/git-sumi-action/commit/92c719bb5aa910169cc7b3a11ea2572ea32ccbe2)) by [@welpo](https://github.com/welpo)

## [0.0.6](https://github.com/welpo/git-sumi-action/compare/v0.0.2..v0.0.6) - 2024-02-06

### ✨ Features

- Install pre-compiled binary ([b24a513](https://github.com/welpo/git-sumi-action/commit/b24a513203f0c54acb8292fdf7d40d9923644cdd)) by [@welpo](https://github.com/welpo)
- Improve summary format ([6799437](https://github.com/welpo/git-sumi-action/commit/6799437971d36cf5897694d2262dc799b326824a)) by [@welpo](https://github.com/welpo)

### 🐛 Bug fixes

- Actually use the binary, not the directory ([8036579](https://github.com/welpo/git-sumi-action/commit/8036579a3154c6fed137d5487866723564bbf7cb)) by [@welpo](https://github.com/welpo)
- Force quiet=false to get proper summary ([42635d2](https://github.com/welpo/git-sumi-action/commit/42635d2183cc6b0c6a3bd84e20b7a74f4871ee19)) by [@welpo](https://github.com/welpo)

### 📝 Documentation

- *(README)* Add spacing below logo ([328f35f](https://github.com/welpo/git-sumi-action/commit/328f35fdfee3ce38c06403a6f72ad714bf12cccc)) by [@welpo](https://github.com/welpo)

### ♻️ Refactor

- Remove checkmark from summary header ([111baff](https://github.com/welpo/git-sumi-action/commit/111baff6f464217fc83e95f0e7419b0d56d06e3f)) by [@welpo](https://github.com/welpo)

### 🔧 Miscellaneous tasks

- *(CHANGELOG)* Update grouping ([0aaec02](https://github.com/welpo/git-sumi-action/commit/0aaec02881d3e45b5341a4c46b2b3be8e2af09e8)) by [@welpo](https://github.com/welpo)
- *(CI)* Rename git-sumi job ([aed6b78](https://github.com/welpo/git-sumi-action/commit/aed6b78378edaf3fe14b432aec2cb91a37ba961e)) by [@welpo](https://github.com/welpo)
- *(release)* Check for clean working directory ([eda2d8d](https://github.com/welpo/git-sumi-action/commit/eda2d8d0a585e7aba00b2ac28eea9dbe5fd860d5)) by [@welpo](https://github.com/welpo)

## 0.0.2 - 2024-02-04

### ✨ Features

- Add markdown summary ([d3c864d](https://github.com/welpo/git-sumi-action/commit/d3c864de8fd4d398159260252a8f39ce2a7087d7)) by [@welpo](https://github.com/welpo)
- Initial commit ([cc32032](https://github.com/welpo/git-sumi-action/commit/cc3203223fe8921197ae00b0621fc1671388bdb1)) by [@welpo](https://github.com/welpo)

### ♻️ Refactor

- Install git-sumi from cargo, not pypi ([b3c3af4](https://github.com/welpo/git-sumi-action/commit/b3c3af4f91afd47e2fbe038503ba04934ce21b91)) by [@welpo](https://github.com/welpo)

### 🔧 Miscellaneous tasks

- *(CI)* Fix links in tag description ([9cbffab](https://github.com/welpo/git-sumi-action/commit/9cbffabc0cc6f4ea32d478e26293c9e6c47c6a07)) by [@welpo](https://github.com/welpo)
- *(renovate)* Move config file ([6ed03c3](https://github.com/welpo/git-sumi-action/commit/6ed03c30d391ea7bbd19f867d6abf1210fc1cddd)) by [@welpo](https://github.com/welpo)
- *(sumi)* Update display format ([9f88b9a](https://github.com/welpo/git-sumi-action/commit/9f88b9a73a08529e40c04bf4c85e3529cbabab77)) by [@welpo](https://github.com/welpo)

### 👥 New contributors

🫶 [@welpo](https://github.com/welpo) made their first contribution

<!-- generated by git-cliff -->
