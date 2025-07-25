<!-- markdownlint-disable MD013 -->
# Changelog

Notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

This file is automatically updated by Release Please.

## [2.16.2](https://github.com/albertomh/pycliche/compare/v2.16.1...v2.16.2) (2025-06-25)


### Bug Fixes

* Ensure setuptools can find the app package ([#123](https://github.com/albertomh/pycliche/issues/123)) ([bcae014](https://github.com/albertomh/pycliche/commit/bcae0147e1b0376a7bded7f7a4bf78112ad7a369))

## [2.16.1](https://github.com/albertomh/pycliche/compare/v2.16.0...v2.16.1) (2025-06-17)


### Dependencies

* **ci:** Bump stefanzweifel/git-auto-commit-action from 5 to 6 ([#120](https://github.com/albertomh/pycliche/issues/120)) ([5f0a473](https://github.com/albertomh/pycliche/commit/5f0a473b6ae8946c55f3d9ed66bd3e3bb8af3448))


### Documentation

* Document nox and matrix strategy for test automation across Python versions ([#121](https://github.com/albertomh/pycliche/issues/121)) ([2f4b8f1](https://github.com/albertomh/pycliche/commit/2f4b8f186fbe8edbc7580dce6df814f6f2fe20eb))
* Update pycliche logo ([#118](https://github.com/albertomh/pycliche/issues/118)) ([78afa5e](https://github.com/albertomh/pycliche/commit/78afa5e740d9031abc51c849537308f886369063))

## [2.16.0](https://github.com/albertomh/pycliche/compare/v2.15.0...v2.16.0) (2025-06-11)


### Features

* **deps:** Bump nox in project template's GitHub Actions ([#114](https://github.com/albertomh/pycliche/issues/114)) ([e112d79](https://github.com/albertomh/pycliche/commit/e112d7927117ad077a6629308e53e8c8c6551860))
* **deps:** Update pre-commit hooks in project template ([#115](https://github.com/albertomh/pycliche/issues/115)) ([13ba18d](https://github.com/albertomh/pycliche/commit/13ba18d285bf99174952d9b59ec3ab6cc759777c))

## [2.15.0](https://github.com/albertomh/pycliche/compare/v2.14.2...v2.15.0) (2025-04-26)


### Features

* **ci:** Run tests using nox & a matrix strategy in gen. project ([#107](https://github.com/albertomh/pycliche/issues/107)) ([817c647](https://github.com/albertomh/pycliche/commit/817c6479047499d01385b8a28e514d142b599257))

## [2.14.2](https://github.com/albertomh/pycliche/compare/v2.14.1...v2.14.2) (2025-03-19)


### Bug Fixes

* **ci:** Install project before running unit tests in CI ([#102](https://github.com/albertomh/pycliche/issues/102)) ([468cf46](https://github.com/albertomh/pycliche/commit/468cf46f12d4aba9fd366bc3e0de6992e3b17ae5))
* Have structlog properly serialize unicode characters ([#100](https://github.com/albertomh/pycliche/issues/100)) ([5d90830](https://github.com/albertomh/pycliche/commit/5d90830709cf9fb008a1c32d7d7d7849442e225e))

## [2.14.1](https://github.com/albertomh/pycliche/compare/v2.14.0...v2.14.1) (2025-03-18)


### Documentation

* Add shields to generated projects' README ([#98](https://github.com/albertomh/pycliche/issues/98)) ([beff5ea](https://github.com/albertomh/pycliche/commit/beff5ea37ba12ee670ad75a14bdcbdd8b869818f))

## [2.14.0](https://github.com/albertomh/pycliche/compare/v2.13.1...v2.14.0) (2025-03-18)


### Features

* **ci:** Update uv.lock as part of Release Please action ([#96](https://github.com/albertomh/pycliche/issues/96)) ([4c8c823](https://github.com/albertomh/pycliche/commit/4c8c823542b450579eacf42d50bfa0612341c82e))
* **deps:** Update ipython to v9 in project template ([#92](https://github.com/albertomh/pycliche/issues/92)) ([4aa5a30](https://github.com/albertomh/pycliche/commit/4aa5a3089502f7f2aa1539d9e043df25a6732968))
* **deps:** Update pre-commit hooks in project template ([#93](https://github.com/albertomh/pycliche/issues/93)) ([d626e3b](https://github.com/albertomh/pycliche/commit/d626e3bd4fbb753344c9be388cb78451f405958e))
* **deps:** Update structlog to v25 in project template ([#90](https://github.com/albertomh/pycliche/issues/90)) ([97b1896](https://github.com/albertomh/pycliche/commit/97b18964d5e1adc72906a1de75e347c2f95a96c2))


### Bug Fixes

* **ci:** Avoid redundant 'CI' workflow if merged PR was from Release Please ([#95](https://github.com/albertomh/pycliche/issues/95)) ([3c15910](https://github.com/albertomh/pycliche/commit/3c15910c0512b2ab797ae46ce5efaaccb377bcf3))

## [2.13.1](https://github.com/albertomh/pycliche/compare/v2.13.0...v2.13.1) (2025-01-21)


### Bug Fixes

* Ensure a venv exists as part of the 'just test' recipe ([#86](https://github.com/albertomh/pycliche/issues/86)) ([46a4f07](https://github.com/albertomh/pycliche/commit/46a4f0789de196f919d6138f679870be07b5efc4))

## [2.13.0](https://github.com/albertomh/pycliche/compare/v2.12.1...v2.13.0) (2025-01-20)


### Features

* Add flake8-logging-format as a ruff linter rule ([#82](https://github.com/albertomh/pycliche/issues/82)) ([e4f36ee](https://github.com/albertomh/pycliche/commit/e4f36ee713934cfaec005fb1579b53fb4f1a33f2))


### Bug Fixes

* Formatting is consistent in gen. project's .pre-commit-config.yaml ([#84](https://github.com/albertomh/pycliche/issues/84)) ([1a4db0b](https://github.com/albertomh/pycliche/commit/1a4db0be3d74ac3b00cf7bd2b931f9d1f1ca99c9))

## [2.12.1](https://github.com/albertomh/pycliche/compare/v2.12.0...v2.12.1) (2025-01-16)


### Bug Fixes

* Install the project in editable mode as part of the 'test' recipe ([#80](https://github.com/albertomh/pycliche/issues/80)) ([aa443e6](https://github.com/albertomh/pycliche/commit/aa443e605bb561a0d80b00fbf4f19be22aa76d48))

## [2.12.0](https://github.com/albertomh/pycliche/compare/v2.11.0...v2.12.0) (2025-01-09)


### Features

* Generated project's entrypoint issues a structlog message ([#75](https://github.com/albertomh/pycliche/issues/75)) ([2c17615](https://github.com/albertomh/pycliche/commit/2c17615f32b12c29b88358ba75399bf9aadcce16))

## [2.11.0](https://github.com/albertomh/pycliche/compare/v2.10.1...v2.11.0) (2025-01-08)


### Features

* Bump version of pre-commit hooks used by template ([#73](https://github.com/albertomh/pycliche/issues/73)) ([16dbe5b](https://github.com/albertomh/pycliche/commit/16dbe5b9cbaa3032b3b6d43b7e37fc8c7f457991))


### Documentation

* In changelog, mention it is maintained by Release Please ([#71](https://github.com/albertomh/pycliche/issues/71)) ([cf2d774](https://github.com/albertomh/pycliche/commit/cf2d774ad01e335df1aa58b9f0dddf3c8cfd19e7))

## [2.10.1](https://github.com/albertomh/pycliche/compare/v2.10.0...v2.10.1) (2024-12-17)


### Bug Fixes

* Editorconfig ignores trailing whitespace in markdown files ([#69](https://github.com/albertomh/pycliche/issues/69)) ([27f7e40](https://github.com/albertomh/pycliche/commit/27f7e40d5be52895028b47492cde43f7f377e1c5))

## [2.10.0](https://github.com/albertomh/pycliche/compare/v2.9.1...v2.10.0) (2024-12-15)


### Features

* Add json, case-conflict pre-commit hooks to project template ([#65](https://github.com/albertomh/pycliche/issues/65)) ([359dc26](https://github.com/albertomh/pycliche/commit/359dc2661c3577f54053987bf69a39d2688ab22b))
* Add pytest marks to pyproject.toml in project template ([#63](https://github.com/albertomh/pycliche/issues/63)) ([c787b93](https://github.com/albertomh/pycliche/commit/c787b9343fb4d546819f590cdbc6306d92970d59))

## [2.9.1](https://github.com/albertomh/pycliche/compare/v2.9.0...v2.9.1) (2024-12-14)


### Documentation

* Add new wordmark to README ([#58](https://github.com/albertomh/pycliche/issues/58)) ([b28cac0](https://github.com/albertomh/pycliche/commit/b28cac0884396bce5258f783a5bf23806d10f983))

## [2.9.0](https://github.com/albertomh/pycliche/compare/v2.8.0...v2.9.0) (2024-12-13)


### Features

* Add pyupgrade pre-commit hook to project template ([8c96924](https://github.com/albertomh/pycliche/commit/8c96924969dff1224e5c5821cbde238fb4963977))
* Add structlog to the project template ([#52](https://github.com/albertomh/pycliche/issues/52)) ([67452be](https://github.com/albertomh/pycliche/commit/67452bef8c4c0515efb43ddd7f213c4dba255312))
* Pre-commit hook to guard against committing merge conflict markers ([#55](https://github.com/albertomh/pycliche/issues/55)) ([fc16acc](https://github.com/albertomh/pycliche/commit/fc16accfce521cf199a4979d77a14be588151b22))


### Bug Fixes

* Indentation issue in project template's .pre-commit-config.yaml ([#51](https://github.com/albertomh/pycliche/issues/51)) ([e149593](https://github.com/albertomh/pycliche/commit/e149593b96694e6f81cee0bd0befcd5faaf55bdd))

## [2.8.0](https://github.com/albertomh/pycliche/compare/v2.7.0...v2.8.0) (2024-12-11)


### Features

* Enable additional flake8 plugin rules for ruff linter in project template ([#48](https://github.com/albertomh/pycliche/issues/48)) ([62c3a6f](https://github.com/albertomh/pycliche/commit/62c3a6fba45cc229ae15ae1d40f69c6d54dda996))
* Enable flake8-bandit linting rules for ruff in project template ([#47](https://github.com/albertomh/pycliche/issues/47)) ([ede56c1](https://github.com/albertomh/pycliche/commit/ede56c18be5670a1bde738ba0fd648f90d1a2798))
* Enable flake8-bugbear linting rules for ruff in project template ([#45](https://github.com/albertomh/pycliche/issues/45)) ([9fa4c5e](https://github.com/albertomh/pycliche/commit/9fa4c5e259b08cf1626a20c56f5832161ca35bfa))

## [2.7.0](https://github.com/albertomh/pycliche/compare/v2.6.0...v2.7.0) (2024-12-11)


### Features

* Add IPython as the default shell for generated projects ([#41](https://github.com/albertomh/pycliche/issues/41)) ([e500d34](https://github.com/albertomh/pycliche/commit/e500d34fa7ad234351f9e2d8691ea3765e97b11f))
* Configure pytest to use ipdb as default debugger ([#43](https://github.com/albertomh/pycliche/issues/43)) ([8dc801a](https://github.com/albertomh/pycliche/commit/8dc801a7beec532b2e6f2ef4723ca04c6ff6eda0))

## [2.6.0](https://github.com/albertomh/pycliche/compare/v2.5.0...v2.6.0) (2024-12-10)


### Features

* Update ruff, commitlint, markdownlint pre-commit hooks in project template ([#38](https://github.com/albertomh/pycliche/issues/38)) ([b20ccc6](https://github.com/albertomh/pycliche/commit/b20ccc62e52773a03783ebd389dafbe7d65bb0ca))

## [2.5.0](https://github.com/albertomh/pycliche/compare/v2.4.1...v2.5.0) (2024-11-30)


### Features

* Regex validator for the author_email question ([#37](https://github.com/albertomh/pycliche/issues/37)) ([45d8690](https://github.com/albertomh/pycliche/commit/45d869031289da0115c2a19a5de223952e613439))
* Regex validator for the project_name question ([#35](https://github.com/albertomh/pycliche/issues/35)) ([1b45246](https://github.com/albertomh/pycliche/commit/1b452468d50d27821a56a276eeeee58c38f319ca))

## [2.4.1](https://github.com/albertomh/pycliche/compare/v2.4.0...v2.4.1) (2024-11-29)


### Bug Fixes

* __version__ sourced from metadata instead of being hardcoded ([#33](https://github.com/albertomh/pycliche/issues/33)) ([a7cec2f](https://github.com/albertomh/pycliche/commit/a7cec2f8a49ff172e775dd44001a253e00075ca0))

## [2.4.0](https://github.com/albertomh/pycliche/compare/v2.3.0...v2.4.0) (2024-11-28)


### Features

* Init git repo and generate uv lockfile after creating a project ([#32](https://github.com/albertomh/pycliche/issues/32)) ([933101e](https://github.com/albertomh/pycliche/commit/933101e527209d1147fa59482ef4816f4a70c45c))


### Documentation

* Add demo of generating project using 2.3.0 to README ([#27](https://github.com/albertomh/pycliche/issues/27)) ([d59449b](https://github.com/albertomh/pycliche/commit/d59449beee6fbb0d74a25ac596cdac0e4a4d1d86))
* Updating dependencies in the template ([#31](https://github.com/albertomh/pycliche/issues/31)) ([a400a1e](https://github.com/albertomh/pycliche/commit/a400a1ea3e8506a71b77d666578a5cb0a5070e43))

## [2.3.0](https://github.com/albertomh/pycliche/compare/v2.2.0...v2.3.0) (2024-11-27)


### Features

* Add 'is_github_project' as a question ([cc53de5](https://github.com/albertomh/pycliche/commit/cc53de5e3301379d13630a4d56921293fddbf677))
* Make .github/ and Release Please config conditional on 'is_github_project' ([6a4df3f](https://github.com/albertomh/pycliche/commit/6a4df3f19310358e775051cd8deb1dd73972e3ca))
* Make template README sections conditional on 'is_github_project' ([8a68477](https://github.com/albertomh/pycliche/commit/8a68477b4c0b13b85f9415b51c22c6a79773ae78))
* Upgrade 'ruff' & 'bandit' git hooks in template ([#26](https://github.com/albertomh/pycliche/issues/26)) ([006c1f3](https://github.com/albertomh/pycliche/commit/006c1f3d8edbac54871c27f5017fd0d1b6b04d3e))


### Bug Fixes

* Populate 'tool.ruff.target-version' in generated pyproject.toml ([ced39ee](https://github.com/albertomh/pycliche/commit/ced39ee194ffd544351a6a834d638715f0932d78))


### Dependencies

* Add copier as a test dependency ([c4b8279](https://github.com/albertomh/pycliche/commit/c4b827935459a5110077c6b29cb7af3b469f5bc9))


### Documentation

* Document which features of generated projects are conditional on 'is_github_project' ([cb35680](https://github.com/albertomh/pycliche/commit/cb35680e51687ce8134f19a4a8320856436649d2))

## [2.2.0](https://github.com/albertomh/pycliche/compare/v2.1.1...v2.2.0) (2024-11-26)


### Features

* Add dependabot config for Python packages & GitHub actions ([#17](https://github.com/albertomh/pycliche/issues/17)) ([5f92b34](https://github.com/albertomh/pycliche/commit/5f92b34a698eb2ee3a964818af1ab28b73d73f52))
* Add pre-commit & pytest GitHub Actions to template ([#23](https://github.com/albertomh/pycliche/issues/23)) ([db3612f](https://github.com/albertomh/pycliche/commit/db3612f9fe1cd269ad13a6148df0ef5979e6ee3c))
* Markdownlint ignores changelog since generated by 'Release Please' ([6b33f16](https://github.com/albertomh/pycliche/commit/6b33f168cccfc32f462e4094cb397ea570101661))


### Dependencies

* Add pytest as a test dependency ([d947538](https://github.com/albertomh/pycliche/commit/d94753853ece8bd39ba46ad0d00f3511f5d95f4e))


### Documentation

* Document how to update existing project to newer version of pycliche ([7b18656](https://github.com/albertomh/pycliche/commit/7b1865646aa06ec94b977471d4cc94a2c4a6475c))
* Readme section on running pytest tests ([0becfbf](https://github.com/albertomh/pycliche/commit/0becfbfe32051447f69c72db4ac777cea9043422))

## [2.1.1](https://github.com/albertomh/pycliche/compare/v2.1.0...v2.1.1) (2024-11-25)


### Bug Fixes

* Tag format in project template's 'Release Please manifest' ([#16](https://github.com/albertomh/pycliche/issues/16)) ([deb0572](https://github.com/albertomh/pycliche/commit/deb05726005f2b63d2cdafe550fb8037a17f8a05))


### Documentation

* Document release process and use of Release Please ([#13](https://github.com/albertomh/pycliche/issues/13)) ([16f86cb](https://github.com/albertomh/pycliche/commit/16f86cb714006c7687581b433f0080ee1f25b3f3))
* Document the GitHub PAT needed to automate Release Please ([824f848](https://github.com/albertomh/pycliche/commit/824f8483927714809c5d86398bcf732515b1e31b))

## [2.1.0](https://github.com/albertomh/pycliche/compare/v2.0.0...v2.1.0) (2024-11-24)

### Features

* Add Release Please config & GitHub Action to the project template ([#12](https://github.com/albertomh/pycliche/issues/12)) ([2247823](https://github.com/albertomh/pycliche/commit/224782304359d35a1e995f43d3c748460249478f))

### Bug Fixes

* Add 'deps' as a valid commit type in the project template ([#10](https://github.com/albertomh/pycliche/issues/10)) ([59e29f1](https://github.com/albertomh/pycliche/commit/59e29f1fcf1d1b1cdc9d56b6f4e5e3d80985a034))

## [2.0.0](https://github.com/albertomh/pycliche/compare/v1.0.0...v2.0.0) (2024-11-23)

### Added

* copier.yaml config file.

### Changed

* **BREAKING**: Switch from cookiecutter to copier as the project templating tool.

### Removed

* cookiecutter.json config file.

## [1.0.0](https://github.com/albertomh/pycliche/releases/tag/v1.0.0) (2024-11-17)

### Added

* Project template package structure and entrypoint.
* cookiecutter.json config file.
* Minimal unit test suite structure. Configuration for running tests and reporting on coverage.
* git hooks for both pycliché and the project template, including:
  * commitlint
  * ruff (linter & formatter)
  * bandit (SAST)
