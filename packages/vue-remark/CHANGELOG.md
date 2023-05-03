# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 0.3.0 (2023-05-03)


### Bug Fixes

* **vue-remark:** add more image options ([031d832](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/031d83255eae10b228d2e24f79d39141e56b39d3))
* **vue-remark:** add undeclared dependencies babel-loader and vue-loader ([cc3bdf1](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/cc3bdf164787d9963a8444cdd0399ef92ef58dbb))
* **vue-remark:** don't use g-link for mailto links ([#740](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/740)) ([99e577a](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/99e577a05a5adabdea8f40f281efd502a6d90438))
* **vue-remark:** don't wrap end tag in paragraph ([#941](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/941)) ([7a48f0c](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/7a48f0c81c1b5ae870cc6b06190d53936553baa9))
* **vue-remark:** don’t interpolate inline code ([db3416f](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/db3416fdb7aa562a5e66d928569620492657bdd4))
* **vue-remark:** don’t touch built-in tags ([#677](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/677)) ([cb69ea9](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/cb69ea9a9fd21dc7735dfee4355525273a4c1bb5))
* **vue-remark:** don’t use g-image and g-link for urls ([9264970](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/92649702e46c4c2569f0b33d531af01e4f1a6a3f))
* **vue-remark:** exclude layout settings from schema ([#991](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/991)) ([dcafdcc](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/dcafdcc5010147d458b887076ec530330edca3fd))
* **vue-remark:** exclude remark-cli in cache identifier ([#1128](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/1128)) ([a8cfa84](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/a8cfa84254e45b73c9bde98e274d7b89ad4bd0e3))
* **vue-remark:** extract sfc blocks from template ([dc33f4a](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/dc33f4a896140354d8383cd871a2fa0bebe18e1c))
* **vue-remark:** generate route chunk names ([18615ad](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/18615adf393d5ed8d15ec0ed1ca35fb4ebe0977d))
* **vue-remark:** improve cache invalidation ([#707](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/707)) ([a9bff02](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/a9bff02499d8300ac0bb3c360dd4462e9d81cf46))
* **vue-remark:** include alt tag for images ([139f780](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/139f7802e09fe611a3f92a5889cc64b4856488c8))
* **vue-remark:** parse markdown inside components ([#677](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/677)) ([d52e716](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/d52e71627bf482f37e6bf7cf644195a8c81fa730))
* **vue-remark:** preload VueRemarkContent component ([369d2fc](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/369d2fccb6d23d456416a8320b218305e93c7fe0))
* **vue-remark:** prevent type name conflicts in schema ([#815](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/815)) ([c56182e](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/c56182ed9c8047555d842a09fc29adccde36600d))
* **vue-remark:** process style tags after components ([#693](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/693)) ([47cc556](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/47cc55683300bdac7676cd2339496ef97de7435b))
* **vue-remark:** require.resolve webpack loaders ([40d7680](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/40d76801001ef7cc4cfc6cf10b20bbbef241939a))
* **vue-remark:** support import as syntax ([b429d3f](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/b429d3f217b6b3de8bab14ef2478840a3eda6e82))
* **vue-remark:** support VueComponent function ([#1264](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/1264)) ([b4eb3ec](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/b4eb3ecd23baf25719f5bdbe45fc5a9cabb0c4ba))
* **vue-remark:** throw error if using global templates ([1c54c27](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/1c54c27c57ff328f697baa97d3c76c1597009816))
* **vue-remark:** transpile custom sfc blocks ([a79a67c](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/a79a67cb6fa3395e81f31dad3eb738ae2757feed))
* **vue-remark:** use babel env preset for custom blocks ([11e56eb](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/11e56eb47f6828e4527734877e627e8099d8e6ee))
* **vue-remark:** use named entities when encoding ([#1179](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/1179)) ([1fcecc0](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/1fcecc0f47f88f8e0d4992defc30fb3862c226cb))


### Features

* **vue-remark:** option for ignoring files with glob patterns ([#1003](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/1003)) ([9a605fb](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/9a605fbf86ef6bc1dcfd3775ee6544f226c92832))
* **vue-remark:** vue components in markdown ([#424](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/424)) ([00e710d](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/00e710db5b4ca9d5f7212e1c6f195e6f66142458))





## [0.2.8](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.2.7...@gridsome/vue-remark@0.2.8) (2023-04-26)

**Note:** Version bump only for package @gridsome/vue-remark





## [0.2.7](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.2.6...@gridsome/vue-remark@0.2.7) (2023-04-26)


### Bug Fixes

* **vue-remark:** add undeclared dependencies babel-loader and vue-loader ([cc3bdf1](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/cc3bdf164787d9963a8444cdd0399ef92ef58dbb))
* **vue-remark:** require.resolve webpack loaders ([40d7680](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/40d76801001ef7cc4cfc6cf10b20bbbef241939a))





## [0.2.6](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.2.5...@gridsome/vue-remark@0.2.6) (2020-11-22)

**Note:** Version bump only for package @gridsome/vue-remark





## [0.2.5](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.2.4...@gridsome/vue-remark@0.2.5) (2020-09-18)

**Note:** Version bump only for package @gridsome/vue-remark





## [0.2.4](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.2.3...@gridsome/vue-remark@0.2.4) (2020-08-25)

**Note:** Version bump only for package @gridsome/vue-remark





## [0.2.3](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.2.2...@gridsome/vue-remark@0.2.3) (2020-08-20)


### Bug Fixes

* **vue-remark:** support VueComponent function ([#1264](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/1264)) ([b4eb3ec](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/b4eb3ecd23baf25719f5bdbe45fc5a9cabb0c4ba))





## [0.2.2](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.2.1...@gridsome/vue-remark@0.2.2) (2020-07-02)

**Note:** Version bump only for package @gridsome/vue-remark





## [0.2.1](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.2.0...@gridsome/vue-remark@0.2.1) (2020-05-26)


### Bug Fixes

* **vue-remark:** exclude remark-cli in cache identifier ([#1128](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/1128)) ([a8cfa84](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/a8cfa84254e45b73c9bde98e274d7b89ad4bd0e3))
* **vue-remark:** use named entities when encoding ([#1179](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/1179)) ([1fcecc0](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/1fcecc0f47f88f8e0d4992defc30fb3862c226cb))





# [0.2.0](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.1.10...@gridsome/vue-remark@0.2.0) (2020-04-18)


### Bug Fixes

* **vue-remark:** don't wrap end tag in paragraph ([#941](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/941)) ([7a48f0c](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/7a48f0c81c1b5ae870cc6b06190d53936553baa9))
* **vue-remark:** exclude layout settings from schema ([#991](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/991)) ([dcafdcc](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/dcafdcc5010147d458b887076ec530330edca3fd))
* **vue-remark:** prevent type name conflicts in schema ([#815](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/815)) ([c56182e](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/c56182ed9c8047555d842a09fc29adccde36600d))


### Features

* **vue-remark:** option for ignoring files with glob patterns ([#1003](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/1003)) ([9a605fb](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/9a605fbf86ef6bc1dcfd3775ee6544f226c92832))





## [0.1.10](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.1.9...@gridsome/vue-remark@0.1.10) (2020-02-18)

**Note:** Version bump only for package @gridsome/vue-remark





## [0.1.9](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.1.8...@gridsome/vue-remark@0.1.9) (2019-11-19)


### Bug Fixes

* **vue-remark:** improve cache invalidation ([#707](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/707)) ([a9bff02](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/a9bff02))





## [0.1.8](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.1.7...@gridsome/vue-remark@0.1.8) (2019-10-25)

**Note:** Version bump only for package @gridsome/vue-remark





## [0.1.7](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.1.6...@gridsome/vue-remark@0.1.7) (2019-10-15)


### Bug Fixes

* **vue-remark:** don't use g-link for mailto links ([#740](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/740)) ([99e577a](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/99e577a))





## [0.1.6](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.1.5...@gridsome/vue-remark@0.1.6) (2019-10-07)

**Note:** Version bump only for package @gridsome/vue-remark





## [0.1.5](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.1.4...@gridsome/vue-remark@0.1.5) (2019-09-27)


### Bug Fixes

* **vue-remark:** don’t use g-image and g-link for urls ([9264970](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/9264970))





## [0.1.4](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.1.3...@gridsome/vue-remark@0.1.4) (2019-09-22)


### Bug Fixes

* **vue-remark:** process style tags after components ([#693](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/693)) ([47cc556](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/47cc556))





## [0.1.3](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.1.2...@gridsome/vue-remark@0.1.3) (2019-09-20)


### Bug Fixes

* **vue-remark:** don’t touch built-in tags ([#677](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/677)) ([cb69ea9](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/cb69ea9))
* **vue-remark:** extract sfc blocks from template ([dc33f4a](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/dc33f4a))
* **vue-remark:** generate route chunk names ([18615ad](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/18615ad))
* **vue-remark:** throw error if using global templates ([1c54c27](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/1c54c27))
* **vue-remark:** use babel env preset for custom blocks ([11e56eb](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/11e56eb))





## [0.1.2](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.1.1...@gridsome/vue-remark@0.1.2) (2019-09-20)


### Bug Fixes

* **vue-remark:** add more image options ([031d832](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/031d832))
* **vue-remark:** include alt tag for images ([139f780](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/139f780))
* **vue-remark:** parse markdown inside components ([#677](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/677)) ([d52e716](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/d52e716))
* **vue-remark:** support import as syntax ([b429d3f](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/b429d3f))
* **vue-remark:** transpile custom sfc blocks ([a79a67c](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/a79a67c))





## [0.1.1](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/compare/@gridsome/vue-remark@0.1.0...@gridsome/vue-remark@0.1.1) (2019-09-13)


### Bug Fixes

* **vue-remark:** don’t interpolate inline code ([db3416f](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/db3416f))
* **vue-remark:** preload VueRemarkContent component ([369d2fc](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/369d2fc))





# 0.1.0 (2019-09-11)


### Features

* **vue-remark:** vue components in markdown ([#424](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/issues/424)) ([00e710d](https://github.com/gridsome/gridsome/tree/master/packages/vue-remark/commit/00e710d))
