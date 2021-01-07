# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [9.1.0](https://github.com/itgalaxy/webfont/compare/v9.0.0...v9.1.0) (2021-01-07)


### Features

* add support to ligatures and JSON template ([f622c44](https://github.com/itgalaxy/webfont/commit/f622c44561534f1d997d2ebd82a08e00ca2af86c))
* **cli:** add support to `template-cache-string` argument ([ae8b050](https://github.com/itgalaxy/webfont/commit/ae8b0503506be2544cd5b5a5b0f2c420fec588b5))
* **demo:** add styl file example ([3aa5180](https://github.com/itgalaxy/webfont/commit/3aa5180a63fffc8d1067803e63ba9f35097009b9))
* **demo:** update fonts with ligatures support ([64b10d6](https://github.com/itgalaxy/webfont/commit/64b10d645f43c49f0ffe92ca2978739a3abb115c))
* **json template and template cache string:** add json built-in template, and templateCacheString which defaults to unix timestamp. ([1e43bba](https://github.com/itgalaxy/webfont/commit/1e43bba3e7aab537b2ff601c5205bd9b4b136734))
* **ligatures:** add ligature support ([9106a13](https://github.com/itgalaxy/webfont/commit/9106a139067141f9d57fe2726ff4f295af35e4b7))
* **standalone:** add support to JSON template and cacheString ([ad64421](https://github.com/itgalaxy/webfont/commit/ad64421a9da9cadbaba96e423cc00c1c6be76572))
* **templates:** add cacheString support ([f39d2c1](https://github.com/itgalaxy/webfont/commit/f39d2c1753f19474d1fc0defd7de37b5f9706ca5))
* **templates:** add template for JSON ([3b704b3](https://github.com/itgalaxy/webfont/commit/3b704b391682a99262c8ffd1a6c2c1bb22b5df58))
* add stylus template ([588a753](https://github.com/itgalaxy/webfont/commit/588a75320daead1e3340da18efd716d75db4d00d))
* allow adding a hash in generated font file name ([@brunoroux](https://github.com/brunoroux)) ([1913c9a](https://github.com/itgalaxy/webfont/commit/1913c9a87ea868810d7ceac9d6f203f13d90a6ea))
* allow to add a hash in generated font file name ([6ca0d9e](https://github.com/itgalaxy/webfont/commit/6ca0d9ea7cb190d677b03db8c591183cd93c9b19))
* respect `formats` option when using external config ([29769b0](https://github.com/itgalaxy/webfont/commit/29769b0b7f9b10a1ae77e49b813e3be494e9b699))


### Bug Fixes

* **cli:** use `fs` instead of `fs-extra` for writing files ([e7bf9f5](https://github.com/itgalaxy/webfont/commit/e7bf9f567be4aa370193d32f0a167841aa7b1567))
* **demo:** adopt `font-display: block` for a little better icon font loading ([0f9dbc0](https://github.com/itgalaxy/webfont/commit/0f9dbc012a65e0f05bec916986e27fa7322d6306))
* **deps:** [Snyk] Fix for 1 vulnerabilities ([6e08d33](https://github.com/itgalaxy/webfont/commit/6e08d332797128dbcfba70a2c11a2d1db6f72649)), closes [#197](https://github.com/itgalaxy/webfont/issues/197)
* **deps:** [Snyk] Fix for 1 vulnerable dependencies ([6e9e243](https://github.com/itgalaxy/webfont/commit/6e9e24369a7908c494c4fbf91eee5ccce212bd73)), closes [#188](https://github.com/itgalaxy/webfont/issues/188)
* **deps:** [Snyk] Security upgrade meow from 5.0.0 to 6.1.0 ([b5f9021](https://github.com/itgalaxy/webfont/commit/b5f9021d9327eaad8aeaf86ea95f80e70f47f9da)), closes [#195](https://github.com/itgalaxy/webfont/issues/195)
* **deps:** fix insecure dependency ([59a9604](https://github.com/itgalaxy/webfont/commit/59a96045b3ec2fd296ddc0c49d6ff856105617cb))
* **deps:** fix/sort deps and scripts after `npm audit fix` ([cf5cfc4](https://github.com/itgalaxy/webfont/commit/cf5cfc467ca4b4d62071b3bcc5b937878f655777)), closes [#209](https://github.com/itgalaxy/webfont/issues/209)
* **deps:** fix/sort deps and scripts after `npm audit fix` ([4118fcf](https://github.com/itgalaxy/webfont/commit/4118fcf5e816c2545bf149791c06457c5c27728f))
* **deps:** pin/upgrade eslint dependencies, fix some errors ([9206e72](https://github.com/itgalaxy/webfont/commit/9206e72ec9294373532968253fe4376a718986f6)), closes [#225](https://github.com/itgalaxy/webfont/issues/225)
* **deps:** sort/upgrade dependencies after npm audit fix ([0f976a9](https://github.com/itgalaxy/webfont/commit/0f976a930bb345af4401d4812bb37b7044c6a07d)), closes [#220](https://github.com/itgalaxy/webfont/issues/220)
* **deps:** sort/upgrade dependencies after npm audit fix ([a1ba509](https://github.com/itgalaxy/webfont/commit/a1ba50959b36763543787478b22e836852e8ab10))
* **deps:** upgrade `eslint` dependencies and plugins ([1e5a5ca](https://github.com/itgalaxy/webfont/commit/1e5a5cae0d4f488a45d076d9af6317135ab0ae7e))
* **templates:** adopt `font-display: block` for better icon font loading ([4669891](https://github.com/itgalaxy/webfont/commit/4669891dc9e10ce836c13c4e99f5c8357ab7ae51))
* .snyk, package.json & package-lock.json to reduce vulnerabilities ([2e387cc](https://github.com/itgalaxy/webfont/commit/2e387ccf780b79ae3efda07030f238e45eb43977))
* package.json & package-lock.json to reduce vulnerabilities ([b02f52f](https://github.com/itgalaxy/webfont/commit/b02f52fa77b495ef5e19f14e849d4f886a2f584b))
* package.json, package-lock.json & .snyk to reduce vulnerabilities ([c805812](https://github.com/itgalaxy/webfont/commit/c8058125bc1f7410c43c8d057f485c425aa739c9))
* package.json, package-lock.json & .snyk to reduce vulnerabilities ([791e5f4](https://github.com/itgalaxy/webfont/commit/791e5f4c56466853e97c5874d74ca52dfee1fd9a))
* package.json, package-lock.json & .snyk to reduce vulnerabilities ([8f037d5](https://github.com/itgalaxy/webfont/commit/8f037d50711d633d406a127ef76384662d40ff09))

## 9.0.0 - 2019-04-19

- Changed: drops support for Node.js 6.
- Feat: improve basic templates (see [templates](templates)).
- Feat: use wasm package for generate woff2

## 8.2.1 - 2018-12-28

- Chore: update dependencies.

## 8.2.0 - 2018-11-13

- Added: `sort` option (and `--no-sort` flag for CLI).
- Chore: update dependencies.

## 8.1.4 - 2018-06-05

- Chore: minimum require `svgicons2svgfont` version is now `^9.0.3` (this fix compatibility with `nodejs@10`).

## 8.1.3 - 2018-04-25

- Chore: minimum require `meow` version is now `^5.0.0`.
- Chore: minimum require `cosmiconfig` version is now `^5.0.3`.
- Chore: minimum require `fs-extra` version is now `^6.0.1`.
- Chore: drop `merge-deep` in favor `lodash.merge`.

## 8.1.2 - 2018-04-23

- Fixed: deterministic output (i.e. each glyph in font have same unicode in font).

## 8.1.1 - 2018-03-22

- Fixed: always configure `nunjucks` for template path.

## 8.1.0 - 2018-03-22

- Feat: export `config` path when he is using (in `result.config.filePath`).

## 8.0.0 - 2018-03-21

- Added: `demo` directory (thanks for [@shogo](https://github.com/ShogoFunaguchi)).
- Changed: export `glyphsData` instead `foundFiles` (`glyphsData` contain all information about any glyph).
- Changed: `result.styles` rename to `result.template` (for API).
- Changed: `dest` by default `process.cwd()`.
- Changed: rename `dest-styles` CLI option to `dest-template`.
- Changed: rename `cssTemplateClassName` to `templateClassName`.
- Changed: rename `cssTemplateFontPath` to `templateFontPath`.
- Changed: rename `cssTemplateFontName` to `templateFontName`.
- Changed: `glyphTransformFn` should always return glyph metadata.
- Changed: minimum required `nodejs` version is now `6.9.5` (see [svgicons2svgfont](https://github.com/nfroidure/svgicons2svgfont/blob/master/package.json#L41).
- Changed: use `globby@8` (based on `fast-glob`, it is better perf).
- Chore: minimum used `svgicons2svgfont` package is now `^9.0.2`
- Chore: minimum used `cosmiconfig` package is now `^4.0.0`
- Fixed: don't use `globby` for getting build-in tempalte (better perf).
- Fixed: always add trailing slash to `templateFontPath`.

## 7.1.4 - 2017-05-24

- Fixed: use `copyright`, `ts` and `version` with null value by default, it is avoid problems when your use long term caching.
- Fixed: options for `ttf` font generation now correctly handles.

## 7.1.3 - 2017-04-13

- Fixed: search config if not present in CLI arguments.

## 7.1.2 - 2017-04-12

- Fixed: `template` option now respected from config.

## 7.1.1 - 2017-03-29

- Fixed: potential crash with memory allocation when using `fs` for read files.

## 7.1.0 - 2017-01-24

- Added: `glyphTransformFn` option for transform glyph metadata before transferred in style template.

## 7.0.2 - 2016-12-22

- Fixed: exit code can be not number.

## 7.0.1 - 2016-12-20

- Fixed: arguments for svgicons2svgfont (missing font prefix).
- Chore: improved output of help in `CLI`.

## 7.0.0 - 2016-11-09

- Added: `template` option instead `css`, `cssFormat`, `srcCssTemplate`.
- Added: `destStyles` options instead `destCssTemplate`.
- Added: `styles` property to result.
- Fixed: throw error on empty `svg` files.
- Removed: `css` option.
- Removed: `cssFormat` option.
- Removed: `srcCssTemplate` option.
- Removed: `css` property from result.
- Removed: `destCssTemplate` argument from `cli`.
- Tests: improved tests (relative and absolute path to template).

## 6.0.4 - 2016-11-08

- Fixed: regression bug with passed arguments to template.

## 6.0.3 - 2016-11-08

- Fixed: validate `xml` of glyphs.
- Chore: minimum required `eslint-plugin-ava` version is now `^2.2.0`.
- Chore: minimum required `eslint-plugin-itgalaxy` version is now `^26.0.0`.
- Chore: minimum required `eslint-plugin-jsx-a11y` version is now `^3.0.0`.
- Chore: minimum required `eslint-plugin-react` version is now `^6.6.0`.
- Chore: refactoring code.

## 6.0.2 - 2016-11-07

- Fixed: use `reject` instead `Promise.reject` in glyphs `error` callback.
- Fixed: use callback `finish` instead `end` for `svgicons2svgfont` stream.
- Tests: improve tests on bad examples.

## 6.0.1 - 2016-11-07

- Fixed: add `error` event to `glyph` stream.
- Fixed: don't create `new Error` where this is not necessary.
- Chore: minimum required `nunjucks` version is now `^3.0.0`.
- Chore: minimum required `eslint` version is now `^3.9.1`.
- Chore: minimum required `eslint-plugin-ava` version is now `^4.0.0`.
- Chore: minimum required `eslint-plugin-itgalaxy` version is now `^25.0.0`.
- Chore: minimum required `eslint-plugin-node` version is now `^3.0.0`.
- Chore: minimum required `eslint-plugin-promise` version is now `^3.3.0`.
- Chore: minimum required `eslint-plugin-react` version is now `^6.5.0`.
- Tests: improve tests on bad examples.

## 6.0.0 - 2016-10-26

- Added: support `nodejs` `7`.
- Added: `verbose` argument for verbose output.
- Remove: `quite` argument.
- Chore: improve `README.md`.
- Chore: improve `description` in `package.json`.

## 5.0.0 - 2016-10-24

- Fixed: wrong `CSS` syntax when not all format are selected.
- Chore(SEMVER-MAJOR): rename extension for all templates from `nunjucks` to `njk`.

## 4.0.1 - 2016-10-19

- Fixed: CLI `fontName` and `formats` arguments bug.
- Chore: minimum required `ajv-cli` version is now `^1.1.0`.
- Chore: minimum required `remark-preset-lint-itgalaxy` version is now `^2.0.0`.
- Chore: minimum required `nunjucks` from `2.0.0` to `2.5.0`.
- Chore: minimum required `eslint-plugin-import` version is now `^2.0.0`.
- Chore: minimum required `eslint-plugin-promise` version is now `^3.0.0`.
- Chore: minimum required `eslint-plugin-lodash` version is now `^2.1.0`.
- Chore: rename `eslint-plugin-xo` to `eslint-plugin-unicorn`.
- Chore: minimum required `eslint-plugin-unicorn` version is now `^1.0.0`.
- Chore: minimum required `eslint-plugin-itgalaxy` version is now `^23.0.0`.
- Chore: minimum required `cosmiconfig` version is now `^2.0.0`.

## 4.0.0

- Changed: all style templates for font now have `nunjucks` extension.
- Chore(package): remove extra `files` from `package.json`.
- Chore(package): install all `peerDependencies` for `eslint-plugin-itgalaxy`.
- Chore(package): update a minimal version `ava` from `0.15.0` to `0.16.0`.
- Chore(package): update a minimal version `eslint-plugin-ava` from `2.5.0` to `3.0.0`.
- Chore(package): update a minimal version `npm-run-all` from `2.3.0` to `3.0.0`.
- Chore(package): update a minimal version `eslint-plugin-itgalaxy` from `8.0.0` to `11.0.0`.
- Chore(package): update a minimal version `nyc` from `7.0.0` to `8.0.0`.
- Chore(package): remove `nyc` settings, now fine works without their.
- Chore(package): use `^` instead `~` from `babel-preset-stage-0`.
- Chore(package): use `remark-preset-lint-itgalaxy` instead `remark-lint-config-itgalaxy`.
- Chore(package): use right version for `eslint-plugin-*` and `eslint`.
- Chore: improved `README.md`.
- Chore: fix glob pattern for `lint:remark` script command.

## 3.0.1

- Fixed: `--css-template-font-path` now get also from `cosmiconfig`.

## 3.0.0

- Added: support `cosmiconfig`.
- Changed: change function arguments in `standalone`.
- Chore: refactoring.
- Chore: sorting alphabetically `dependencies` and `devDependencies`.
- Chore: remove unused `eslint-*` plugins from `devDependencies`.
- Chore: update minimal version `eslint-plugin-itgalaxy` to `8.0.0`.
- Chore: check is valid fonts in tests.
- Chore: add more tests.
- Chore: sharable config for `remark-lint`.
- Chore: add `nodejs` v5 to `.travis.yml`.

## 2.0.3

- Chore: improved `description` and `keywords` in `package.json`.

## 2.0.2

- Fixed: `svg2ttf` now correctly generates `ttf` font.
- Fixed: `ttf2eot` now correctly generates `eot` font.
- Fixed: `ttf2woff` now correctly generates `woff` font.
- Fixed: `svg2ttf` now correctly accepts option.
- Chore: more readable name tests.
- Chore: rename extension `templates`.

## 2.0.1

- Chore: update `globby` to `6.0.0`.
- Chore: update minimal version `babel-cli` to `6.11.0`.
- Chore: update minimal version `babel-core` to `6.11.0`.
- Chore: update `eslint-plugin-itgalaxy` to `6.0.0`.

## 2.0.0

- Added: `--src-css-template` agument.
- Added: `--css-template-class-name` argument.
- Added: `--css-template-font-path` argument.
- Added: `--css-template-font-name` argument.
- Changed: remove `--css-template-format` argument, now format is taken from `--dest-css-template`.
- Changed: remove `--css` argument, css now generated if you use `--dest-css-template` argument.
- Changed: rename `--css-template-dest` argument to `--dest-css-template`.
- Remove: `--css-template` argument.

## 1.0.1

- Fixed: get `fontId` from `fontName`, if `fontId` is `null` or `undefined`.

## 1.0.0

- Initial release.
