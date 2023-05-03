# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 0.7.0 (2023-05-03)


### Bug Fixes

* **remark:** add aria-hidden to heading links ([45a276f](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/45a276f9343b24f9e2c53f378a0e99d66381eb2b))
* **remark:** add more image options ([#489](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/issues/489), [#674](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/issues/674)) ([3a6580c](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/3a6580c22db44a268818cd0d5aba52dba9fc39a6))
* **remark:** basic gridsome v0.7 support ([424140d](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/424140d80e1e0c30c4fbf8d012246639632ad58e))
* **remark:** calculate time to read correctly ([4d5801d](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/4d5801d7fce4bef4fdae424d09ec6b8c2b206bdf))
* **remark:** fix return value from visitor ([#1586](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/issues/1586)) ([bd8ce90](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/bd8ce909694c6761bce1d8ac1e6f706d30ee47af))
* **remark:** get heading anchors ([5806569](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/5806569e0a98df159da126a85bba6cee676aacff))
* **remark:** improve time to read calculation ([48bf600](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/48bf6004de6ee578eeea40871a0dbedb034a923a))
* **remark:** let plugins set custom stringifier ([f2d3acc](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/f2d3acc8e8909166eb970c62dbf65d820a55555f))
* **remark:** more options for disabling plugins ([4224568](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/4224568ccbbcbc0a5e1123e271c309ac4c80f643))
* **remark:** noscript fallback image ([34ad69d](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/34ad69d0d5ef092d53a5132edc348e0e18b4b801))
* **remark:** override autolink heading options ([21ba048](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/21ba048fe4f76684e05d71cf1f81e4eced2f9cad))
* **remark:** resolve image urls like front matter paths ([db7dde1](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/db7dde13bb4a4b281eb7d9cd88abe9d1fd1e6957))
* **remark:** strip html tags from headings ([c6da951](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/c6da951689eb6c475fe8cf6c0ba8123b1dc4a6f2))
* **remark:** support all remark plugins ([#18](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/issues/18)) ([9b4ea5b](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/9b4ea5beed6980819eabb1fc705b96a794fcff29))
* use local remark options ([2be21e5](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/2be21e595ced05a3f461fa9818a0e897da1f505e))
* **transformer-remark:** dont process relative image urls ([7d4edf3](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/7d4edf3065ab6d9fbb7e6b8a7e6036bf36997398))
* **transformer-remark:** support any remark plugin ([d9ff803](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/d9ff80367129e17d9d77d5bb920fd8ef2a86b724))
* **transformer-remark:** title fallback ([d0a83b5](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/d0a83b54b36f1d2f2d69b79e113256a4389afadf))


### Features

* **remark:** generate excerpt automatically ([#1085](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/issues/1085)) ([8fc1c5a](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/8fc1c5a6a36324ceb679c4bdefa7e47a5e56770c))
* **remark:** option for disabling all built-in plugins ([6336590](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/6336590aadd2ff75aa0af23fd6d0e0a358e1a8f4))
* **remark:** optionally disable built-in plugins ([fc1e2c2](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/fc1e2c25c3fc04c7c8832254fa038ec3768245c8))
* **remark:** resolve local file links in content ([3ffc066](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/3ffc066717736777c0dbd7ad161bfdf180cf1028))
* **remark:** set custom grayMatter options ([#284](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/issues/284)) ([23a5d82](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/23a5d82a639c4c1c3f2e431a29b0617b8a789d2f))
* **remark:** set custom parser config ([#944](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/issues/944)) ([81de8c1](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/81de8c109b394769baef91ab83d0fa77e0da1a91))
* **remark:** simple api for other pugins ([760d1bc](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/760d1bcbc71088586c75afb1a5c71315956cb3bf))
* **remark:** timeToRead with CJK support ([#1160](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/issues/1160)) ([f9ec161](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/f9ec1619e2702715c95e052fee68bfed0fb6956a))
* update for latests changes in core ([8abcbf4](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/8abcbf46910a9e5e470a95ff1bf5a1b5b98ac15e))
* **transformer-remark:** process absolute image paths ([d558cf0](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/d558cf0200833967ff2d487908e62c0e1edde18e))



## 0.0.2 (2018-09-16)



## 0.0.1 (2018-09-16)





## [0.6.6](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/compare/@gridsome/transformer-remark@0.6.5...@gridsome/transformer-remark@0.6.6) (2023-04-26)

**Note:** Version bump only for package @gridsome/transformer-remark





## [0.6.5](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/compare/@gridsome/transformer-remark@0.6.4...@gridsome/transformer-remark@0.6.5) (2023-04-26)


### Bug Fixes

* **remark:** fix return value from visitor ([#1586](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/issues/1586)) ([bd8ce90](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/bd8ce909694c6761bce1d8ac1e6f706d30ee47af))





## [0.6.4](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/compare/@gridsome/transformer-remark@0.6.3...@gridsome/transformer-remark@0.6.4) (2020-11-22)

**Note:** Version bump only for package @gridsome/transformer-remark





## [0.6.3](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/compare/@gridsome/transformer-remark@0.6.2...@gridsome/transformer-remark@0.6.3) (2020-09-18)

**Note:** Version bump only for package @gridsome/transformer-remark





## [0.6.2](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/compare/@gridsome/transformer-remark@0.6.1...@gridsome/transformer-remark@0.6.2) (2020-08-25)

**Note:** Version bump only for package @gridsome/transformer-remark





## [0.6.1](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/compare/@gridsome/transformer-remark@0.6.0...@gridsome/transformer-remark@0.6.1) (2020-07-02)

**Note:** Version bump only for package @gridsome/transformer-remark





# [0.6.0](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/compare/@gridsome/transformer-remark@0.5.0...@gridsome/transformer-remark@0.6.0) (2020-05-26)


### Features

* **remark:** generate excerpt automatically ([#1085](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/issues/1085)) ([8fc1c5a](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/8fc1c5a6a36324ceb679c4bdefa7e47a5e56770c))
* **remark:** timeToRead with CJK support ([#1160](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/issues/1160)) ([f9ec161](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/f9ec1619e2702715c95e052fee68bfed0fb6956a))





# [0.5.0](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/compare/@gridsome/transformer-remark@0.4.0...@gridsome/transformer-remark@0.5.0) (2020-02-18)


### Features

* **remark:** set custom parser config ([#944](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/issues/944)) ([81de8c1](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/81de8c109b394769baef91ab83d0fa77e0da1a91))





# [0.4.0](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/compare/@gridsome/transformer-remark@0.3.4...@gridsome/transformer-remark@0.4.0) (2019-10-25)


### Features

* **remark:** set custom grayMatter options ([#284](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/issues/284)) ([23a5d82](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/23a5d82))





## [0.3.4](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/compare/@gridsome/transformer-remark@0.3.3...@gridsome/transformer-remark@0.3.4) (2019-09-20)


### Bug Fixes

* **remark:** add more image options ([#489](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/issues/489), [#674](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/issues/674)) ([3a6580c](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/3a6580c))





## [0.3.3](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/compare/@gridsome/transformer-remark@0.3.2...@gridsome/transformer-remark@0.3.3) (2019-09-11)


### Bug Fixes

* **remark:** basic gridsome v0.7 support ([424140d](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/424140d))
* **remark:** more options for disabling plugins ([4224568](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/4224568))





## [0.3.2](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/compare/@gridsome/transformer-remark@0.3.1...@gridsome/transformer-remark@0.3.2) (2019-05-20)

**Note:** Version bump only for package @gridsome/transformer-remark





## [0.3.1](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/compare/@gridsome/transformer-remark@0.3.0...@gridsome/transformer-remark@0.3.1) (2019-05-13)


### Bug Fixes

* **remark:** let plugins set custom stringifier ([f2d3acc](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/f2d3acc))





# [0.3.0](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/compare/@gridsome/transformer-remark@0.2.1...@gridsome/transformer-remark@0.3.0) (2019-05-10)


### Bug Fixes

* **remark:** support all remark plugins ([#18](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/issues/18)) ([9b4ea5b](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/9b4ea5b))


### Features

* update for latests changes in core ([8abcbf4](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/commit/8abcbf4))





<a name="0.2.1"></a>
## [0.2.1](https://github.com/gridsome/gridsome/tree/master/packages/transformer-remark/compare/@gridsome/transformer-remark@0.2.0...@gridsome/transformer-remark@0.2.1) (2019-02-26)

**Note:** Version bump only for package @gridsome/transformer-remark





<a name="0.2.0"></a>
# [0.2.0](https://github.com/gridsome/gridsome/tree/master/packages/remark-prismjs/compare/@gridsome/transformer-remark@0.1.3...@gridsome/transformer-remark@0.2.0) (2019-02-19)


### Bug Fixes

* **remark:** improve time to read calculation ([48bf600](https://github.com/gridsome/gridsome/tree/master/packages/remark-prismjs/commit/48bf600))
* **remark:** resolve image urls like front matter paths ([db7dde1](https://github.com/gridsome/gridsome/tree/master/packages/remark-prismjs/commit/db7dde1))


### Features

* **remark:** option for disabling all built-in plugins ([6336590](https://github.com/gridsome/gridsome/tree/master/packages/remark-prismjs/commit/6336590))
* **remark:** optionally disable built-in plugins ([fc1e2c2](https://github.com/gridsome/gridsome/tree/master/packages/remark-prismjs/commit/fc1e2c2))
* **remark:** resolve local file links in content ([3ffc066](https://github.com/gridsome/gridsome/tree/master/packages/remark-prismjs/commit/3ffc066))
* **remark:** simple api for other pugins ([760d1bc](https://github.com/gridsome/gridsome/tree/master/packages/remark-prismjs/commit/760d1bc))





<a name="0.1.3"></a>
## [0.1.3](https://github.com/gridsome/gridsome/compare/@gridsome/transformer-remark@0.1.2...@gridsome/transformer-remark@0.1.3) (2019-01-04)


### Bug Fixes

* **remark:** calculate time to read correctly ([4d5801d](https://github.com/gridsome/gridsome/commit/4d5801d))


<a name="0.1.2"></a>
## [0.1.2](https://github.com/gridsome/gridsome/compare/@gridsome/transformer-remark@0.1.1...@gridsome/transformer-remark@0.1.2) (2018-12-06)


### Bug Fixes

* **remark:** get heading anchors ([5806569](https://github.com/gridsome/gridsome/commit/5806569))
* **remark:** override autolink heading options ([21ba048](https://github.com/gridsome/gridsome/commit/21ba048))
* **remark:** strip html tags from headings ([c6da951](https://github.com/gridsome/gridsome/commit/c6da951))


<a name="0.1.1"></a>
## [0.1.1](https://github.com/gridsome/gridsome/compare/@gridsome/transformer-remark@0.1.0...@gridsome/transformer-remark@0.1.1) (2018-11-11)


### Bug Fixes

* use local remark options ([2be21e5](https://github.com/gridsome/gridsome/commit/2be21e5))


<a name="0.1.0"></a>
# [0.1.0](https://github.com/gridsome/gridsome/compare/@gridsome/transformer-remark@0.0.3...@gridsome/transformer-remark@0.1.0) (2018-10-30)


### Bug Fixes

* **transformer-remark:** dont process relative image urls ([7d4edf3](https://github.com/gridsome/gridsome/commit/7d4edf3))
* **transformer-remark:** support any remark plugin ([d9ff803](https://github.com/gridsome/gridsome/commit/d9ff803))
* **transformer-remark:** title fallback ([d0a83b5](https://github.com/gridsome/gridsome/commit/d0a83b5))


### Features

* **transformer-remark:** process absolute image paths ([d558cf0](https://github.com/gridsome/gridsome/commit/d558cf0))


<a name="0.0.3"></a>
## [0.0.3](https://github.com/gridsome/gridsome/compare/142896c2454016dc989a7872faffec7263fc658c...@gridsome/transformer-remark@0.0.3) (2018-09-26)


### Bug Fixes

* **remark:** add aria-hidden to heading links ([45a276f](https://github.com/gridsome/gridsome/commit/45a276f))
* **remark:** noscript fallback image ([34ad69d](https://github.com/gridsome/gridsome/commit/34ad69d))



<a name="0.0.2"></a>
## [0.0.2](https://github.com/gridsome/gridsome/compare/142896c2454016dc989a7872faffec7263fc658c...@gridsome/transformer-remark@0.0.3) (2018-09-16)
