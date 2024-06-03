# Changelog

## [2.0.5](https://github.com/cerebruminc/fast-forward-action/compare/v2.0.4...v2.0.5) (2024-06-03)


### Bug Fixes

* github actions CI workflow name ([#36](https://github.com/cerebruminc/fast-forward-action/issues/36)) ([0869aa8](https://github.com/cerebruminc/fast-forward-action/commit/0869aa8d006d1b97c48dad45387e2dadad89a7e6))

## [2.0.4](https://github.com/cerebruminc/fast-forward-action/compare/v2.0.3...v2.0.4) (2024-02-19)


### Bug Fixes

* only allow certain users to fast forward merge ([5817ed0](https://github.com/cerebruminc/fast-forward-action/commit/5817ed05f7fc54a58f1a0aac5ad648fc9dfadd6b))

## [2.0.3](https://github.com/cerebruminc/fast-forward-action/compare/v2.0.2...v2.0.3) (2024-02-16)


### Bug Fixes

* set user and email for rp tags ([72bae72](https://github.com/cerebruminc/fast-forward-action/commit/72bae72e29b547a993ed17a041b3c95d69ffccd8))

## [2.0.2](https://github.com/cerebruminc/fast-forward-action/compare/v2.0.1...v2.0.2) (2024-02-16)


### Bug Fixes

* checkout code before generating floating tags ([084eef4](https://github.com/cerebruminc/fast-forward-action/commit/084eef4b44cecaac33b1fd6add455c3649d6d893))

## [2.0.1](https://github.com/cerebruminc/fast-forward-action/compare/v2.0.0...v2.0.1) (2024-02-16)


### Bug Fixes

* create floating major and minor tags ([cb075b8](https://github.com/cerebruminc/fast-forward-action/commit/cb075b8ec3304943668ca3b1c62d97840d098778))

## [2.0.0](https://github.com/cerebruminc/fast-forward-action/compare/v1.0.0...v2.0.0) (2024-02-16)


### ⚠ BREAKING CHANGES

* merge scripts into a single workflow
* do not rely on unnecessary inputs

### Code Refactoring

* do not rely on unnecessary inputs ([323af99](https://github.com/cerebruminc/fast-forward-action/commit/323af99e0a14d84f51455b04763b74482e648a1f))
* merge scripts into a single workflow ([2b5ac7e](https://github.com/cerebruminc/fast-forward-action/commit/2b5ac7e6adb181f4fa3e0a46f82dd48e4dcfa984))

## 1.0.0 (2024-02-16)


### Features

* adding demo to the branches ([11abdb7](https://github.com/cerebruminc/fast-forward-action/commit/11abdb78f91266d72ca77bc339a15470c80e2605))


### Bug Fixes

* add checkout actions ([0baa4ea](https://github.com/cerebruminc/fast-forward-action/commit/0baa4ea342d064f80c9e9f4635d4677198fbc490))
* add demo to comment-check as well ([3c02ba2](https://github.com/cerebruminc/fast-forward-action/commit/3c02ba2abe604fd08225687b4eb59152658ec650))
* authentication ([3b2e570](https://github.com/cerebruminc/fast-forward-action/commit/3b2e570e2a8c0207783e84bc5a8ba257bb8f7250))
* change url and how secret is passed ([99b7501](https://github.com/cerebruminc/fast-forward-action/commit/99b75016cabfae7e6f3f64a89eb4079edc047ae9))
* checkout action ([9199062](https://github.com/cerebruminc/fast-forward-action/commit/9199062f316990380e6e60fd2e2f1c6a2af9854b))
* checkout both branches ([cbd3688](https://github.com/cerebruminc/fast-forward-action/commit/cbd368810cb99f2d358dbedd0876bcfcc1be1d33))
* checkout track ([4409bec](https://github.com/cerebruminc/fast-forward-action/commit/4409bec3ffe2ec7082c5a9f36bbd5ea900a5bc90))
* choosing the branch to checkout ([6275a89](https://github.com/cerebruminc/fast-forward-action/commit/6275a89b6754bbc3c9d1b3dfd1ca37cce729bd90))
* conditional ([#6](https://github.com/cerebruminc/fast-forward-action/issues/6)) ([71ad488](https://github.com/cerebruminc/fast-forward-action/commit/71ad48828841160c2a0b4a7eb46cf508ca6408aa))
* credentials ([ba049e8](https://github.com/cerebruminc/fast-forward-action/commit/ba049e8b35c676682ad29d42820f88a6355fb622))
* debug COMMENT_EXISTS VARIABLE ([#9](https://github.com/cerebruminc/fast-forward-action/issues/9)) ([794a2ac](https://github.com/cerebruminc/fast-forward-action/commit/794a2aca9e39cb7fe2445a4eee6e47adb3a3fe2a))
* enabling the check-comment action to run on issue_comment events ([#11](https://github.com/cerebruminc/fast-forward-action/issues/11)) ([99d7d87](https://github.com/cerebruminc/fast-forward-action/commit/99d7d87ac79bc92f95b0a781d788b82b0bde493b))
* fix checkout ([e97199b](https://github.com/cerebruminc/fast-forward-action/commit/e97199b257c0addda65cfaad7eb99d010b35ec6e))
* folder structure ([2a56244](https://github.com/cerebruminc/fast-forward-action/commit/2a5624450d8404a34733df4c8f10950803c20754))
* getting base and compare branches from call to the GitHub API as well ([5bad52d](https://github.com/cerebruminc/fast-forward-action/commit/5bad52d0f02c202870227aee5caa44be53481e68))
* git config ([b59096a](https://github.com/cerebruminc/fast-forward-action/commit/b59096a8fa45e5fe15ce14071de3f38bd0b65be2))
* git switch instead of git checkout ([7fb68dc](https://github.com/cerebruminc/fast-forward-action/commit/7fb68dc66e862cccbf7aa586d28b0b25454113b9))
* merge pr condition ([1862de2](https://github.com/cerebruminc/fast-forward-action/commit/1862de22fbb96d4ad3d2f5300e5fe53fb553fc2b))
* move release-please workflow into correct folder ([394558f](https://github.com/cerebruminc/fast-forward-action/commit/394558f17974841b6554575899cf20b71aa4b785))
* move the base ref check to the action code ([#8](https://github.com/cerebruminc/fast-forward-action/issues/8)) ([9f9e1a0](https://github.com/cerebruminc/fast-forward-action/commit/9f9e1a0c7a8166cb7b1d276c966edbccd4f18a39))
* only operate if head_ref is master or main ([#4](https://github.com/cerebruminc/fast-forward-action/issues/4)) ([7d62f41](https://github.com/cerebruminc/fast-forward-action/commit/7d62f41e46ad986429fb782762c75f16f32483df))
* pass correct input to jq ([#10](https://github.com/cerebruminc/fast-forward-action/issues/10)) ([7c877b1](https://github.com/cerebruminc/fast-forward-action/commit/7c877b11c7db99e461886c7a937b6e5bccb0ddb5))
* pass mergefreeze token at beginning ([f5e192f](https://github.com/cerebruminc/fast-forward-action/commit/f5e192f11fc173851a0a8770e56bdf9216478caa))
* passing the token to the checkout action ([3e092cb](https://github.com/cerebruminc/fast-forward-action/commit/3e092cbbbbec6803fb875799ba5594bd91fb8c58))
* prevent parameter substitution inside EOF statements [security] ([9848f2f](https://github.com/cerebruminc/fast-forward-action/commit/9848f2ffe9091f6873c31d0fae5a7b24cf3bbc01))
* return true even if there are many fast-forward comments ([#7](https://github.com/cerebruminc/fast-forward-action/issues/7)) ([6ec9dda](https://github.com/cerebruminc/fast-forward-action/commit/6ec9dda2d32c574408934d9cb02d4108d8015e31))
* use contains function instead of direct comparison for refs ([#5](https://github.com/cerebruminc/fast-forward-action/issues/5)) ([f7c009d](https://github.com/cerebruminc/fast-forward-action/commit/f7c009d0a8efe1eb97bbd868513b18f8025b8bd9))
