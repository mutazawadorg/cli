# Changelog

## [6.0.0-pre.1](https://github.com/npm/cli/compare/arborist-v6.0.0-pre.0...arborist-v6.0.0-pre.1) (2022-09-14)

### Bug Fixes

* [`f3b0c43`](https://github.com/npm/cli/commit/f3b0c438d5b62b267f36c21d7b9fa57ae9507ef5) keep saveTypes separate for each `add` (@wraithgar)

## [6.0.0-pre.0](https://github.com/npm/cli/compare/arborist-v5.6.1...arborist-v6.0.0-pre.0) (2022-09-08)

### ⚠ BREAKING CHANGES

* **workspaces:** all workspace packages are now compatible with the following semver range for node: `^14.17.0 || ^16.13.0 || >=18.0.0`

### Features

  * [`e95017a`](https://github.com/npm/cli/commit/e95017a07b041cbb3293e659dad853f76462c108) [#5485](https://github.com/npm/cli/pull/5485) feat(workspaces): update supported node engines in package.json (@lukekarrys)
  * [`09c46e8`](https://github.com/npm/cli/commit/09c46e815fe1b44658d32dd760a689e8b2c8d92f) [#5324](https://github.com/npm/cli/pull/5324) feat(arborist): allow for selectors and function names with :semver pseudo selector (@nlf)

### Bug Fixes

  * [`fe926ed`](https://github.com/npm/cli/commit/fe926eddf98459e1fcb0ffd011ce7703da14928c) [#5484](https://github.com/npm/cli/pull/5484) fix: don't mark workspaces as invalid if installing links (@wraithgar)
  * [`548e70e`](https://github.com/npm/cli/commit/548e70e0f87167fb96929b29787620391a77b826) [#5376](https://github.com/npm/cli/pull/5376) fix: link.target setter (@wraithgar)
  * [`2db6c08`](https://github.com/npm/cli/commit/2db6c085ea08ee639767d37e6fd83a1ca0fbd9ce) [#5376](https://github.com/npm/cli/pull/5376) fix: loadActual cleanup (@wraithgar)

### Documentation

  * [`285b39f`](https://github.com/npm/cli/commit/285b39f8d6915823fb424cca7161a0b445b86bd3) [#5324](https://github.com/npm/cli/pull/5324) docs: add documentation for expanded :semver selector (@nlf)

## [5.6.1](https://github.com/npm/cli/compare/arborist-v5.6.0...arborist-v5.6.1) (2022-08-31)

### Bug Fixes

  * [`1e84102`](https://github.com/npm/cli/commit/1e841029917817556207c39d25be1ea91e2959e7) [#5350](https://github.com/npm/cli/pull/5350) fix: create links relative to the target (@wraithgar)
  * [`ea5e3a3`](https://github.com/npm/cli/commit/ea5e3a319a7c1b5f7f2a66284227a34b79b2c831) [#5350](https://github.com/npm/cli/pull/5350) fix: inline single-use functions (@wraithgar)
  * [`645c680`](https://github.com/npm/cli/commit/645c6804c09014b96c2d1eff191b174d12a2b7c0) [#5329](https://github.com/npm/cli/pull/5329) fix: update `index.js` spelling error in comment (@KevinBrother)
  * [`bd2ae5d`](https://github.com/npm/cli/commit/bd2ae5d79eb8807bfca6075e98432c545a9ededa) [#5323](https://github.com/npm/cli/pull/5323) fix: linting (@wraithgar)

### Dependencies

  * [`1286f03`](https://github.com/npm/cli/commit/1286f03fe73dee9a447b13b662f0c5622ab6ec9e) [#5381](https://github.com/npm/cli/pull/5381) deps: `unique-filename@2.0.1`
  * [`2c4e387`](https://github.com/npm/cli/commit/2c4e38728f25fd32624df2eb5bbf61c2c40c8ad5) [#5381](https://github.com/npm/cli/pull/5381) deps: `hosted-git-info@5.1.0`
  * [`b12ac01`](https://github.com/npm/cli/commit/b12ac013226b7d86b5b1847d58eabbac2846b153) [#5381](https://github.com/npm/cli/pull/5381) deps: `npm-pick-manifest@7.0.2`
  * [`7fbf6f7`](https://github.com/npm/cli/commit/7fbf6f7825f76906ecdec79ab15595f9e2f7b784) [#5381](https://github.com/npm/cli/pull/5381) deps: `bin-links@3.0.3`
  * [`26d2e55`](https://github.com/npm/cli/commit/26d2e551b250972caa550d56127810648a1663a1) [#5381](https://github.com/npm/cli/pull/5381) deps: `@npmcli/query@1.2.0`
  * [`a79ee00`](https://github.com/npm/cli/commit/a79ee00b530b765ed219e81de77c37057c373adf) [#5381](https://github.com/npm/cli/pull/5381) deps: `cacache@16.1.3`
  * [`8ab12dc`](https://github.com/npm/cli/commit/8ab12dc32b26db770b868cf694cedab38f4e7460) [#5323](https://github.com/npm/cli/pull/5323) deps: `@npmcli/eslint-config@3.1.0`

## [5.6.0](https://github.com/npm/cli/compare/arborist-v5.5.0...arborist-v5.6.0) (2022-08-17)


### Features

* **arborist:** add :overridden pseudo selector ([d221f72](https://github.com/npm/cli/commit/d221f72c00e13258469a748227a1d6f9953a5948))
* **arborist:** add overridden getter to Node class ([e6d4304](https://github.com/npm/cli/commit/e6d4304bbd03e38dcf2c7467bb1e61b5740a4c73))
* **query:** support :overridden pseudo selector ([0d4ed0f](https://github.com/npm/cli/commit/0d4ed0fb1cd86edd827cac0b5367b73bb864a9bf))

## [5.5.0](https://github.com/npm/cli/compare/arborist-v5.4.0...arborist-v5.5.0) (2022-08-10)


### Features

* **arborist:** add option to forcibly skip loading a virtual tree ([96b6781](https://github.com/npm/cli/commit/96b6781086143d7285c2c5bf7808c24b2c87e4dd))


### Bug Fixes

* **query:** tell arborist to load an actual tree, not a virtual one ([9078e27](https://github.com/npm/cli/commit/9078e27cef0233d6fc81e0ca824a34fd7685d93c))


### Dependencies

* nopt@6.0.0 ([7f31b85](https://github.com/npm/cli/commit/7f31b85db650c7a2b3b0577840251f5e25e63a01))

## [5.4.0](https://github.com/npm/cli/compare/arborist-v5.3.1...arborist-v5.4.0) (2022-08-03)


### Features

* add --replace-registry-host=<npmjs|always|never> ([#4860](https://github.com/npm/cli/issues/4860)) ([703dbbf](https://github.com/npm/cli/commit/703dbbf2a8149dff72c848d60600889a76779828))
* add --replace-registry-host=<npmjs|always|never>|<hostname> ([703dbbf](https://github.com/npm/cli/commit/703dbbf2a8149dff72c848d60600889a76779828))
* add npm query cmd ([#5000](https://github.com/npm/cli/issues/5000)) ([3c024ac](https://github.com/npm/cli/commit/3c024ace60904c69e61da00e1fb56c0c1735804a))


### Bug Fixes

* **arborist:** fix bare attribute queries ([#5248](https://github.com/npm/cli/issues/5248)) ([8233fca](https://github.com/npm/cli/commit/8233fca44321186c485964d26aa3c7c43eafff3d))
* **arborist:** pass the edge to fromPath in order to determine correct path ([#5233](https://github.com/npm/cli/issues/5233)) ([050284d](https://github.com/npm/cli/commit/050284d2abb6aa91a0f9ffad5b0c4f074e5dbf6d))
* **arborist:** use the sourceReference root rather than the node root for overrides ([#5227](https://github.com/npm/cli/issues/5227)) ([47cc95d](https://github.com/npm/cli/commit/47cc95d9ffb37fc8ff62a1d5554eab16d303aa43)), closes [#4395](https://github.com/npm/cli/issues/4395)


### Dependencies

* @npmcli/query@1.1.1 ([#5247](https://github.com/npm/cli/issues/5247)) ([d55007d](https://github.com/npm/cli/commit/d55007d9c535b17612a07a7a58cb6be94eedf77a))

## [5.3.1](https://github.com/npm/cli/compare/arborist-v5.3.0...arborist-v5.3.1) (2022-07-27)


### Bug Fixes

* allow hash character in paths ([#5122](https://github.com/npm/cli/issues/5122)) ([62b95a0](https://github.com/npm/cli/commit/62b95a04337661e3fa17093708b57000054442d9))

## [5.3.0](https://github.com/npm/cli/compare/arborist-v5.2.3...arborist-v5.3.0) (2022-07-11)


### Features

* **arborist:** add support for dependencies script ([#5094](https://github.com/npm/cli/issues/5094)) ([e9b4214](https://github.com/npm/cli/commit/e9b4214e1ddb1ad79fe6826cf2ce7ba385f0c274))

## [5.2.3](https://github.com/npm/cli/compare/arborist-v5.2.2...arborist-v5.2.3) (2022-06-23)


### Dependencies

* @npmcli/run-script@4.1.3 ([#5064](https://github.com/npm/cli/issues/5064)) ([f59a114](https://github.com/npm/cli/commit/f59a114ffe3d1f86ccb2e52a4432292ab76852cc))

## [5.2.2](https://github.com/npm/cli/compare/arborist-v5.2.1...arborist-v5.2.2) (2022-06-22)


### Bug Fixes

* Add space to SemVer log message ([#5042](https://github.com/npm/cli/issues/5042)) ([e03009f](https://github.com/npm/cli/commit/e03009f4b423e85e498f1b1851fae785de91a73d))


### Dependencies

* @npmcli/run-script@4.1.0 ([2c06cee](https://github.com/npm/cli/commit/2c06ceee82dd813c0ae84cc0b09e6941cfc5533e))
* pacote@13.6.1 ([2e50cb8](https://github.com/npm/cli/commit/2e50cb83e84cf25fee93ba0ca5a0343fbdb33c41))

### [5.2.1](https://github.com/npm/cli/compare/arborist-v5.2.0...arborist-v5.2.1) (2022-06-01)


### Bug Fixes

* **arborist:** use rawSpec for bundled and shrinkwrapped deps ([#4963](https://github.com/npm/cli/issues/4963)) ([646b6b5](https://github.com/npm/cli/commit/646b6b5d05de937beb8202e5fd8b8daf3e58e902))

## [5.2.0](https://github.com/npm/cli/compare/arborist-v5.1.1...arborist-v5.2.0) (2022-05-10)


### Features

* add flag --omit-lockfile-registry-resolved ([#4874](https://github.com/npm/cli/issues/4874)) ([bfb8bcc](https://github.com/npm/cli/commit/bfb8bccbe83753e527b43c8a3889696087dbe8f1))


### Bug Fixes

* **arborist:** link deps lifecycle scripts ([#4875](https://github.com/npm/cli/issues/4875)) ([5a50762](https://github.com/npm/cli/commit/5a50762faa37ae5964ae6f12595b20b367056c0a))

### [5.1.1](https://github.com/npm/cli/compare/arborist-v5.1.0...arborist-v5.1.1) (2022-04-26)


### Dependencies

* @npmcli/map-workspaces@2.0.3 ([3f2b24a](https://github.com/npm/cli/commit/3f2b24afe205547dbbadf5a6313e95f6b565fb49))
* cacache@16.0.6 ([532883f](https://github.com/npm/cli/commit/532883ffc35fc1cc9aec09f03bf5ee0f256b94a4))
* npmlog@6.0.2 ([5e31322](https://github.com/npm/cli/commit/5e313223100db1207818d756b081eaba3468b273))
* semver@7.3.7 ([c51e553](https://github.com/npm/cli/commit/c51e553a32315e4f1b703ca9030eb7ade91d1a85))

## [5.1.0](https://github.com/npm/cli/compare/arborist-v5.0.6...arborist-v5.1.0) (2022-04-19)


### Features

* **arborist:** add support for installLinks ([0ebadf5](https://github.com/npm/cli/commit/0ebadf5b603368557e9e837a46ea5c59c2677a81))


### Bug Fixes

* **arborist:** when replacing a Link with a Node, make sure to remove the Link target from the root ([3d96494](https://github.com/npm/cli/commit/3d964940f410052918e37a9b05818fe9dc4cd86a))

### [5.0.6](https://github.com/npm/cli/compare/arborist-v5.0.5...arborist-v5.0.6) (2022-04-13)


### Bug Fixes

* **arborist:** dont skip adding advisories to audit based on name/range ([aa4a4da](https://github.com/npm/cli/commit/aa4a4da336a6ec1963394fdbd06acb173c842d26)), closes [#4681](https://github.com/npm/cli/issues/4681)
* **arborist:** when reloading an edge, also refresh overrides ([4d676e3](https://github.com/npm/cli/commit/4d676e31a68f081b8553eff4e79db1f29acf47e1))

### [5.0.5](https://github.com/npm/cli/compare/arborist-v5.0.4...arborist-v5.0.5) (2022-04-06)


### Bug Fixes

* replace deprecated String.prototype.substr() ([#4667](https://github.com/npm/cli/issues/4667)) ([e3da5df](https://github.com/npm/cli/commit/e3da5df4152fbe547f7871547165328e1bf06262))
* update readme badges ([#4658](https://github.com/npm/cli/issues/4658)) ([2829cb2](https://github.com/npm/cli/commit/2829cb28a432b5ff7beeeb3bf3e7e2e174c1121d))


### Dependencies

* @npmcli/arborist@5.0.4 ([679e569](https://github.com/npm/cli/commit/679e569d5778aef312b37c1ba3bda0171366c9fb))
* @npmcli/move-file@2.0.0 ([e9b25cd](https://github.com/npm/cli/commit/e9b25cd66bef17e807a84e7b10384f5f4d0064b7))
* @npmcli/node-gyp@2.0.0 ([0e87cac](https://github.com/npm/cli/commit/0e87cac8b6f09692f6bd1bf086aadbe323d127b5))
* @npmcli/package-json@2.0.0 ([4a9a705](https://github.com/npm/cli/commit/4a9a705de6992a3e9eefecc6c0cf8da45a527c7a))
* npm-install-checks@5.0.0 ([ad99360](https://github.com/npm/cli/commit/ad9936063f20829eb9d5358d056593883f17a57b))
* ssri@9.0.0 ([a2781a3](https://github.com/npm/cli/commit/a2781a367d62328d7f870de878f1b63d66593f4f))
* treeverse@2.0.0 ([1a90b9e](https://github.com/npm/cli/commit/1a90b9e9ebe98cce83591e11312aaf41c830f835))

### [5.0.4](https://github.com/npm/cli/compare/arborist-v5.0.3...arborist-v5.0.4) (2022-03-31)


### Bug Fixes

* **arborist:** handle link nodes in old lockfiles correctly ([6f9cb49](https://github.com/npm/cli/commit/6f9cb490e7299976c43c6a118036c130671fe188))
* **arborist:** identify and repair invalid nodes in the virtual tree ([bd96ae4](https://github.com/npm/cli/commit/bd96ae4071f9cc8a65e741f414db12e98537971d))
* **arborist:** make sure resolveParent exists before checking props ([18b8b94](https://github.com/npm/cli/commit/18b8b94357d8f57301fbaa0f1e5dc2cf1128bf3e))
* make sure we loadOverrides on the root node in loadVirtual() ([99d8845](https://github.com/npm/cli/commit/99d88454248f950b82652b592fe2b4d019c1060b))
* only call npmlog progress methods if explicitly requested ([#4644](https://github.com/npm/cli/issues/4644)) ([668ec7f](https://github.com/npm/cli/commit/668ec7f33b7a76f5e86a59f7e5a6c0e068a242b1)), closes [#3314](https://github.com/npm/cli/issues/3314)

### [5.0.3](https://www.github.com/npm/cli/compare/arborist-v5.0.2...arborist-v5.0.3) (2022-03-17)


### Bug Fixes

* **arborist:** _findMissingEdges missing dependency due to inconsistent path separators ([#4261](https://www.github.com/npm/cli/issues/4261)) ([0e7511d](https://www.github.com/npm/cli/commit/0e7511d144bdb6624e4c0fdfb31b4b42ed2954c9))
* **arborist:** save workspace version ([#4578](https://www.github.com/npm/cli/issues/4578)) ([e9a2981](https://www.github.com/npm/cli/commit/e9a2981f55f84ff521ef597883a4e732d08ce1c1))


### Dependencies

* @npmcli/metavuln-calculator@3.0.1 ([fcc6acf](https://www.github.com/npm/cli/commit/fcc6acfa808aa556748544edf4e9b73262f77608))
* cacache@16.0.0 ([e26548f](https://www.github.com/npm/cli/commit/e26548fb12a3bb23fbe32a336f1305e083aa51c0))
* pacote@13.0.5 ([340fa51](https://www.github.com/npm/cli/commit/340fa51f423a518a96c8015a67d8f6144a2e8051))

### [5.0.2](https://www.github.com/npm/cli/compare/arborist-v5.0.1...arborist-v5.0.2) (2022-03-10)


### Bug Fixes

* **rebuild:** don't run lifecycle scripts twice on linked deps ([#4529](https://www.github.com/npm/cli/issues/4529)) ([fbdb431](https://www.github.com/npm/cli/commit/fbdb43138ab8e682efb7668767465e7066d43b9f))


### Documentation

* standardize changelog heading ([#4510](https://www.github.com/npm/cli/issues/4510)) ([91f03ee](https://www.github.com/npm/cli/commit/91f03ee618bc635f9cfbded735fe98bbfa9d643f))

### [5.0.1](https://www.github.com/npm/cli/compare/arborist-v5.0.0...arborist-v5.0.1) (2022-03-08)


### Bug Fixes

* set proper workspace repo urls in package.json ([#4476](https://www.github.com/npm/cli/issues/4476)) ([0cfc155](https://www.github.com/npm/cli/commit/0cfc155db5f11ce23419e440111d99a63bf39754))

## 2.0.0

* BREAKING CHANGE: root node is now included in inventory
* All parent/target/fsParent/etc. references set in `root` setter, rather
  than the hodgepodge of setters that existed before.
* `treeCheck` function added, to enforce strict correctness guarantees when
  `ARBORIST_DEBUG=1` in the environment (on by default in Arborist tests).

## 1.0.0

* Release for npm v7 beta
* Fully functional

## 0.0.0

* Proof of concept
* Before this, it was [`read-package-tree`](http://npm.im/read-package-tree)
