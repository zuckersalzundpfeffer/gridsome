# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 0.9.0 (2023-04-26)


### Bug Fixes

* **api:** allow arrow function as default export ([44d13bc](https://github.com/zuckersalzundpfeffer/gridsome/commit/44d13bca481d43904be62e2b051ef6eaed526897))
* **api:** pass graphql object to addSchemaField ([#64](https://github.com/zuckersalzundpfeffer/gridsome/issues/64)) ([f6fd2a8](https://github.com/zuckersalzundpfeffer/gridsome/commit/f6fd2a81c5de0382c90a4aaf0ccfb89351f7858c))
* **api:** use express app in configureServer ([#668](https://github.com/zuckersalzundpfeffer/gridsome/issues/668)) ([fff7a8f](https://github.com/zuckersalzundpfeffer/gridsome/commit/fff7a8f39afafbecf457caa055381ddf7bb42a20))
* **app:** clear cache if the request fails ([#1312](https://github.com/zuckersalzundpfeffer/gridsome/issues/1312)) ([f3f473e](https://github.com/zuckersalzundpfeffer/gridsome/commit/f3f473e9883bc7879f21b3c69522cf2c9a32a82f))
* **app:** decode anchor hash value ([#1281](https://github.com/zuckersalzundpfeffer/gridsome/issues/1281)) ([#1293](https://github.com/zuckersalzundpfeffer/gridsome/issues/1293)) ([b93eb39](https://github.com/zuckersalzundpfeffer/gridsome/commit/b93eb39ec41384f9ec1869650e29d783d93a5d48))
* **app:** don’t fetch data if no context in development ([0850875](https://github.com/zuckersalzundpfeffer/gridsome/commit/08508753cc40ad975bdef57eaafa6fcd523d7325))
* **app:** don’t prefetch already loaded data ([025ab83](https://github.com/zuckersalzundpfeffer/gridsome/commit/025ab8304360b674e7aa5c0224770ac194f5158e))
* **app:** don’t resolve links without path prefix ([66eb650](https://github.com/zuckersalzundpfeffer/gridsome/commit/66eb65040133e3b6caae80489aa75253ad38fe5d))
* **app:** don’t use empty siteDescription ([#511](https://github.com/zuckersalzundpfeffer/gridsome/issues/511), [#516](https://github.com/zuckersalzundpfeffer/gridsome/issues/516)) ([346279d](https://github.com/zuckersalzundpfeffer/gridsome/commit/346279d6030e40fc5aa9da31321a30b40d844b69))
* **app:** ensure siteUrl is set before checking url ([dfdfea9](https://github.com/zuckersalzundpfeffer/gridsome/commit/dfdfea9ec3e9ee77d9f077cbc4c7ccb00797b398))
* **app:** ignore NavigationDuplicated error ([#703](https://github.com/zuckersalzundpfeffer/gridsome/issues/703)) ([a000bfb](https://github.com/zuckersalzundpfeffer/gridsome/commit/a000bfb3edea382c845286fdd3f9887136a9cea7))
* **app:** improve IE11 compatibility ([39b5114](https://github.com/zuckersalzundpfeffer/gridsome/commit/39b511463530487ac9833405a2cb4e132667506f))
* **app:** include query params in html links ([f0b162e](https://github.com/zuckersalzundpfeffer/gridsome/commit/f0b162eb176648b17673cce1a100aa1c3338e058))
* **app:** parse json regardless of content-type ([#534](https://github.com/zuckersalzundpfeffer/gridsome/issues/534)) ([f2d2d40](https://github.com/zuckersalzundpfeffer/gridsome/commit/f2d2d40249b1716130fe5cfb49a0d0112cd14f1f))
* **app:** prevent cyclic dependency ([#421](https://github.com/zuckersalzundpfeffer/gridsome/issues/421)) ([3574efa](https://github.com/zuckersalzundpfeffer/gridsome/commit/3574efa68929fa2029e246ee897243209b52fca2))
* **app:** prevent images from loading twice ([#486](https://github.com/zuckersalzundpfeffer/gridsome/issues/486)) ([d44b5ac](https://github.com/zuckersalzundpfeffer/gridsome/commit/d44b5acea0a514f23e2cd2f8319face78c3e8b7a)), closes [#438](https://github.com/zuckersalzundpfeffer/gridsome/issues/438)
* **app:** prevent infinite loop for 404 ([#387](https://github.com/zuckersalzundpfeffer/gridsome/issues/387)) ([698f8b3](https://github.com/zuckersalzundpfeffer/gridsome/commit/698f8b3972923f0492b2db8c276230d391da203a))
* **app:** prevent request to favicon.ico ([#711](https://github.com/zuckersalzundpfeffer/gridsome/issues/711)) ([28278f7](https://github.com/zuckersalzundpfeffer/gridsome/commit/28278f7419cc1ffc2ff19a40355be8228db0dbe8))
* **app:** redirect to fallback route if not found ([#1239](https://github.com/zuckersalzundpfeffer/gridsome/issues/1239)) ([41f2b0f](https://github.com/zuckersalzundpfeffer/gridsome/commit/41f2b0ff411b319cd2a018c5d1b8d256088d9e57))
* **app:** reload when assets are missing ([#488](https://github.com/zuckersalzundpfeffer/gridsome/issues/488)) ([db86a09](https://github.com/zuckersalzundpfeffer/gridsome/commit/db86a0964b0e155ce634a5a5711473c2d0311280))
* **app:** resolve pagination with trailing slash ([#430](https://github.com/zuckersalzundpfeffer/gridsome/issues/430)) ([a035311](https://github.com/zuckersalzundpfeffer/gridsome/commit/a03531198366ea8542337d7b64979a1ef09ea95a))
* **app:** respect active link class options ([#478](https://github.com/zuckersalzundpfeffer/gridsome/issues/478)) ([f27cfd6](https://github.com/zuckersalzundpfeffer/gridsome/commit/f27cfd65128c8a3a3e0345b303f40bdbb9b54443))
* **app:** set custom classes for <Pager> links ([#1234](https://github.com/zuckersalzundpfeffer/gridsome/issues/1234)) ([f2ba2a3](https://github.com/zuckersalzundpfeffer/gridsome/commit/f2ba2a385591cf09bd07b64652ee314febd431ee))
* **app:** use xhr for better IE compatibility ([81b5e84](https://github.com/zuckersalzundpfeffer/gridsome/commit/81b5e847d58445ab710b58e9ed5b16dd2edb4ed5))
* **assets:** better error message for broken images ([59919aa](https://github.com/zuckersalzundpfeffer/gridsome/commit/59919aaf58dcd0fdbefed2aff966f2af6da16f15))
* **assets:** encode generated urls ([#393](https://github.com/zuckersalzundpfeffer/gridsome/issues/393)) ([b6994c8](https://github.com/zuckersalzundpfeffer/gridsome/commit/b6994c81101f65aa43c65d3f1b24c27805712554))
* **build:** don’t inline large data sets ([#462](https://github.com/zuckersalzundpfeffer/gridsome/issues/462)) ([88f28a7](https://github.com/zuckersalzundpfeffer/gridsome/commit/88f28a72598d9909323232be1b38b85dc5ad5547))
* **build:** don’t process existing images ([3fa9efb](https://github.com/zuckersalzundpfeffer/gridsome/commit/3fa9efb493fa5dcf7ac1e2eb3313374df90ed313))
* **build:** don’t write out empty data files ([55f323d](https://github.com/zuckersalzundpfeffer/gridsome/commit/55f323d5ea107c8b8a479ddc1723cd0452831037))
* **build:** ensure column width for deprecation notices ([50a6ebb](https://github.com/zuckersalzundpfeffer/gridsome/commit/50a6ebb88e2f280fd6dc02d02859853d5f2f6935))
* **build:** ensure page context is an object ([#434](https://github.com/zuckersalzundpfeffer/gridsome/issues/434)) ([65bc3ed](https://github.com/zuckersalzundpfeffer/gridsome/commit/65bc3ed6d5b15e694f9f95a584fa3bae970f50dc))
* **build:** ensure routes always have the same order ([#1247](https://github.com/zuckersalzundpfeffer/gridsome/issues/1247)) ([da5674f](https://github.com/zuckersalzundpfeffer/gridsome/commit/da5674fd248fd518963328628d578c0c93451d95))
* **build:** keep dist folder between builds ([#409](https://github.com/zuckersalzundpfeffer/gridsome/issues/409)) ([1ef584b](https://github.com/zuckersalzundpfeffer/gridsome/commit/1ef584b6388ef6ee7f8cb2cae78c089fddd9328b))
* **build:** keep webpack hash between builds ([#1247](https://github.com/zuckersalzundpfeffer/gridsome/issues/1247)) ([e184813](https://github.com/zuckersalzundpfeffer/gridsome/commit/e1848132f0466cb4bf2dc0a4bfe621cc9599e1ad))
* **build:** set correct dest path for files ([#221](https://github.com/zuckersalzundpfeffer/gridsome/issues/221)) ([f9dad9e](https://github.com/zuckersalzundpfeffer/gridsome/commit/f9dad9e89660db02923cbfbc4cd7ee5729f04892))
* **build:** show better error messages ([b71bcc6](https://github.com/zuckersalzundpfeffer/gridsome/commit/b71bcc6192066b122a8818385ced32d39bcad9f8))
* **build:** stabilize image processing worker ([#501](https://github.com/zuckersalzundpfeffer/gridsome/issues/501)) ([9d66273](https://github.com/zuckersalzundpfeffer/gridsome/commit/9d66273c9d62e7b36ade8642b79df526170fd30e))
* **build:** support symlinks in static folder ([#671](https://github.com/zuckersalzundpfeffer/gridsome/issues/671)) ([d35ec39](https://github.com/zuckersalzundpfeffer/gridsome/commit/d35ec39ba8fab826e4ecfeae2ea3bfe8926e6e62))
* **build:** use pretty path in render queue ([699b027](https://github.com/zuckersalzundpfeffer/gridsome/commit/699b027e5b92109b9dc02c9b6b52b01246844e75))
* **build:** warm up sharp to prevent xmllib error ([918e76b](https://github.com/zuckersalzundpfeffer/gridsome/commit/918e76be556aece82ef50c23777f4acc2b2467e8))
* **config:** load custom favicon config ([#526](https://github.com/zuckersalzundpfeffer/gridsome/issues/526)) ([73a4c38](https://github.com/zuckersalzundpfeffer/gridsome/commit/73a4c388336c1467b0b1eb0de5a51286b4f73c47))
* **develop:** always use port from cli args ([d94c76c](https://github.com/zuckersalzundpfeffer/gridsome/commit/d94c76cf3ac57a866db32a59f2cd99752a9e3b0d)), closes [http-party/node-portfinder#84](https://github.com/http-party/node-portfinder/issues/84)
* **develop:** ensure dynamic page loads on first run ([6357f19](https://github.com/zuckersalzundpfeffer/gridsome/commit/6357f1934510e8fae2d950c6074818b35e70fcba))
* **develop:** guard against sockjs `null` argument ([#1383](https://github.com/zuckersalzundpfeffer/gridsome/issues/1383)) ([ed99c62](https://github.com/zuckersalzundpfeffer/gridsome/commit/ed99c62fc81c7886484a55493c5502cb900832ea))
* **develop:** refresh query results on navigation ([0ce8de3](https://github.com/zuckersalzundpfeffer/gridsome/commit/0ce8de391e1894ecbedc66c97ccb0e81316a1aa1))
* **develop:** request graphql endpoint without page path ([#518](https://github.com/zuckersalzundpfeffer/gridsome/issues/518)) ([d9c0eec](https://github.com/zuckersalzundpfeffer/gridsome/commit/d9c0eecacd585ff19763aa97a65514487845b923))
* **develop:** run sockjs on main port ([e78503b](https://github.com/zuckersalzundpfeffer/gridsome/commit/e78503be2fa3eef9a7c80ea3cdde0d31caf040c8))
* **develop:** show 404 for page/1 in development ([#515](https://github.com/zuckersalzundpfeffer/gridsome/issues/515)) ([9a10a37](https://github.com/zuckersalzundpfeffer/gridsome/commit/9a10a37d54b5c6a292c35662cdb5fe4bc33822da))
* **develop:** show deprecation notices ([#639](https://github.com/zuckersalzundpfeffer/gridsome/issues/639)) ([9ed78c9](https://github.com/zuckersalzundpfeffer/gridsome/commit/9ed78c98958b6108cff95afcd97b6e87d8fc8184))
* **develop:** show original error when no filename ([eb702d8](https://github.com/zuckersalzundpfeffer/gridsome/commit/eb702d848541ae0e96d083e3923f86ba07532b52))
* **develop:** use some webpack dev server options ([d009325](https://github.com/zuckersalzundpfeffer/gridsome/commit/d0093257d5c676c05eee26b9089982121f34bc5b))
* **develop:** yarn PnP in develop ([#1434](https://github.com/zuckersalzundpfeffer/gridsome/issues/1434)) ([c2a71f5](https://github.com/zuckersalzundpfeffer/gridsome/commit/c2a71f52962477f33988ed7700ee5ddb6b2acb40))
* **explore:** set correct mode for explore command ([#435](https://github.com/zuckersalzundpfeffer/gridsome/issues/435)) ([08b312e](https://github.com/zuckersalzundpfeffer/gridsome/commit/08b312e9818bdbec52c782d2648efc5253dc41ba))
* **g-image:** add height attribute ([#1257](https://github.com/zuckersalzundpfeffer/gridsome/issues/1257)) ([bc8d3c4](https://github.com/zuckersalzundpfeffer/gridsome/commit/bc8d3c4e0ab911215c43c41176608ec9f30ece82))
* **g-image:** data uri w3c compliance ([#1438](https://github.com/zuckersalzundpfeffer/gridsome/issues/1438)) ([9330b63](https://github.com/zuckersalzundpfeffer/gridsome/commit/9330b6371cb7dfa0e1fe6c36ad9b8ba2318bbc27))
* **g-image:** exclude base64 data when not lazy loading ([#1318](https://github.com/zuckersalzundpfeffer/gridsome/issues/1318)) ([be15ba8](https://github.com/zuckersalzundpfeffer/gridsome/commit/be15ba89518d73178613ca50d19cbe091363e6d0))
* **g-image:** fallback to dataUri if image fails to load ([#1430](https://github.com/zuckersalzundpfeffer/gridsome/issues/1430)) ([0b4a4b5](https://github.com/zuckersalzundpfeffer/gridsome/commit/0b4a4b5957062f9d71f814dcd2ee8d1c3b8d847a))
* **g-image:** fix size for fit inside and fit outside ([#608](https://github.com/zuckersalzundpfeffer/gridsome/issues/608)) ([ff88566](https://github.com/zuckersalzundpfeffer/gridsome/commit/ff88566493dfb98c1017f72f576ccf932c5e208d))
* **g-image:** height attribute in generated markup ([#1257](https://github.com/zuckersalzundpfeffer/gridsome/issues/1257)) ([71f4184](https://github.com/zuckersalzundpfeffer/gridsome/commit/71f41848a5fb53d180513118a662aeef6344e436))
* **g-image:** improve edges in blurred placeholders ([7a2080e](https://github.com/zuckersalzundpfeffer/gridsome/commit/7a2080ef39621d4e15f97fffa3442404549009ac))
* **g-image:** maintain blur placeholder aspect ratio ([7c81f8c](https://github.com/zuckersalzundpfeffer/gridsome/commit/7c81f8c0f96b14ed8da8645280af10ac519ec327))
* **g-image:** option for disabling compression ([#1256](https://github.com/zuckersalzundpfeffer/gridsome/issues/1256)) ([7e6691f](https://github.com/zuckersalzundpfeffer/gridsome/commit/7e6691febd5ba7de40b33a15de6940fead8316cd))
* **g-image:** optional `srcset` and `sizes` ([#1574](https://github.com/zuckersalzundpfeffer/gridsome/issues/1574)) ([dbb55d7](https://github.com/zuckersalzundpfeffer/gridsome/commit/dbb55d7c4180ca34c16cb74259721797dc1e83eb))
* **g-image:** prevent increased image sizes ([#1256](https://github.com/zuckersalzundpfeffer/gridsome/issues/1256)) ([20776c9](https://github.com/zuckersalzundpfeffer/gridsome/commit/20776c90e8ad48bbb653ed5358e303d44093750e))
* **g-image:** proper immediate typing and behaviour ([#1372](https://github.com/zuckersalzundpfeffer/gridsome/issues/1372)) ([a4c9d1f](https://github.com/zuckersalzundpfeffer/gridsome/commit/a4c9d1f061427a50ae84b3dea3f2881e0562cbd3))
* **g-image:** support uppercase file extensions ([#1381](https://github.com/zuckersalzundpfeffer/gridsome/issues/1381)) ([063c984](https://github.com/zuckersalzundpfeffer/gridsome/commit/063c98444d3e3c59c0536e5b3b784dedc5d9e109))
* **g-link:** add support for v-html ([#1373](https://github.com/zuckersalzundpfeffer/gridsome/issues/1373)) ([3762ecd](https://github.com/zuckersalzundpfeffer/gridsome/commit/3762ecd1d5d16d91d2976ef2dbdcea86fb5f0dba))
* **graphql:** add missing ref exists functions ([#1252](https://github.com/zuckersalzundpfeffer/gridsome/issues/1252)) ([83b0f96](https://github.com/zuckersalzundpfeffer/gridsome/commit/83b0f966fcdd3ae6a1e0231985d45c3f2e74a308))
* **graphql:** add schema.createScalarType() method ([5f59747](https://github.com/zuckersalzundpfeffer/gridsome/commit/5f59747f6f5d1855c0b1bcd46308dfe62d19e9ad))
* **graphql:** auto create missing reference fields ([9a4d24c](https://github.com/zuckersalzundpfeffer/gridsome/commit/9a4d24c2f93703d6d74f29d3c926e3ce32ca37ab))
* **graphql:** better error message for reserved type names ([#1388](https://github.com/zuckersalzundpfeffer/gridsome/issues/1388)) ([f9cfa4b](https://github.com/zuckersalzundpfeffer/gridsome/commit/f9cfa4b3a4c5156c55001320b8771504438df479))
* **graphql:** convert to input type correctly ([#1338](https://github.com/zuckersalzundpfeffer/gridsome/issues/1338)) ([09478fc](https://github.com/zuckersalzundpfeffer/gridsome/commit/09478fc16b8701581e339aec8e09e6e5ab384d7f))
* **graphql:** do not camelCase field names automatically ([#351](https://github.com/zuckersalzundpfeffer/gridsome/issues/351)) ([4e54c5c](https://github.com/zuckersalzundpfeffer/gridsome/commit/4e54c5c566d68170e9e3ad63f142dcd41fa2fb03))
* **graphql:** don’t create empty fields in objects ([#713](https://github.com/zuckersalzundpfeffer/gridsome/issues/713)) ([b4776e2](https://github.com/zuckersalzundpfeffer/gridsome/commit/b4776e2cf1b219ce421f8f6eb2f098959aff6bc3))
* **graphql:** don’t create fields for lists with invalid values ([f635e8b](https://github.com/zuckersalzundpfeffer/gridsome/commit/f635e8b4380c30a00586f3bc0e461df16330a43d))
* **graphql:** don’t create input types for unions ([c4ba3c5](https://github.com/zuckersalzundpfeffer/gridsome/commit/c4ba3c5868549e26e93f93b874c0e30af2d4b9ac))
* **graphql:** don’t fix unknown variable types ([8e45485](https://github.com/zuckersalzundpfeffer/gridsome/commit/8e454857a3dbce19040270af3268c2c190a6cd56))
* **graphql:** don’t fix variables for other types ([#689](https://github.com/zuckersalzundpfeffer/gridsome/issues/689)) ([35cfd2b](https://github.com/zuckersalzundpfeffer/gridsome/commit/35cfd2b51c0a8feb6f6dc0591faf55081a838f5a))
* **graphql:** don’t process empty object fields ([#662](https://github.com/zuckersalzundpfeffer/gridsome/issues/662)) ([7852e9e](https://github.com/zuckersalzundpfeffer/gridsome/commit/7852e9e2c8e981496072fed28789ac34b9005444))
* **graphql:** don’t process invalid references ([b88960e](https://github.com/zuckersalzundpfeffer/gridsome/commit/b88960ed59fd5da0c910c665921bd4db429bf313))
* **graphql:** don’t transform missing input types ([6e2f28e](https://github.com/zuckersalzundpfeffer/gridsome/commit/6e2f28e024ac463f93ef34b6af59bf9f2a1411cb))
* **graphql:** ensure field value is array for lists ([8e02ccd](https://github.com/zuckersalzundpfeffer/gridsome/commit/8e02ccd9ac3d9ed9eea3990ad80a064b4218d32b))
* **graphql:** ensure inferred fields are added to filters ([#718](https://github.com/zuckersalzundpfeffer/gridsome/issues/718)) ([18d0091](https://github.com/zuckersalzundpfeffer/gridsome/commit/18d009168c01955a1f006a1cbf95073e33634afc))
* **graphql:** ensure totalPages count is not null ([ae75b39](https://github.com/zuckersalzundpfeffer/gridsome/commit/ae75b397604eb179cbc169314560cd69c08aa577))
* **graphql:** fix metadata module error ([598de72](https://github.com/zuckersalzundpfeffer/gridsome/commit/598de728b08f036f61ffcc0ef4ee2dae6da96901))
* **graphql:** fix union fields by addReference() ([99e2ce8](https://github.com/zuckersalzundpfeffer/gridsome/commit/99e2ce84b5535bc7f079574c656d490d533ed2cd))
* **graphql:** ignore trailing slash for path argument ([2b5d17f](https://github.com/zuckersalzundpfeffer/gridsome/commit/2b5d17ff51e29d76e831ef1ea67e1ccafabc905b))
* **graphql:** image background argument ([#596](https://github.com/zuckersalzundpfeffer/gridsome/issues/596)) ([1f7702c](https://github.com/zuckersalzundpfeffer/gridsome/commit/1f7702cb486365f885cf800f3b2b93548c4b7699))
* **graphql:** prevent infinite loop while creating input types ([7e5f863](https://github.com/zuckersalzundpfeffer/gridsome/commit/7e5f863199d86b9d0eeb288719cbe96765cbc7ac))
* **graphql:** process images in list ([#609](https://github.com/zuckersalzundpfeffer/gridsome/issues/609)) ([97590d0](https://github.com/zuckersalzundpfeffer/gridsome/commit/97590d02531571804fd76124bd883d39e5f4e359))
* **graphql:** process object types only once ([11416ac](https://github.com/zuckersalzundpfeffer/gridsome/commit/11416acf06ea6f7d8668949170dac33b42ed88e0))
* **graphql:** proxy invalid reference field names ([b23df81](https://github.com/zuckersalzundpfeffer/gridsome/commit/b23df81baacf1ba2be472283e8f535188096a354))
* **graphql:** require resolve for custom resolvers ([63da3dd](https://github.com/zuckersalzundpfeffer/gridsome/commit/63da3dddcf7d8e61d943807f94ade121e3e04df2))
* **graphql:** resolve deprecated node.fields field ([#477](https://github.com/zuckersalzundpfeffer/gridsome/issues/477)) ([36911bd](https://github.com/zuckersalzundpfeffer/gridsome/commit/36911bdabfa4ff00f2fa1239c1f54a32caec775e))
* **graphql:** return 404 for missing pages ([7e3fe84](https://github.com/zuckersalzundpfeffer/gridsome/commit/7e3fe848fb2a48272d159c566623b4f0bae576a3))
* **graphql:** return last node if no arguments ([#541](https://github.com/zuckersalzundpfeffer/gridsome/issues/541)) ([865728a](https://github.com/zuckersalzundpfeffer/gridsome/commit/865728a1275e79030cd3b7efebe32eeecb923714))
* **graphql:** return null if date value is null or falsy ([#527](https://github.com/zuckersalzundpfeffer/gridsome/issues/527)) ([3b4de3a](https://github.com/zuckersalzundpfeffer/gridsome/commit/3b4de3acbcdc503e167a4ec644f78bdbd06359c8))
* **graphql:** set sdl type def with addReference ([619b510](https://github.com/zuckersalzundpfeffer/gridsome/commit/619b5104307d3b5d6f839252472bb109596c30be))
* **graphql:** update variables when query changes ([0fc0056](https://github.com/zuckersalzundpfeffer/gridsome/commit/0fc00567b71a44f1ae4bff227c058de0af5249be))
* **graphql:** use correct typeName for belongsTo pagination ([#422](https://github.com/zuckersalzundpfeffer/gridsome/issues/422)) ([b06310f](https://github.com/zuckersalzundpfeffer/gridsome/commit/b06310f9df36d64a8009d1656e6320dd957dae89))
* **graphql:** validate static queries ([b9e79f2](https://github.com/zuckersalzundpfeffer/gridsome/commit/b9e79f29c32b8cf61df7f6e89ec5eed9fa777e5b))
* **gridsome:** add undeclared dependency vue-style-loader ([cbcede6](https://github.com/zuckersalzundpfeffer/gridsome/commit/cbcede6692e9a29bcce01f9ed112d508d9e653bc))
* **gridsome:** require.resolve develop entries ([ceed033](https://github.com/zuckersalzundpfeffer/gridsome/commit/ceed033b168f14c866d4dc8210562a561b975dca))
* **gridsome:** require.resolve style loaders ([1af3a9a](https://github.com/zuckersalzundpfeffer/gridsome/commit/1af3a9a3dc255b9ba5d5276f81c6353ef4441dea))
* **gridsome:** require.resolve webpack loaders ([1c983d5](https://github.com/zuckersalzundpfeffer/gridsome/commit/1c983d575ed7d5584301d84fcbbba6a59bfdb143))
* **pager:** make showLinks prop work correctly  ([#215](https://github.com/zuckersalzundpfeffer/gridsome/issues/215)) ([#1429](https://github.com/zuckersalzundpfeffer/gridsome/issues/1429)) ([f0b9bc7](https://github.com/zuckersalzundpfeffer/gridsome/commit/f0b9bc7604551055f504d2494db20a9375ce5d90))
* **pages:** set page context in dev mode ([#417](https://github.com/zuckersalzundpfeffer/gridsome/issues/417)) ([a7a6e17](https://github.com/zuckersalzundpfeffer/gridsome/commit/a7a6e17e0d4a66bc04b90b50303a9b78972e7d9b))
* **pages:** show an error if component is not found ([654d075](https://github.com/zuckersalzundpfeffer/gridsome/commit/654d075cfa2db0064ece16a666dcfc7b954643a7))
* **store:** create reference to node instance ([81bb047](https://github.com/zuckersalzundpfeffer/gridsome/commit/81bb04717224204922f161313bd2896ac7d2448f))
* **store:** do not resolve emails ([#500](https://github.com/zuckersalzundpfeffer/gridsome/issues/500)) ([6105069](https://github.com/zuckersalzundpfeffer/gridsome/commit/6105069738a18a69953e2f53c474ae24ab6698ed))
* **store:** do not slugify id in routes ([#429](https://github.com/zuckersalzundpfeffer/gridsome/issues/429)) ([308beff](https://github.com/zuckersalzundpfeffer/gridsome/commit/308beffd5813e291e80dea554b58e486220cf2db))
* **store:** keep custom _id field on node ([bee711c](https://github.com/zuckersalzundpfeffer/gridsome/commit/bee711c99e52a20fb5213ffa2fb20ed0a46350fd))
* **store:** resolve absolute url paths ([990b673](https://github.com/zuckersalzundpfeffer/gridsome/commit/990b673d5407aca4825e2fc1c5b40cfa0402f620))
* **store:** return collection in getCollection action ([7f0a631](https://github.com/zuckersalzundpfeffer/gridsome/commit/7f0a6312c120eaa27d9f6bfb2fdbda4b20220f7b))
* **store:** use custom year, month or day fields if they exist ([91728ef](https://github.com/zuckersalzundpfeffer/gridsome/commit/91728ef1237fcb4db032ef0bd8d99604f86e7f61))
* **templates:** don't allow reserved names ([#1427](https://github.com/zuckersalzundpfeffer/gridsome/issues/1427)) ([4abeeed](https://github.com/zuckersalzundpfeffer/gridsome/commit/4abeeed83eb2c9dfdebed3e93f714ce7767f6b6f))
* **templates:** fix templates on windows ([a80fb76](https://github.com/zuckersalzundpfeffer/gridsome/commit/a80fb76d9eb55f958be5d789e11430d62df0fb92))
* **templates:** preserve trailing slash in routes ([f7b5397](https://github.com/zuckersalzundpfeffer/gridsome/commit/f7b5397eed3963ac60ac86077636bfb205cebb5e))
* **templates:** skip auto template if no node paths ([2e72f5f](https://github.com/zuckersalzundpfeffer/gridsome/commit/2e72f5fc99cba4fa5307565b536f7ff31e9b4c25))
* **templates:** throw error if component is missing in prod ([350f9f5](https://github.com/zuckersalzundpfeffer/gridsome/commit/350f9f5ad7667e2c76467adccc3c9d3942888b16)), closes [#702](https://github.com/zuckersalzundpfeffer/gridsome/issues/702)
* alias vue to an absolute path ([432c005](https://github.com/zuckersalzundpfeffer/gridsome/commit/432c005fca02f6775ae3a099156d1d9436c58ac6))
* provide vue-server-renderer with a basedir ([3f60762](https://github.com/zuckersalzundpfeffer/gridsome/commit/3f6076235a4de27e3c0186603fa64243fd6efe6f))
* remove unnecessary modules ([b5f5a48](https://github.com/zuckersalzundpfeffer/gridsome/commit/b5f5a482c8fe95f67b147ed58a081c210455e8fa))
* resolve plugins relative to config ([42f3d21](https://github.com/zuckersalzundpfeffer/gridsome/commit/42f3d217ef2a89749092132cb69ebba58af5036a))
* **app:** add extra debugging output on hash mismatch failure ([#1150](https://github.com/zuckersalzundpfeffer/gridsome/issues/1150)) ([dc1a3fe](https://github.com/zuckersalzundpfeffer/gridsome/commit/dc1a3fe528f61c97b1dab0b34fb93076a33cdf08))
* **app:** add trailing slash to paths in Pager component ([#1073](https://github.com/zuckersalzundpfeffer/gridsome/issues/1073)) ([a559bb8](https://github.com/zuckersalzundpfeffer/gridsome/commit/a559bb8138f5021c22d00777c7b6021c5a4f36dd))
* **app:** allow absolute path to custom favicon ([53a755c](https://github.com/zuckersalzundpfeffer/gridsome/commit/53a755c28de8d34ff4eb78c32dec681b2bc61a1e))
* **app:** allow css.split option to be true ([#266](https://github.com/zuckersalzundpfeffer/gridsome/issues/266)) ([a0fcd10](https://github.com/zuckersalzundpfeffer/gridsome/commit/a0fcd10ca7d10adb2307685e482b6a7762a84d7b))
* **app:** allow custom routes from router.addRoutes ([fc78a59](https://github.com/zuckersalzundpfeffer/gridsome/commit/fc78a59debf92725302866cc8bbd031a100cf43d))
* **app:** allow pascal cased g-link and g-image ([#985](https://github.com/zuckersalzundpfeffer/gridsome/issues/985)) ([b4805eb](https://github.com/zuckersalzundpfeffer/gridsome/commit/b4805eb3b01806fea53ced94e91a55b6754879a2))
* **app:** don't resolve url for different port ([#350](https://github.com/zuckersalzundpfeffer/gridsome/issues/350)) ([a6ab23f](https://github.com/zuckersalzundpfeffer/gridsome/commit/a6ab23f098b56b4fc2e471f4ba038afc2de9893b))
* **app:** don’t handle external links with router ([#367](https://github.com/zuckersalzundpfeffer/gridsome/issues/367)) ([bfb2a79](https://github.com/zuckersalzundpfeffer/gridsome/commit/bfb2a7964e2253e37d8f83813fbffeb4e272b98a))
* **app:** don’t preload /404 without page-query ([5835733](https://github.com/zuckersalzundpfeffer/gridsome/commit/5835733ee65d62a61cbc57a52129f949b883ec63))
* **app:** don’t resolve constructor components ([#552](https://github.com/zuckersalzundpfeffer/gridsome/issues/552)) ([a4e22d6](https://github.com/zuckersalzundpfeffer/gridsome/commit/a4e22d6e8f21be360a7e750dcfea27180910cbe4))
* **app:** fetch data properly for homepage ([#218](https://github.com/zuckersalzundpfeffer/gridsome/issues/218)) ([fd72abc](https://github.com/zuckersalzundpfeffer/gridsome/commit/fd72abc794d6f657904bed24c59b04f0752a2ed7))
* **app:** keep original path when showing 404 ([f0efbaa](https://github.com/zuckersalzundpfeffer/gridsome/commit/f0efbaa2a0c11f0adf8e6ad12b56e2c081fd71c3))
* **app:** make routes appear in vue-devtools ([#322](https://github.com/zuckersalzundpfeffer/gridsome/issues/322)) ([f1a865c](https://github.com/zuckersalzundpfeffer/gridsome/commit/f1a865cdf7e39f6bdaf5180c05d841df9b2ca5f9))
* **app:** only intercept left clicks on links ([#236](https://github.com/zuckersalzundpfeffer/gridsome/issues/236)) ([78413dc](https://github.com/zuckersalzundpfeffer/gridsome/commit/78413dcedb3a7525043059764b6503ee0a419289))
* **app:** preload data for links in view ([35411aa](https://github.com/zuckersalzundpfeffer/gridsome/commit/35411aab1d5d4e0a35433bae87e432f97deab959))
* **app:** unslash path before fetching data ([7c086a7](https://github.com/zuckersalzundpfeffer/gridsome/commit/7c086a780d6524c4c46e062999583c0b2b2dd283))
* **build:** ensure data directory exists before building ([#93](https://github.com/zuckersalzundpfeffer/gridsome/issues/93)) ([3453aff](https://github.com/zuckersalzundpfeffer/gridsome/commit/3453affee1acc3263b5a9d1bc00124622714ec51))
* **build:** fail if path resolves to 404 ([#218](https://github.com/zuckersalzundpfeffer/gridsome/issues/218)) ([b3b7add](https://github.com/zuckersalzundpfeffer/gridsome/commit/b3b7addb5c32b81a038159b1138337fd2828e611))
* **build:** put images in correct folder when pathPrefix is used ([#221](https://github.com/zuckersalzundpfeffer/gridsome/issues/221)) ([497998c](https://github.com/zuckersalzundpfeffer/gridsome/commit/497998c61525042a4e688c39fc5ec3d8270ea68a))
* **build:** query context for templates with static route ([a962482](https://github.com/zuckersalzundpfeffer/gridsome/commit/a96248219973eef27d45ea735262346d869ff6b0))
* **build:** render pagination correctly for root path ([#218](https://github.com/zuckersalzundpfeffer/gridsome/issues/218)) ([1ee57fe](https://github.com/zuckersalzundpfeffer/gridsome/commit/1ee57fe1e56d8e30bf229f4a3a178d9abf15f92d))
* **build:** render template with static route and pagination once ([2f4d93a](https://github.com/zuckersalzundpfeffer/gridsome/commit/2f4d93ad65570d4ef07468134d4af5023cb3d6ba))
* **develop:** allow OPTIONS method request to /___graphql ([#271](https://github.com/zuckersalzundpfeffer/gridsome/issues/271)) ([f1ec997](https://github.com/zuckersalzundpfeffer/gridsome/commit/f1ec997acaad45f4e2c6664fcc9f50eadb68abcd))
* **develop:** show /404 for non existing paths ([b18e8e9](https://github.com/zuckersalzundpfeffer/gridsome/commit/b18e8e94d857fdadd341e72b32928e6a3929d994))
* **develop:** update static-query when source changes ([d867e93](https://github.com/zuckersalzundpfeffer/gridsome/commit/d867e934ea12c4c60ec4d4c0ba0aa93ef82c8bd8))
* **g-image:** add static classes to noscript image ([#203](https://github.com/zuckersalzundpfeffer/gridsome/issues/203)) ([c4036b8](https://github.com/zuckersalzundpfeffer/gridsome/commit/c4036b85f1bd3ee0a9e023746573ff4b5339e1d4))
* **g-image:** alt attribute for noscript image ([#353](https://github.com/zuckersalzundpfeffer/gridsome/issues/353)) ([fcfcf36](https://github.com/zuckersalzundpfeffer/gridsome/commit/fcfcf3696d6ea3257024d47c3b3c397557921be2))
* **g-image:** increase max image width ([#286](https://github.com/zuckersalzundpfeffer/gridsome/issues/286)) ([8a7ae89](https://github.com/zuckersalzundpfeffer/gridsome/commit/8a7ae892377c33ecf05b8dc84e17fc663fc4d286))
* **g-image:** refresh when src updates on same element ([7128fd6](https://github.com/zuckersalzundpfeffer/gridsome/commit/7128fd6760005357877fbe30475fe57895044acc))
* **g-image:** remove duplicate class names ([2de526f](https://github.com/zuckersalzundpfeffer/gridsome/commit/2de526f02a48118f81d75e0845e7c0faf6934122))
* **graphq:** siteDescription as metaData ([#260](https://github.com/zuckersalzundpfeffer/gridsome/issues/260)) ([640f72d](https://github.com/zuckersalzundpfeffer/gridsome/commit/640f72de8849324ba4cdd4779a963a90600ce676))
* **graphql:** allow requests without variables ([#323](https://github.com/zuckersalzundpfeffer/gridsome/issues/323)) ([8184834](https://github.com/zuckersalzundpfeffer/gridsome/commit/81848349b41bd7f26200569c147c3a3f7a32889f))
* **graphql:** don’t fail when invalid page-query ([d143767](https://github.com/zuckersalzundpfeffer/gridsome/commit/d14376798eb67ce9e5f733d3314bae2436b8baf5))
* **graphql:** don’t process non graphql requests ([#220](https://github.com/zuckersalzundpfeffer/gridsome/issues/220)) ([c276b98](https://github.com/zuckersalzundpfeffer/gridsome/commit/c276b98795aa869710146e78091f2d76e28c3022))
* **graphql:** improve graphql error handling ([#204](https://github.com/zuckersalzundpfeffer/gridsome/issues/204)) ([767b674](https://github.com/zuckersalzundpfeffer/gridsome/commit/767b674f235697506c402dd97d026065aa99f940))
* **graphql:** prefer float when mixed number types ([#332](https://github.com/zuckersalzundpfeffer/gridsome/issues/332)) ([b311850](https://github.com/zuckersalzundpfeffer/gridsome/commit/b31185058f7097c6b7c2c32261ff4cbc5fcda1af))
* **pager:** bind linkClass to an object ([#257](https://github.com/zuckersalzundpfeffer/gridsome/issues/257)) ([6765a3d](https://github.com/zuckersalzundpfeffer/gridsome/commit/6765a3d076205fb1087d76b352b74b35adb528af))
* **store:** handle route params starting with raw correctly ([#295](https://github.com/zuckersalzundpfeffer/gridsome/issues/295)) ([931937c](https://github.com/zuckersalzundpfeffer/gridsome/commit/931937c6e94e2d49adfb3d8dcf1587b4510d9303))
* **store:** keep references for empty arrays ([ec6fcf9](https://github.com/zuckersalzundpfeffer/gridsome/commit/ec6fcf9639f030100c9a7e2d3b3d0d6da07220cd))
* **store:** prioritize node.id over node.fields.id ([3d7c180](https://github.com/zuckersalzundpfeffer/gridsome/commit/3d7c180be776a582504d6c0099945d810748df06))
* **store:** support repeated segments in dynamic routes ([#279](https://github.com/zuckersalzundpfeffer/gridsome/issues/279)) ([2259f85](https://github.com/zuckersalzundpfeffer/gridsome/commit/2259f85de11f0b0139d2c0cfac87c6be0217ae35))
* count minimum one physical cpu ([#255](https://github.com/zuckersalzundpfeffer/gridsome/issues/255)) ([91444c7](https://github.com/zuckersalzundpfeffer/gridsome/commit/91444c70a6a7aa2aff453012525d4aed7c9d6fe1))
* pin jest-worker version until fix is published ([#252](https://github.com/zuckersalzundpfeffer/gridsome/issues/252)) ([c0d15b6](https://github.com/zuckersalzundpfeffer/gridsome/commit/c0d15b65b950d0ac73756adf28f032454dc91bbe))
* **app:** add format-detection meta tag ([#145](https://github.com/zuckersalzundpfeffer/gridsome/issues/145)) ([f7f94ae](https://github.com/zuckersalzundpfeffer/gridsome/commit/f7f94aef41c88ac08388d7284d06803f2944fb6e))
* **app:** add key to viewport meta ([#169](https://github.com/zuckersalzundpfeffer/gridsome/issues/169)) ([c7f6dfa](https://github.com/zuckersalzundpfeffer/gridsome/commit/c7f6dfa3a265b709d4dd36f5fb0a9b2fbaf11607))
* **app:** custom favicon path ([#149](https://github.com/zuckersalzundpfeffer/gridsome/issues/149)) ([f6b6b3d](https://github.com/zuckersalzundpfeffer/gridsome/commit/f6b6b3d8443b2d73f6ce8fc6ee5ad2a3efe02732)), closes [#138](https://github.com/zuckersalzundpfeffer/gridsome/issues/138)
* **app:** use default link behavior if 404 ([f9aeed7](https://github.com/zuckersalzundpfeffer/gridsome/commit/f9aeed7b6562f6f4086deef3c76a48fa7fdef159))
* **build:** clear cached data files ([909caa0](https://github.com/zuckersalzundpfeffer/gridsome/commit/909caa03bdd8b40d890f06d5b3e54d982a199be1))
* **build:** fix beforeProcessAssets hook name ([8eafe68](https://github.com/zuckersalzundpfeffer/gridsome/commit/8eafe68e1b1c2aea38fd6f8645a1d034beb7785c))
* **build:** use correct path for pagination ([e8a642c](https://github.com/zuckersalzundpfeffer/gridsome/commit/e8a642ca475e8f5cf37000106c19374499e23f5d))
* **favicon:** set mime type for icons in head ([bface4d](https://github.com/zuckersalzundpfeffer/gridsome/commit/bface4d53caeabb052ac390bf0cae91971bd4f10))
* **g-link:** link to local files ([ece2de5](https://github.com/zuckersalzundpfeffer/gridsome/commit/ece2de56e212f48778337908e15286e08bbd5d64))
* **graphql:** do not use file type for urls ([fd14b44](https://github.com/zuckersalzundpfeffer/gridsome/commit/fd14b44841c7c39f1eff60692bf81aba875db676))
* **graphql:** do not use file type if no extension ([3b1fb7c](https://github.com/zuckersalzundpfeffer/gridsome/commit/3b1fb7c9d501c144511d66773d8b30927f931845))
* **graphql:** dont infer filename as file type ([3a04df9](https://github.com/zuckersalzundpfeffer/gridsome/commit/3a04df946d888f574ef76739c6c8556e06875c1c))
* **graphql:** fix order argument for collections ([3e6a1fa](https://github.com/zuckersalzundpfeffer/gridsome/commit/3e6a1fac8ef799e8507cf1c990a47f519499e544))
* **graphql:** get node by id ([ba83545](https://github.com/zuckersalzundpfeffer/gridsome/commit/ba83545a64a598bffb23df6e4296ca6a8dba2264))
* **graphql:** get sub fields from object fields ([039a532](https://github.com/zuckersalzundpfeffer/gridsome/commit/039a5328152cc12cd51c0c9abc926c6594bf4f52))
* **graphql:** include empty string type in schema ([44b68b2](https://github.com/zuckersalzundpfeffer/gridsome/commit/44b68b2c50fe352f9f3fe40535488fae2755ad36))
* **graphql:** merge nested object fields ([f2e9d4a](https://github.com/zuckersalzundpfeffer/gridsome/commit/f2e9d4ac91151ef434d3f7078330bcc80cbdb536))
* **graphql:** return correct dates ([1965091](https://github.com/zuckersalzundpfeffer/gridsome/commit/196509191196c295ae7e4649326c5b751bdb5818))
* **graphql:** transform nested invalid field names ([5555354](https://github.com/zuckersalzundpfeffer/gridsome/commit/555535451e1975f8ef055969d0539c37d137522f))
* **image:** add more attributes to markup ([5c5052d](https://github.com/zuckersalzundpfeffer/gridsome/commit/5c5052d8705a63d2171dba0c97d6ffa6706cac92))
* **image:** exclude unecessary data ([574928c](https://github.com/zuckersalzundpfeffer/gridsome/commit/574928c64b4b3816cd39f38c1a2a0cc501052743))
* **image:** render fallback as html string ([738ef23](https://github.com/zuckersalzundpfeffer/gridsome/commit/738ef234e6a7134658cd28b88733f14dc4a72ecc))
* **ssr:** render body scripts from vue-meta ([b4b50bd](https://github.com/zuckersalzundpfeffer/gridsome/commit/b4b50bdea37d07e67ace8778efee59cd23fcd8b2))
* **touchicon:** use correct sizes when custom icon ([db1c349](https://github.com/zuckersalzundpfeffer/gridsome/commit/db1c3491171e3b36f8cdfd6f91d9d1cc39556c7a))
* **webpack:** absolute path to 404 fallback ([97e5e36](https://github.com/zuckersalzundpfeffer/gridsome/commit/97e5e369b8d21cf9d40ac3a00a8432be1019a3ee)), closes [#43](https://github.com/zuckersalzundpfeffer/gridsome/issues/43)
* **webpack:** allow async chainWebpack ([a0caa84](https://github.com/zuckersalzundpfeffer/gridsome/commit/a0caa8402b361f0a1598d7a595147039a73cb4b2))
* handle urls in process queue ([60623ee](https://github.com/zuckersalzundpfeffer/gridsome/commit/60623ee82cce564623f46a03895a6df90d54f088))
* keep hash when resolving raw html links ([87860ab](https://github.com/zuckersalzundpfeffer/gridsome/commit/87860ab97c67e7d35a8c80cdbc386475e3b655ad))
* re-create routes after a node.path change ([b6e16c9](https://github.com/zuckersalzundpfeffer/gridsome/commit/b6e16c9f0f674132018c8bcec199687b4a142601))
* **webpack:** load local babel config files ([975bfea](https://github.com/zuckersalzundpfeffer/gridsome/commit/975bfea4f4235211a00fc814d194ff40a9e0531a))
* **webpack:** run chainWebpack after all plugins ([2cc5850](https://github.com/zuckersalzundpfeffer/gridsome/commit/2cc585057da027f0376ee326a651125da24678d7))
* clear errors in terminal when resolved ([832e7de](https://github.com/zuckersalzundpfeffer/gridsome/commit/832e7dee3b6145f2f9c95e6a052c46a50638690b))
* don’t create routes for missing content types ([9eb216e](https://github.com/zuckersalzundpfeffer/gridsome/commit/9eb216ead6d28ffe7514c91cb0d6bc80ab314b90))
* dont fail when missing favicon.png ([829091b](https://github.com/zuckersalzundpfeffer/gridsome/commit/829091b1e5bc40f4f3b3f942e9ba196a0f9de290))
* ensure cache dir exists ([f243338](https://github.com/zuckersalzundpfeffer/gridsome/commit/f243338788bb412699518abd485083d5252ad184))
* forward slash component file path ([5c8e0d6](https://github.com/zuckersalzundpfeffer/gridsome/commit/5c8e0d64d9b40be9c2261ae29ff2c5dc0068dd00))
* freeze base config object to prevent changes ([5fad26f](https://github.com/zuckersalzundpfeffer/gridsome/commit/5fad26f01919ce42aea47d8a5e8b2576568f9e90))
* hot reload page-query in windows ([f1ab80a](https://github.com/zuckersalzundpfeffer/gridsome/commit/f1ab80a26de3cf7d616334198ea3f24c1d7507cc))
* lazy load external image urls ([4f7f867](https://github.com/zuckersalzundpfeffer/gridsome/commit/4f7f8677682621509e124ab102eec155037d6be1))
* make paths in loaders work in windows ([7e27ca1](https://github.com/zuckersalzundpfeffer/gridsome/commit/7e27ca19186c2d411f49aa661fec099e42c97e3a))
* prioritize static files ([6326958](https://github.com/zuckersalzundpfeffer/gridsome/commit/63269588856f084ad8e882bfd9611d0a9d346297))
* replace path prefix correctly in links ([90dc133](https://github.com/zuckersalzundpfeffer/gridsome/commit/90dc1337a167d37c715c8279d0574f825667eb50))
* send context to transformer ([7b50bae](https://github.com/zuckersalzundpfeffer/gridsome/commit/7b50bae3f82ae7c47ae4b182c90c3d453bd372d8))
* send context to transofmers ([0b5840e](https://github.com/zuckersalzundpfeffer/gridsome/commit/0b5840e855397af3957914824d36f49d03e3e1fd))
* send graphql to createSchema api ([86363c3](https://github.com/zuckersalzundpfeffer/gridsome/commit/86363c32a3910484ae34f7301dc3d8b114cc9750))
* update routes when source path changes ([85171cf](https://github.com/zuckersalzundpfeffer/gridsome/commit/85171cf410a3e4db19701cb8ff68ba610a3131eb))
* **image:** send quality attr to worker ([4fd5151](https://github.com/zuckersalzundpfeffer/gridsome/commit/4fd5151efa0be74110050f918288b775d08f30b7))
* use correct paths on windows ([fd624df](https://github.com/zuckersalzundpfeffer/gridsome/commit/fd624dfe343a77c1d41e034b6e70d735b772294f))
* **app:** dont sanitize inline styles and scripts ([eaac209](https://github.com/zuckersalzundpfeffer/gridsome/commit/eaac209b98ff629c79c6a9ec6184a6ce1509398e))
* **app:** ensure favicon height is set ([5164258](https://github.com/zuckersalzundpfeffer/gridsome/commit/5164258a5c1af73a3b7307a4bd128ed0307a9070))
* **app:** fix cyclic dependency when importing Pager ([#109](https://github.com/zuckersalzundpfeffer/gridsome/issues/109)) ([b8247af](https://github.com/zuckersalzundpfeffer/gridsome/commit/b8247afbc27ee333581b7df01532630ceb3e1ddf))
* **app:** include pathPrefix when hard reloading app ([#1044](https://github.com/zuckersalzundpfeffer/gridsome/issues/1044)) ([4d22712](https://github.com/zuckersalzundpfeffer/gridsome/commit/4d2271222cb44e94b9e6f7c0ca04740226c0a7ce))
* **app:** option for disabling global link catcher ([#959](https://github.com/zuckersalzundpfeffer/gridsome/issues/959)) ([3acbada](https://github.com/zuckersalzundpfeffer/gridsome/commit/3acbada56288327dee7118bde7b0d1e9b898bd5c))
* **app:** parse dates as UTC ([bb1972d](https://github.com/zuckersalzundpfeffer/gridsome/commit/bb1972def3e84c97992ce919ecab8cfd2b1ecbdc))
* **app:** prevent duplicate router.push ([508dd58](https://github.com/zuckersalzundpfeffer/gridsome/commit/508dd58ca7bb18247dd278b2a9ba8dfade5e45cf))
* **app:** reduce generated code in routes.js ([#724](https://github.com/zuckersalzundpfeffer/gridsome/issues/724)) ([5e1d49a](https://github.com/zuckersalzundpfeffer/gridsome/commit/5e1d49ad1f0069bc4e7e73b05e2e3be72a31fbbe))
* **app:** simplify IntersectionObserver check ([#153](https://github.com/zuckersalzundpfeffer/gridsome/issues/153)) ([5a0d729](https://github.com/zuckersalzundpfeffer/gridsome/commit/5a0d729991c8eef5dd50a5f66ac4c378c3891722))
* **app:** use pathPrefix option ([7edfb79](https://github.com/zuckersalzundpfeffer/gridsome/commit/7edfb795b82270798ba48dea67130addbab2f3db))
* **babel:** dont load config files ([c891593](https://github.com/zuckersalzundpfeffer/gridsome/commit/c891593b8b51186d41ee833b0fe343408dfb5396))
* **build:** adjustments for better render times ([290e92d](https://github.com/zuckersalzundpfeffer/gridsome/commit/290e92d3b2924f5a2e90e96bfbef564c2f2cdb21))
* **build:** allow overriding cpu count with env var ([#923](https://github.com/zuckersalzundpfeffer/gridsome/issues/923)) ([12c4865](https://github.com/zuckersalzundpfeffer/gridsome/commit/12c486545170feb4096ffd88600e618873884a9a))
* **build:** better error if render fails ([7158300](https://github.com/zuckersalzundpfeffer/gridsome/commit/7158300deb5b538d6ce50a0136b28658b0212139))
* **build:** check if static dir exists ([e42ca05](https://github.com/zuckersalzundpfeffer/gridsome/commit/e42ca05623c44ce58283e15c9dde44232659ea33))
* **build:** create new Vue instance before each route ([424e678](https://github.com/zuckersalzundpfeffer/gridsome/commit/424e6783d22abb0571ab7581d683740fe9111e6f))
* **build:** dont prefetch data chunks ([46e80a4](https://github.com/zuckersalzundpfeffer/gridsome/commit/46e80a46f435d25a75467b5cd26aa8633b224529))
* **build:** ensure 404 route for /404 page ([70698e0](https://github.com/zuckersalzundpfeffer/gridsome/commit/70698e07dda1b44d510839cd1ca9241c20bf5534))
* **build:** handle some webpack errors properly ([#932](https://github.com/zuckersalzundpfeffer/gridsome/issues/932)) ([63bd6a3](https://github.com/zuckersalzundpfeffer/gridsome/commit/63bd6a3966db687fce74c5e13564d33451fe4748))
* **build:** keep leading slash for paged paths ([a2abccc](https://github.com/zuckersalzundpfeffer/gridsome/commit/a2abccc2dd303a2383b570aad4205c3dc8fe2e48))
* **build:** option for disabling hash in asset filenames ([#840](https://github.com/zuckersalzundpfeffer/gridsome/issues/840)) ([6765782](https://github.com/zuckersalzundpfeffer/gridsome/commit/6765782723ae1646a96903eebc15f045df062692))
* **build:** output paths for html and data ([d167e8e](https://github.com/zuckersalzundpfeffer/gridsome/commit/d167e8e1aa3ad5b1d19af383f6b0a8829742d6a0))
* **build:** show error stack form render failures ([5ba558e](https://github.com/zuckersalzundpfeffer/gridsome/commit/5ba558e852a2d6338be9535faff22999dc845653))
* **build:** throw error if something fails in main.js ([bb62605](https://github.com/zuckersalzundpfeffer/gridsome/commit/bb62605180bcf3ab4d0533833825329bc8d2437c))
* **build:** use correct manifest path ([7a204be](https://github.com/zuckersalzundpfeffer/gridsome/commit/7a204be8046b6439ba8501c5133fbcf09adbded3))
* **build:** validate page-query during build ([5fff97a](https://github.com/zuckersalzundpfeffer/gridsome/commit/5fff97a7b97b9cfa88367a921f217b46a136206c))
* **cli:** show stack when failing ([7507051](https://github.com/zuckersalzundpfeffer/gridsome/commit/7507051496160fabe9668f6c4b48d17bb31e91c7))
* **cli:** stop if not in a gridsome dir ([8c29072](https://github.com/zuckersalzundpfeffer/gridsome/commit/8c29072628523bdce6c3699c9dffecfc609245dc))
* **config:** customizing host and port ([bc44a64](https://github.com/zuckersalzundpfeffer/gridsome/commit/bc44a6408c4735163aece9515fcd82732600c0a2))
* **config:** skip undefined plugins ([3dc6b0f](https://github.com/zuckersalzundpfeffer/gridsome/commit/3dc6b0f74ddf20aacb774056d7c2e66e05a72209))
* **config:** use host and port from project config ([7936aa7](https://github.com/zuckersalzundpfeffer/gridsome/commit/7936aa772704e0b376f95a9b66e5f5763a104710))
* **critical:** use htmlOutput ([c2c9670](https://github.com/zuckersalzundpfeffer/gridsome/commit/c2c9670f7d668ced59cb2944fe801413f90b346c))
* **data:** strip trailing slash before import ([35fc653](https://github.com/zuckersalzundpfeffer/gridsome/commit/35fc6537ddc473edaa5f5d0cd49805328b481f18))
* **develop:** audio/video playback issues in Chrome ([#1220](https://github.com/zuckersalzundpfeffer/gridsome/issues/1220)) ([3a3c235](https://github.com/zuckersalzundpfeffer/gridsome/commit/3a3c235331449011a05117667215b71f71b2416d))
* **develop:** exclude dev middleware for playground route ([cff46b9](https://github.com/zuckersalzundpfeffer/gridsome/commit/cff46b907ebc286092be51d82774244353b1fcd6))
* **develop:** fallback to url when no key param is set ([809aaf8](https://github.com/zuckersalzundpfeffer/gridsome/commit/809aaf8a8b40d07ef89c34c32bfe783e33b61f43))
* **g-image:** always crop by given dimensions ([#759](https://github.com/zuckersalzundpfeffer/gridsome/issues/759)) ([97ca9db](https://github.com/zuckersalzundpfeffer/gridsome/commit/97ca9db66c0ccaf5a0de6cfba08d5d5d5b6ee20b))
* **g-image:** behave properly inside v-for ([#185](https://github.com/zuckersalzundpfeffer/gridsome/issues/185)) ([e3c2aba](https://github.com/zuckersalzundpfeffer/gridsome/commit/e3c2abab540294d19ba4aff01b2bd282d12cd15d))
* **g-image:** bind custom classes to object ([#151](https://github.com/zuckersalzundpfeffer/gridsome/issues/151)) ([10150ca](https://github.com/zuckersalzundpfeffer/gridsome/commit/10150caf998d1a7c75e3bb7b46b255ba66db4ae4))
* **g-image:** include wanted width in srcset ([#797](https://github.com/zuckersalzundpfeffer/gridsome/issues/797)) ([26dc27b](https://github.com/zuckersalzundpfeffer/gridsome/commit/26dc27bc8ade9b1d99c10910a74e21e1b18d1951))
* **g-image:** observe images in v-html ([#158](https://github.com/zuckersalzundpfeffer/gridsome/issues/158)) ([07821da](https://github.com/zuckersalzundpfeffer/gridsome/commit/07821dac69f03f41102b9c874289167fb249c0d4))
* **g-image:** option for setting default blur ([#760](https://github.com/zuckersalzundpfeffer/gridsome/issues/760)) ([71421f3](https://github.com/zuckersalzundpfeffer/gridsome/commit/71421f3ce114796725c591a19b503d2ac0a940c8))
* **g-image:** pass custom blur to asset queue ([1f9ce9a](https://github.com/zuckersalzundpfeffer/gridsome/commit/1f9ce9a5ba1070d7c22655e2fb3e816eb3539e86))
* **g-image:** resize correctly when reusing image ([#797](https://github.com/zuckersalzundpfeffer/gridsome/issues/797)) ([8c2d834](https://github.com/zuckersalzundpfeffer/gridsome/commit/8c2d834ddc1b4334eda3ff92c8b383587c37df5c))
* **g-image:** rotate based on exif orientation ([#1178](https://github.com/zuckersalzundpfeffer/gridsome/issues/1178)) ([9e6e118](https://github.com/zuckersalzundpfeffer/gridsome/commit/9e6e1186ea3f06913a8843062dc86b0969b34d85))
* **g-image:** run onload event once ([ca6f015](https://github.com/zuckersalzundpfeffer/gridsome/commit/ca6f01587aa0caf1b72017339dda80a38eb0f8a8)), closes [#93](https://github.com/zuckersalzundpfeffer/gridsome/issues/93)
* **g-image:** set blank src if sets is empty ([#824](https://github.com/zuckersalzundpfeffer/gridsome/issues/824)) ([8ab30fc](https://github.com/zuckersalzundpfeffer/gridsome/commit/8ab30fcdd94599357df884f44f462750b4ceace4))
* **g-link:** customizable active classes ([#65](https://github.com/zuckersalzundpfeffer/gridsome/issues/65)) ([0ee5273](https://github.com/zuckersalzundpfeffer/gridsome/commit/0ee527323cc9375505838f73674bd94ed790dda8))
* **g-link:** don't use router-link for mailto and tel links ([#755](https://github.com/zuckersalzundpfeffer/gridsome/issues/755)) ([d1b5779](https://github.com/zuckersalzundpfeffer/gridsome/commit/d1b57795f5ae75744b91fc60eed97cbd25531c2f))
* **graphql:** add exists filter query operator ([4777d0c](https://github.com/zuckersalzundpfeffer/gridsome/commit/4777d0ccd9b04201d63bc17bda520b622df4b304))
* **graphql:** allow GET request with query param ([#1127](https://github.com/zuckersalzundpfeffer/gridsome/issues/1127)) ([5a28064](https://github.com/zuckersalzundpfeffer/gridsome/commit/5a280646a368dd8b29ffa648405b6953451aa81a))
* **graphql:** apply extensions once per usage ([91f346e](https://github.com/zuckersalzundpfeffer/gridsome/commit/91f346ea21fe2c31681e71692180b658601275a2))
* **graphql:** calculate pagination in dev mode ([#1198](https://github.com/zuckersalzundpfeffer/gridsome/issues/1198)) ([39e9381](https://github.com/zuckersalzundpfeffer/gridsome/commit/39e9381e764a634dd6af7e17fc085e66f7f1a674))
* **graphql:** convert field to union if multiple typeNames ([8bf2931](https://github.com/zuckersalzundpfeffer/gridsome/commit/8bf29311cc9ce84383a06988cad10dc6cbd23615))
* **graphql:** createEnumType schema method ([#814](https://github.com/zuckersalzundpfeffer/gridsome/issues/814)) ([b09b116](https://github.com/zuckersalzundpfeffer/gridsome/commit/b09b1164dcda39159dbb0bbc35269f72755ce90b))
* **graphql:** do not send page param in path ([61cdf9c](https://github.com/zuckersalzundpfeffer/gridsome/commit/61cdf9cac20d532663cfc187b43bb720074dce4f))
* **graphql:** don’t convert URLs or filenames to object ([be08c52](https://github.com/zuckersalzundpfeffer/gridsome/commit/be08c524221725c815148a25fdb9ab03f7a4c30f))
* **graphql:** dont run empty page query ([9cc7176](https://github.com/zuckersalzundpfeffer/gridsome/commit/9cc7176454540dc2549026352bd16d2a78adcfd2))
* **graphql:** exclude undefined variables in page-query ([f753a47](https://github.com/zuckersalzundpfeffer/gridsome/commit/f753a47f247828538dbb803a2b28bddc230e194c))
* **graphql:** filter collection by reference id ([#745](https://github.com/zuckersalzundpfeffer/gridsome/issues/745)) ([cbb009a](https://github.com/zuckersalzundpfeffer/gridsome/commit/cbb009a0140fcd61d366ef5986afb8e6167eb197))
* **graphql:** fix deprecated references api ([cb6f245](https://github.com/zuckersalzundpfeffer/gridsome/commit/cb6f24565ca7c9ea2285edf5bd78f39fd9582367))
* **graphql:** handle date types correctly ([53f963d](https://github.com/zuckersalzundpfeffer/gridsome/commit/53f963d0ca3a2655eb5d274fb765767ef8afec70))
* **graphql:** hot reload page-query changes ([017aa95](https://github.com/zuckersalzundpfeffer/gridsome/commit/017aa95dfae120df2831d071424feee80bcf31ae))
* **graphql:** improved error handling ([0dad580](https://github.com/zuckersalzundpfeffer/gridsome/commit/0dad5804dd5cf2f45b144db967e093873a294ae7))
* **graphql:** keep extensions for third party fields ([b0e3cfb](https://github.com/zuckersalzundpfeffer/gridsome/commit/b0e3cfbe7afe893da3eeac579f578495cf4ae466))
* **graphql:** merge all entries in arrays ([#184](https://github.com/zuckersalzundpfeffer/gridsome/issues/184)) ([80952d6](https://github.com/zuckersalzundpfeffer/gridsome/commit/80952d6d1f9b2962f8a8ccdbe97611ab714b9fb8))
* **graphql:** merge ref fields correctly ([#128](https://github.com/zuckersalzundpfeffer/gridsome/issues/128), [#129](https://github.com/zuckersalzundpfeffer/gridsome/issues/129)) ([ffb29ee](https://github.com/zuckersalzundpfeffer/gridsome/commit/ffb29eee33477b68d0b14d9e42d445c0e807ccb0))
* **graphql:** pass operationName argument to graphql method ([#1047](https://github.com/zuckersalzundpfeffer/gridsome/issues/1047)) ([a5c2d3b](https://github.com/zuckersalzundpfeffer/gridsome/commit/a5c2d3b1b812f8f80f3f96b7fa30d30e1ed64035))
* **graphql:** prevent overriding built-in directives ([878e947](https://github.com/zuckersalzundpfeffer/gridsome/commit/878e9477e01a7ec003fdda24a8f35d2eaa4707a7))
* **graphql:** return null for missing images ([39c5a92](https://github.com/zuckersalzundpfeffer/gridsome/commit/39c5a928ab49dbe4af4e8f7f8fdf25fc4ca1b8df))
* **graphql:** return null for missing references ([8d920fc](https://github.com/zuckersalzundpfeffer/gridsome/commit/8d920fc8a8a02f69134088465c6cad864bb92c1e))
* **graphql:** sort by custom field value ([cfcefaf](https://github.com/zuckersalzundpfeffer/gridsome/commit/cfcefaf355cc8dfa3b1478b07fac95883609b4df))
* **graphql:** use correct type for store.addReference() ([5b71d04](https://github.com/zuckersalzundpfeffer/gridsome/commit/5b71d04ddd23eaf0a5ba40fc56a93db77999cf87))
* **graphql:** warn when missing reference ([a6f7857](https://github.com/zuckersalzundpfeffer/gridsome/commit/a6f78579d944e8fdcfdea34f73b69f068ed037fd))
* **image:** don’t re-render when parent updates ([#93](https://github.com/zuckersalzundpfeffer/gridsome/issues/93)) ([c813d70](https://github.com/zuckersalzundpfeffer/gridsome/commit/c813d702e37f7716f4ecbd9ecfb2c5546b3d2543))
* **image:** dont add lazy class when no srcset ([f3e4257](https://github.com/zuckersalzundpfeffer/gridsome/commit/f3e4257b9a3b9493a4de8970e14253240fcda1d5))
* **image:** hot reload after changes ([b4d83e7](https://github.com/zuckersalzundpfeffer/gridsome/commit/b4d83e738078ea1970b84275356e51de544c6a0a)), closes [#3](https://github.com/zuckersalzundpfeffer/gridsome/issues/3)
* **image:** init observer in client only ([4c4dad9](https://github.com/zuckersalzundpfeffer/gridsome/commit/4c4dad932d2d1478b1c506b6c27871a6c5acf071))
* **image:** re-observe after hot-reload ([dfeeb90](https://github.com/zuckersalzundpfeffer/gridsome/commit/dfeeb90022bfefb0df7dfe62228e45d8bb4e0505))
* **renderer:** protect agains failing ssr vue-meta ([c9ad300](https://github.com/zuckersalzundpfeffer/gridsome/commit/c9ad3009a05acd9dddd43e28d3f6a3d7a8968e89))
* **webpack:** alias to gridsome app ([3891e87](https://github.com/zuckersalzundpfeffer/gridsome/commit/3891e87667ec97eab03d211ca74ef5d3d6cdbb43))
* **webpack:** page data importer in separate chunk ([34b8244](https://github.com/zuckersalzundpfeffer/gridsome/commit/34b8244d600a1c2b19f53384760cbc3c3a2ad4f0))
* show system info at startup ([de9793e](https://github.com/zuckersalzundpfeffer/gridsome/commit/de9793ee036881b0528dab3703271597b6940a40))
* stop worker if any errors ([9890a26](https://github.com/zuckersalzundpfeffer/gridsome/commit/9890a2600dff479affa86e1a56ea648e6580c7af))
* **image:** resize by width attribute + test ([7ac63a7](https://github.com/zuckersalzundpfeffer/gridsome/commit/7ac63a7b97500760e3b4589df4786114f42ed09e))
* **pages:** add missing find* API methods ([#927](https://github.com/zuckersalzundpfeffer/gridsome/issues/927)) ([bfc1104](https://github.com/zuckersalzundpfeffer/gridsome/commit/bfc1104b332c62f7c948c2e5bc14541df44099e5))
* **pages:** dynamic route params in directories on windows ([#1359](https://github.com/zuckersalzundpfeffer/gridsome/issues/1359)) ([3d36051](https://github.com/zuckersalzundpfeffer/gridsome/commit/3d360512ed51045df876df426c450beb891d29e9))
* **pages:** return if no page is found in `removePage()` ([#926](https://github.com/zuckersalzundpfeffer/gridsome/issues/926)) ([9d8aef7](https://github.com/zuckersalzundpfeffer/gridsome/commit/9d8aef77b5eae5be7776af93a72d1b336a58e8d1))
* **pathPrefix:** don’t create subfolder ([#85](https://github.com/zuckersalzundpfeffer/gridsome/issues/85)) ([96bfbed](https://github.com/zuckersalzundpfeffer/gridsome/commit/96bfbed35615ca5b5aca8e50485b601d6082ed1f))
* **route:** allow node props as route params ([1658fde](https://github.com/zuckersalzundpfeffer/gridsome/commit/1658fde7a33260581b85cef660cface7af827e6c))
* **router:** add leading slash to routes ([4024ace](https://github.com/zuckersalzundpfeffer/gridsome/commit/4024ace18fc5094b015beaf8ced6e9f952bbd383))
* **router:** fetch data for paths with hash ([19a0c78](https://github.com/zuckersalzundpfeffer/gridsome/commit/19a0c78dfff0e11321132380b1965d64583366f1))
* **store:** allow regex wildcard route param ([f283526](https://github.com/zuckersalzundpfeffer/gridsome/commit/f283526bbe83730102bb950d9f60bd5ab5bc4e23))
* **store:** dont process null value as an object ([a05bb5a](https://github.com/zuckersalzundpfeffer/gridsome/commit/a05bb5a3da08b1ce42a1354dfb39c618332a86db))
* **store:** ensure reference node id’s are strings ([98a3edf](https://github.com/zuckersalzundpfeffer/gridsome/commit/98a3edfa8aeb516434a4d07e3adacf71651582ce))
* **store:** include GraphQLJSON type in addSchemaField ([73e332c](https://github.com/zuckersalzundpfeffer/gridsome/commit/73e332cb625e533552fbd3a3b4e0628e7f02aed0))
* **store:** pass resolveAbsolutePaths correctly ([6164464](https://github.com/zuckersalzundpfeffer/gridsome/commit/6164464319c29ec11048e04c227025bc8e3dca09))
* **store:** require unique paths for templates only ([91225f1](https://github.com/zuckersalzundpfeffer/gridsome/commit/91225f1616dbdb349b6b2a1b45e6357aa508332e))
* **store:** resolve absolute paths in fields correctly ([#792](https://github.com/zuckersalzundpfeffer/gridsome/issues/792)) ([beb9084](https://github.com/zuckersalzundpfeffer/gridsome/commit/beb9084a686a52d239bb6b438ea86ca2c311d184))
* **store:** update node content and excerpt ([637e0e4](https://github.com/zuckersalzundpfeffer/gridsome/commit/637e0e42f1baf003e4cd65a85c8fdf7686ca198f))
* **store:** warn and skip when duplicate path detected ([215b3e9](https://github.com/zuckersalzundpfeffer/gridsome/commit/215b3e912c0dadadbd1accd8deaf73a22c3703d7))
* **webpack:** cache graphql loader results ([6e794ab](https://github.com/zuckersalzundpfeffer/gridsome/commit/6e794abf4161393fd855d7f4756cf2362f04133f))
* **webpack:** combine all css in one file ([#230](https://github.com/zuckersalzundpfeffer/gridsome/issues/230)) ([952148d](https://github.com/zuckersalzundpfeffer/gridsome/commit/952148db357c2ca80db5977a90f6ffadd588601f))
* **webpack:** don’t cache static-query ([#160](https://github.com/zuckersalzundpfeffer/gridsome/issues/160)) ([0352f99](https://github.com/zuckersalzundpfeffer/gridsome/commit/0352f995e67927c308bb56c08a5c925ddd8fa1c1))
* **webpack:** don’t fail if g-image or g-link has no attrs ([5267a78](https://github.com/zuckersalzundpfeffer/gridsome/commit/5267a78586b39dc911dae744436c106a62b45b31))
* **webpack:** externalize included dependencies only ([adbff52](https://github.com/zuckersalzundpfeffer/gridsome/commit/adbff52eaa0f92d00068f00b329a2334c1119433))
* **webpack:** fix config for IE support ([e403f4c](https://github.com/zuckersalzundpfeffer/gridsome/commit/e403f4c6c5e777ba4194d6eaf31e9c0dd6d16846))
* **webpack:** ignore missing default export in main.js ([a81ed0e](https://github.com/zuckersalzundpfeffer/gridsome/commit/a81ed0e99a6cf78dffb5a42e5cfc0293b76f069e))
* **webpack:** inject promise polyfill ([#480](https://github.com/zuckersalzundpfeffer/gridsome/issues/480)) ([ae29fea](https://github.com/zuckersalzundpfeffer/gridsome/commit/ae29fea3ab9472731297df32720fed0d14c033fe))
* **webpack:** remove duplicate style links (163) ([5ce0106](https://github.com/zuckersalzundpfeffer/gridsome/commit/5ce01068b3a69e88e27b508f3ea1f642c237a1db))
* **webpack:** support webp images ([#227](https://github.com/zuckersalzundpfeffer/gridsome/issues/227)) ([72123f7](https://github.com/zuckersalzundpfeffer/gridsome/commit/72123f72cae11fa8f4ed62a561e8037c742ae53e))
* **webpack:** transpile custom blocks ([#130](https://github.com/zuckersalzundpfeffer/gridsome/issues/130)) ([c81fee4](https://github.com/zuckersalzundpfeffer/gridsome/commit/c81fee4d3e41a855ebb0b3823aef6f7eaf386f2f))
* **webpack:** use devServer.watchOptions for dev middleware ([#865](https://github.com/zuckersalzundpfeffer/gridsome/issues/865)) ([0bedcdb](https://github.com/zuckersalzundpfeffer/gridsome/commit/0bedcdbf7abd02f340bd94b3a905325eda3c996f))
* **worker:** resize images correctly ([61d2e74](https://github.com/zuckersalzundpfeffer/gridsome/commit/61d2e74af3519228a1882b4bd115b9dfa70123d0))
* **worker:** set jpeg quality ([31f8929](https://github.com/zuckersalzundpfeffer/gridsome/commit/31f892947034779f319b1bba4112b1b87dde2651))
* webpack progress in tty only ([bab7e8a](https://github.com/zuckersalzundpfeffer/gridsome/commit/bab7e8a5523f15c716749ba56f9dc4ff6562409e))


### Code Refactoring

* **app:** move link catcher to directive ([4b4f262](https://github.com/zuckersalzundpfeffer/gridsome/commit/4b4f262e9552a81951805b15b4fd57d0f8833b95))


### Features

* `useMetaInfo` ([bc04d02](https://github.com/zuckersalzundpfeffer/gridsome/commit/bc04d02c7c46ee28b728724c49f7992fffa2224c))
* `useRouter` and `useRoute` ([82bc7e3](https://github.com/zuckersalzundpfeffer/gridsome/commit/82bc7e31980b8574a6d3eb092d43449c4f545302))
* `useStaticQuery` ([3cdd271](https://github.com/zuckersalzundpfeffer/gridsome/commit/3cdd27154d350130cc590cede71e18440b3ddced))
* load `.env.local` and `.env.*.local` ([#1583](https://github.com/zuckersalzundpfeffer/gridsome/issues/1583)) ([9920cc8](https://github.com/zuckersalzundpfeffer/gridsome/commit/9920cc8ba4f81b431e1a3bb7bd1aa47f979b0d36))
* upgrade to vue 2.7 ([6528b8b](https://github.com/zuckersalzundpfeffer/gridsome/commit/6528b8b4a139fc3e135bce03638c50c2ff6b5ce6))
* **api:** helper method for resolving paths ([db3546f](https://github.com/zuckersalzundpfeffer/gridsome/commit/db3546f7782ca1dab8350f08720f40cb8d34e1ad))
* **app:** browser field in package json ([3e87581](https://github.com/zuckersalzundpfeffer/gridsome/commit/3e87581d5accddacc4dc4013619c89fbada7ff11))
* **app:** gen favicon and touchicon sizes [#4](https://github.com/zuckersalzundpfeffer/gridsome/issues/4) ([3448301](https://github.com/zuckersalzundpfeffer/gridsome/commit/3448301f6d07c3a0896bcdea8aaf1e0a6360f521))
* **app:** method for fetching page data ([2a624ab](https://github.com/zuckersalzundpfeffer/gridsome/commit/2a624ab49bd44906db94a22af5af035e6f2530d5))
* **app:** override active link classes for Pager ([#143](https://github.com/zuckersalzundpfeffer/gridsome/issues/143)) ([6a5159d](https://github.com/zuckersalzundpfeffer/gridsome/commit/6a5159d93dfcbe19c51ba9404fb98a63899bb30c))
* **app:** override App.vue component ([#635](https://github.com/zuckersalzundpfeffer/gridsome/issues/635)) ([fc9606d](https://github.com/zuckersalzundpfeffer/gridsome/commit/fc9606dcc55155ad0a97ea332e82e08f61ba3339))
* **app:** override default index.html template ([#162](https://github.com/zuckersalzundpfeffer/gridsome/issues/162)) ([4cdd326](https://github.com/zuckersalzundpfeffer/gridsome/commit/4cdd3268579e0ecd818af2c535f7210af10383b5))
* **app:** permalinks config ([#574](https://github.com/zuckersalzundpfeffer/gridsome/issues/574)) ([e89d80a](https://github.com/zuckersalzundpfeffer/gridsome/commit/e89d80a000f1e25c812d29ad6657a08efa49c709)), closes [#121](https://github.com/zuckersalzundpfeffer/gridsome/issues/121)
* **app:** send isServer and isClient to main.js ([fe01c8e](https://github.com/zuckersalzundpfeffer/gridsome/commit/fe01c8e46337a986b42c98cbb676b8985ddfa01a))
* **app:** siteDescription as description meta tag ([#70](https://github.com/zuckersalzundpfeffer/gridsome/issues/70)) ([6fa118c](https://github.com/zuckersalzundpfeffer/gridsome/commit/6fa118c7d74ebffd9976308a94880a423b419833))
* **app:** upgrade to Vue 2.6 ([f1ab4e1](https://github.com/zuckersalzundpfeffer/gridsome/commit/f1ab4e126f0610fc38b9a53cc40c49b8f064cd02))
* **build:** generate 404.html file ([#75](https://github.com/zuckersalzundpfeffer/gridsome/issues/75)) ([59988e5](https://github.com/zuckersalzundpfeffer/gridsome/commit/59988e587c7abf46031721ba80c6c0c3a0730fd1))
* **build:** image processing cache ([#57](https://github.com/zuckersalzundpfeffer/gridsome/issues/57)) ([0a9e449](https://github.com/zuckersalzundpfeffer/gridsome/commit/0a9e449a96a9d803f5887ce6425eb01af900563b))
* **cli:** gridsome serve ([a91c7fc](https://github.com/zuckersalzundpfeffer/gridsome/commit/a91c7fcb1ec6a53bd4107723ec09d6fda77aa82c))
* **config:** `emptyOutputDir` config ([aea2af0](https://github.com/zuckersalzundpfeffer/gridsome/commit/aea2af0eaa645453d22e545f687270085248e298))
* **contentful:** use new plugin api ([eaf6092](https://github.com/zuckersalzundpfeffer/gridsome/commit/eaf609269b3f8b9754e608e583c3b292c350a660))
* **develop:** webpack-dev-server for local dev ([#1470](https://github.com/zuckersalzundpfeffer/gridsome/issues/1470)) ([27011c6](https://github.com/zuckersalzundpfeffer/gridsome/commit/27011c61e1c4c95b2ecd5d5a246aebfc526983e3))
* **env:** rename to isClient and isServer ([90880c6](https://github.com/zuckersalzundpfeffer/gridsome/commit/90880c6c98160b21d6a234a30d8d305aa61b7300))
* **g-link:** rel noopener for external links ([#104](https://github.com/zuckersalzundpfeffer/gridsome/issues/104)) ([9f11efb](https://github.com/zuckersalzundpfeffer/gridsome/commit/9f11efb46d36781ff54ed192856c2e9db56479c1))
* **graphql:** `position` argument for images ([#1471](https://github.com/zuckersalzundpfeffer/gridsome/issues/1471)) ([61dc649](https://github.com/zuckersalzundpfeffer/gridsome/commit/61dc64963449cc009b63c70f18961e536a4c00e0))
* typescript support ([#1467](https://github.com/zuckersalzundpfeffer/gridsome/issues/1467)) ([b14defb](https://github.com/zuckersalzundpfeffer/gridsome/commit/b14defbe1afdc87f579d34729cd5496fbfd277d8))
* webpack 5 ([#1523](https://github.com/zuckersalzundpfeffer/gridsome/issues/1523)) ([93344f3](https://github.com/zuckersalzundpfeffer/gridsome/commit/93344f31416f04cfd54e0d987b24162a5218ba60))
* **app:** range option for Pager component ([#344](https://github.com/zuckersalzundpfeffer/gridsome/issues/344)) ([77dab89](https://github.com/zuckersalzundpfeffer/gridsome/commit/77dab89addb3dc6e823ca4de6e7d9813b9c779c9))
* **app:** upgrade to vue-meta v2.0 ([eac20ef](https://github.com/zuckersalzundpfeffer/gridsome/commit/eac20effa0146cb2ca1d38fae77e35191f9a4b7c))
* **develop:** configureServer hook ([029e431](https://github.com/zuckersalzundpfeffer/gridsome/commit/029e4317dac7dbf23d3281cbabcb83384fcb29bc))
* **develop:** https option for develop command ([#961](https://github.com/zuckersalzundpfeffer/gridsome/issues/961)) ([65ef93b](https://github.com/zuckersalzundpfeffer/gridsome/commit/65ef93b54be21f44f3133e05a79f995275e701cd))
* **develop:** run site on local network ([a1d91f4](https://github.com/zuckersalzundpfeffer/gridsome/commit/a1d91f4a96bee59df2fb8f37bbb8366d5c6bc36e))
* **g-image:** generate placeholder with blurhash ([97006f6](https://github.com/zuckersalzundpfeffer/gridsome/commit/97006f60751fb2d9fa7b7d6070695cc1c275324f))
* **g-image:** trace and dominant placeholder types ([57809a7](https://github.com/zuckersalzundpfeffer/gridsome/commit/57809a7534d47785d8802c8099cc2853c55227a5))
* **graphql:** add custom metadata ([#54](https://github.com/zuckersalzundpfeffer/gridsome/issues/54)) ([7b35378](https://github.com/zuckersalzundpfeffer/gridsome/commit/7b35378614e0dae644cc2b67296ac38da85e5417))
* **graphql:** add metaData from config ([#225](https://github.com/zuckersalzundpfeffer/gridsome/issues/225)) ([b90d490](https://github.com/zuckersalzundpfeffer/gridsome/commit/b90d4904edd4ef47683849b987f41c3df3c6b5b9))
* **graphql:** advanced sort argument ([#247](https://github.com/zuckersalzundpfeffer/gridsome/issues/247)) ([9b0907e](https://github.com/zuckersalzundpfeffer/gridsome/commit/9b0907eb2f18588a1c5c0866cf1211b6ae28f728))
* **graphql:** belongsTo field for listing references ([#119](https://github.com/zuckersalzundpfeffer/gridsome/issues/119)) ([2ef275f](https://github.com/zuckersalzundpfeffer/gridsome/commit/2ef275f9a925542fc5f5675a328b1925a24603fe))
* **graphql:** createSchema api [wip] ([c5d6d6b](https://github.com/zuckersalzundpfeffer/gridsome/commit/c5d6d6bc3411335d4b330f9fd5c33f63a0a3be6c))
* **graphql:** current node as query variables ([#77](https://github.com/zuckersalzundpfeffer/gridsome/issues/77)) ([1beece4](https://github.com/zuckersalzundpfeffer/gridsome/commit/1beece4064be50b431a76499ad11a4fd064cd60c))
* **graphql:** customize the schema ([#509](https://github.com/zuckersalzundpfeffer/gridsome/issues/509)) ([c4684b2](https://github.com/zuckersalzundpfeffer/gridsome/commit/c4684b2078d899bf45341fe2a9f4fed92cb41064))
* **graphql:** date field type ([d9f8335](https://github.com/zuckersalzundpfeffer/gridsome/commit/d9f83354140b02ef094db19e79e57e93280c10fa))
* **graphql:** file type ([05f6c98](https://github.com/zuckersalzundpfeffer/gridsome/commit/05f6c9841882ab3ceac2c568e9b1e89ce3130b3a))
* **graphql:** image arguments ([e38b243](https://github.com/zuckersalzundpfeffer/gridsome/commit/e38b243f5156cceb3a2d867862aee95721e0e23f))
* **graphql:** image type ([#25](https://github.com/zuckersalzundpfeffer/gridsome/issues/25)) ([316c91d](https://github.com/zuckersalzundpfeffer/gridsome/commit/316c91d3308691137dfac3a1308cfc09014218e4))
* **graphql:** limit argument for content types and belongsTo ([7756620](https://github.com/zuckersalzundpfeffer/gridsome/commit/775662056adafc4b84f91d5cab567c891bd7091c))
* **graphql:** merge third party schemas ([1f33169](https://github.com/zuckersalzundpfeffer/gridsome/commit/1f331691102fa4fe356b9e660b95077262792889))
* **graphql:** reference with multiple node types ([#50](https://github.com/zuckersalzundpfeffer/gridsome/issues/50)) ([185297f](https://github.com/zuckersalzundpfeffer/gridsome/commit/185297fc7a82740de51ef8ecf54d5e63ae8b143f))
* **graphql:** rename graphql block to page-query ([8bf5e1a](https://github.com/zuckersalzundpfeffer/gridsome/commit/8bf5e1a5eea1b5ec627a726c9c45d82037e85f84))
* **graphql:** upgrade to graphql v15 ([58292d8](https://github.com/zuckersalzundpfeffer/gridsome/commit/58292d82ed45eeb79abdbe31c7beac750cb31528))
* **gridsome:** add pnp support ([cd8f298](https://github.com/zuckersalzundpfeffer/gridsome/commit/cd8f298af8527e20e7443e2ba5dc3ddf85a25d7d))
* **image:** crop by width and height ([#78](https://github.com/zuckersalzundpfeffer/gridsome/issues/78)) ([001aa0b](https://github.com/zuckersalzundpfeffer/gridsome/commit/001aa0b9d82bb96dc5bd8dba84af3b80640bef1e))
* **page-query:** include graphql with src attribute ([#806](https://github.com/zuckersalzundpfeffer/gridsome/issues/806)) ([6dd86f0](https://github.com/zuckersalzundpfeffer/gridsome/commit/6dd86f0369d2668d97f86cd1305cf934c5f002af))
* make core-js imports absolute ([7e00df1](https://github.com/zuckersalzundpfeffer/gridsome/commit/7e00df1212882b5ee682e0cb5ffaaddb815f9602))
* **graphql:** filter argument ([#84](https://github.com/zuckersalzundpfeffer/gridsome/issues/84)) ([692f6cb](https://github.com/zuckersalzundpfeffer/gridsome/commit/692f6cb632df384e24effaf1be9898f0c199d9f1))
* **pages:** create managed pages ([a9042b0](https://github.com/zuckersalzundpfeffer/gridsome/commit/a9042b0c1c2286ff1caa7ea9a821bdd29a6b7587))
* **pages:** dynamic routing ([#570](https://github.com/zuckersalzundpfeffer/gridsome/issues/570)) ([0061019](https://github.com/zuckersalzundpfeffer/gridsome/commit/00610191227eaf3172d6db20a55efe5b897f50ba))
* **pages:** pages api ([#309](https://github.com/zuckersalzundpfeffer/gridsome/issues/309)) ([5c6a45c](https://github.com/zuckersalzundpfeffer/gridsome/commit/5c6a45c9fa21e9b0c05e0f3563f999ed77b4728f))
* **pages:** trailing slash for page paths ([3116ed5](https://github.com/zuckersalzundpfeffer/gridsome/commit/3116ed582f1084e0a3ebcf062ad02ce2e938b88b))
* **router:** custom fields as params ([#53](https://github.com/zuckersalzundpfeffer/gridsome/issues/53)) ([f53f67f](https://github.com/zuckersalzundpfeffer/gridsome/commit/f53f67fa29576a633a3ae5da16f612061d429a60))
* **router:** deep node fields as route params ([#115](https://github.com/zuckersalzundpfeffer/gridsome/issues/115)) ([2d2ec44](https://github.com/zuckersalzundpfeffer/gridsome/commit/2d2ec44da67bab024f5c187e8ac3b7baf6d26821))
* **sass-loader:** support for sass-loader@8 and above ([#1108](https://github.com/zuckersalzundpfeffer/gridsome/issues/1108)) ([34e980f](https://github.com/zuckersalzundpfeffer/gridsome/commit/34e980f16a486cb0dfd40008a33fb2bc48cbc6c9))
* **store:** helper for creating refs in sub fields ([b9d7add](https://github.com/zuckersalzundpfeffer/gridsome/commit/b9d7addf5b9d1c879d2adaa943721433b08c95c5))
* **store:** methods for retrieving nodes ([7b442a2](https://github.com/zuckersalzundpfeffer/gridsome/commit/7b442a20882d5434dc1a51a8b727f69812163e3c))
* **templates:** centralized templates config ([#571](https://github.com/zuckersalzundpfeffer/gridsome/issues/571)) ([04fa6d1](https://github.com/zuckersalzundpfeffer/gridsome/commit/04fa6d175652ffe7e7d2898c7b5fa33fe9803eb2))
* **webpack:** add custom css loader options ([#46](https://github.com/zuckersalzundpfeffer/gridsome/issues/46)) ([cf7a505](https://github.com/zuckersalzundpfeffer/gridsome/commit/cf7a505e37162ba86f0b8e7889bd6194c0adeae3))
* **webpack:** configure webpack ([#342](https://github.com/zuckersalzundpfeffer/gridsome/issues/342)) ([ac9fc5a](https://github.com/zuckersalzundpfeffer/gridsome/commit/ac9fc5adbb782166deb302b80bba7117302dc21a))
* **webpack:** enviroment variables and support for dotenv files ([#123](https://github.com/zuckersalzundpfeffer/gridsome/issues/123)) ([c236d8b](https://github.com/zuckersalzundpfeffer/gridsome/commit/c236d8b1fa7fd74096562d3ddd816a43baedada7))
* **webpack:** runtimeCompiler config ([cdb676f](https://github.com/zuckersalzundpfeffer/gridsome/commit/cdb676f4f276b054118e6094d1dec2c3bf4d6d7b))
* **webpack:** transpileDependencies config ([36e4932](https://github.com/zuckersalzundpfeffer/gridsome/commit/36e49326f6ca7517864057d31d45598ceb42c769))
* addReference and addSchemaField ([c159ee5](https://github.com/zuckersalzundpfeffer/gridsome/commit/c159ee5ca2395c0084644e043e5a2019ce2cc7a6))
* build hooks ([32774f0](https://github.com/zuckersalzundpfeffer/gridsome/commit/32774f0bbdc719843cd6331d2461d301987bfd8e))
* cleaner graphql schema ([#31](https://github.com/zuckersalzundpfeffer/gridsome/issues/31)) ([98420a2](https://github.com/zuckersalzundpfeffer/gridsome/commit/98420a22e1d99091b6e6068e535d70ad2c9adda1))
* client plugin api ([caa6a17](https://github.com/zuckersalzundpfeffer/gridsome/commit/caa6a17c7d5efc95a6465578b550ad0ab826411f))
* copy linked files ([7dd26f2](https://github.com/zuckersalzundpfeffer/gridsome/commit/7dd26f2c21770b5f2fee278729652362c87448af))
* dir for static files ([4185564](https://github.com/zuckersalzundpfeffer/gridsome/commit/418556428745f2893549d72148049ce0cb7f9445))
* GRIDSOME_MODE env variable ([561e72c](https://github.com/zuckersalzundpfeffer/gridsome/commit/561e72c0d7560a838fafebbe8da64d1c3f07d5bc))
* plugin api ([7a7889b](https://github.com/zuckersalzundpfeffer/gridsome/commit/7a7889b7501265cd7bd75091cabde91f1527ca5e))
* resolve file paths ([#26](https://github.com/zuckersalzundpfeffer/gridsome/issues/26)) ([a4baf68](https://github.com/zuckersalzundpfeffer/gridsome/commit/a4baf68c3c27cb3ed1d2a086d5166dcfb3476fb1))
* support local plugins ([#22](https://github.com/zuckersalzundpfeffer/gridsome/issues/22)) ([568207f](https://github.com/zuckersalzundpfeffer/gridsome/commit/568207fbc413c1b9bd4ff1a671e063ba540b5001))
* **image:** generate blured inline svg ([bd54dfe](https://github.com/zuckersalzundpfeffer/gridsome/commit/bd54dfe3aa46d272ba0d585cb6dc6a8ef55eff64))
* **store:** set content and excerpt on node ([43c4236](https://github.com/zuckersalzundpfeffer/gridsome/commit/43c42361c689f223e4eb4bdbb592b583f0c6cc55))
* store api ([15d1c97](https://github.com/zuckersalzundpfeffer/gridsome/commit/15d1c974199f1e02c450ad43e333274005e59b58))
* **webpack:** alias ~ to src dir ([81c1a5f](https://github.com/zuckersalzundpfeffer/gridsome/commit/81c1a5f5229fcc788960ce606d041fae86cfa3d7))
* **webpack:** use @vue/babel-preset-app ([e51e363](https://github.com/zuckersalzundpfeffer/gridsome/commit/e51e3630559075929f8191eb9f2cd362d86ce4ae))


### Performance Improvements

* stream images while processing them ([d6e34f4](https://github.com/zuckersalzundpfeffer/gridsome/commit/d6e34f4281657b4a4402de7d093aad02170fb420))
* **build:** improve page-query output performance ([#1190](https://github.com/zuckersalzundpfeffer/gridsome/issues/1190)) ([2d81133](https://github.com/zuckersalzundpfeffer/gridsome/commit/2d811337bb61627ebb51e90404fcb24425bffd1d))
* **build:** improve page-query runner ([e3a88be](https://github.com/zuckersalzundpfeffer/gridsome/commit/e3a88be673b58fd563c4528038e6dca77d5ec7fa))
* **build:** improve render queue performance ([25ae955](https://github.com/zuckersalzundpfeffer/gridsome/commit/25ae955e14b25bd56a52a74749d633c203ab97c6))
* **g-image:** get dimensions from sharp metadata ([4f8ed20](https://github.com/zuckersalzundpfeffer/gridsome/commit/4f8ed20c30608fe624f3e3dad87174f600b50e1d))
* **graphql:** improve belongsTo query performance ([bcdacce](https://github.com/zuckersalzundpfeffer/gridsome/commit/bcdacce15df46c5b5f5381fe2ec7df29a0721a37))
* **graphql:** improve path argument performance ([#1190](https://github.com/zuckersalzundpfeffer/gridsome/issues/1190)) ([8f15b4c](https://github.com/zuckersalzundpfeffer/gridsome/commit/8f15b4c01e650476c174b3e1c8b0f00ee66dd739))
* **pages:** improve pages api performance ([#548](https://github.com/zuckersalzundpfeffer/gridsome/issues/548)) ([9bc4ddb](https://github.com/zuckersalzundpfeffer/gridsome/commit/9bc4ddbed08c39502ef9b50d1156351e7e65c1ac))
* **store:** disable adaptive binary indices ([#1190](https://github.com/zuckersalzundpfeffer/gridsome/issues/1190)) ([83d7c67](https://github.com/zuckersalzundpfeffer/gridsome/commit/83d7c67daeb454e0b6c64dada25dc655b7f8baec))
* **store:** disable adaptive indices for node index ([#1190](https://github.com/zuckersalzundpfeffer/gridsome/issues/1190)) ([52f90e4](https://github.com/zuckersalzundpfeffer/gridsome/commit/52f90e4196971411b1559e601b38abf798c63198))
* **templates:** cache date while generating paths ([#1190](https://github.com/zuckersalzundpfeffer/gridsome/issues/1190)) ([c4f17a0](https://github.com/zuckersalzundpfeffer/gridsome/commit/c4f17a020491d1d7238e416a9911f543aac4b3e1))


### BREAKING CHANGES

* **app:** use `v-catch-links` to make internal links in custom HTML use the Vue router



## 0.0.2 (2018-09-16)


### Bug Fixes

* add local bin to core package ([0bab302](https://github.com/zuckersalzundpfeffer/gridsome/commit/0bab302bd20105a9a24b2fc3d0ff16a806cfaab8))



## 0.0.1 (2018-09-16)





# [0.8.0](https://github.com/gridsome/gridsome/compare/gridsome@0.7.23...gridsome@0.8.0) (2023-04-26)


### Bug Fixes

* **build:** don’t process existing images ([3fa9efb](https://github.com/gridsome/gridsome/commit/3fa9efb493fa5dcf7ac1e2eb3313374df90ed313))
* **develop:** use some webpack dev server options ([d009325](https://github.com/gridsome/gridsome/commit/d0093257d5c676c05eee26b9089982121f34bc5b))
* **develop:** yarn PnP in develop ([#1434](https://github.com/gridsome/gridsome/issues/1434)) ([c2a71f5](https://github.com/gridsome/gridsome/commit/c2a71f52962477f33988ed7700ee5ddb6b2acb40))
* **g-image:** add height attribute ([#1257](https://github.com/gridsome/gridsome/issues/1257)) ([bc8d3c4](https://github.com/gridsome/gridsome/commit/bc8d3c4e0ab911215c43c41176608ec9f30ece82))
* **g-image:** data uri w3c compliance ([#1438](https://github.com/gridsome/gridsome/issues/1438)) ([9330b63](https://github.com/gridsome/gridsome/commit/9330b6371cb7dfa0e1fe6c36ad9b8ba2318bbc27))
* **g-image:** fallback to dataUri if image fails to load ([#1430](https://github.com/gridsome/gridsome/issues/1430)) ([0b4a4b5](https://github.com/gridsome/gridsome/commit/0b4a4b5957062f9d71f814dcd2ee8d1c3b8d847a))
* **g-image:** height attribute in generated markup ([#1257](https://github.com/gridsome/gridsome/issues/1257)) ([71f4184](https://github.com/gridsome/gridsome/commit/71f41848a5fb53d180513118a662aeef6344e436))
* **g-image:** improve edges in blurred placeholders ([7a2080e](https://github.com/gridsome/gridsome/commit/7a2080ef39621d4e15f97fffa3442404549009ac))
* **g-image:** maintain blur placeholder aspect ratio ([7c81f8c](https://github.com/gridsome/gridsome/commit/7c81f8c0f96b14ed8da8645280af10ac519ec327))
* **g-image:** optional `srcset` and `sizes` ([#1574](https://github.com/gridsome/gridsome/issues/1574)) ([dbb55d7](https://github.com/gridsome/gridsome/commit/dbb55d7c4180ca34c16cb74259721797dc1e83eb))
* **graphql:** better error message for reserved type names ([#1388](https://github.com/gridsome/gridsome/issues/1388)) ([f9cfa4b](https://github.com/gridsome/gridsome/commit/f9cfa4b3a4c5156c55001320b8771504438df479))
* **graphql:** return last node if no arguments ([#541](https://github.com/gridsome/gridsome/issues/541)) ([865728a](https://github.com/gridsome/gridsome/commit/865728a1275e79030cd3b7efebe32eeecb923714))
* **gridsome:** add undeclared dependency vue-style-loader ([cbcede6](https://github.com/gridsome/gridsome/commit/cbcede6692e9a29bcce01f9ed112d508d9e653bc))
* **gridsome:** require.resolve develop entries ([ceed033](https://github.com/gridsome/gridsome/commit/ceed033b168f14c866d4dc8210562a561b975dca))
* **gridsome:** require.resolve style loaders ([1af3a9a](https://github.com/gridsome/gridsome/commit/1af3a9a3dc255b9ba5d5276f81c6353ef4441dea))
* **gridsome:** require.resolve webpack loaders ([1c983d5](https://github.com/gridsome/gridsome/commit/1c983d575ed7d5584301d84fcbbba6a59bfdb143))
* **pager:** make showLinks prop work correctly  ([#215](https://github.com/gridsome/gridsome/issues/215)) ([#1429](https://github.com/gridsome/gridsome/issues/1429)) ([f0b9bc7](https://github.com/gridsome/gridsome/commit/f0b9bc7604551055f504d2494db20a9375ce5d90))
* **templates:** don't allow reserved names ([#1427](https://github.com/gridsome/gridsome/issues/1427)) ([4abeeed](https://github.com/gridsome/gridsome/commit/4abeeed83eb2c9dfdebed3e93f714ce7767f6b6f))
* **templates:** throw error if component is missing in prod ([350f9f5](https://github.com/gridsome/gridsome/commit/350f9f5ad7667e2c76467adccc3c9d3942888b16)), closes [#702](https://github.com/gridsome/gridsome/issues/702)
* alias vue to an absolute path ([432c005](https://github.com/gridsome/gridsome/commit/432c005fca02f6775ae3a099156d1d9436c58ac6))
* provide vue-server-renderer with a basedir ([3f60762](https://github.com/gridsome/gridsome/commit/3f6076235a4de27e3c0186603fa64243fd6efe6f))
* remove unnecessary modules ([b5f5a48](https://github.com/gridsome/gridsome/commit/b5f5a482c8fe95f67b147ed58a081c210455e8fa))
* resolve plugins relative to config ([42f3d21](https://github.com/gridsome/gridsome/commit/42f3d217ef2a89749092132cb69ebba58af5036a))


### Code Refactoring

* **app:** move link catcher to directive ([4b4f262](https://github.com/gridsome/gridsome/commit/4b4f262e9552a81951805b15b4fd57d0f8833b95))


### Features

* `useMetaInfo` ([bc04d02](https://github.com/gridsome/gridsome/commit/bc04d02c7c46ee28b728724c49f7992fffa2224c))
* `useRouter` and `useRoute` ([82bc7e3](https://github.com/gridsome/gridsome/commit/82bc7e31980b8574a6d3eb092d43449c4f545302))
* `useStaticQuery` ([3cdd271](https://github.com/gridsome/gridsome/commit/3cdd27154d350130cc590cede71e18440b3ddced))
* load `.env.local` and `.env.*.local` ([#1583](https://github.com/gridsome/gridsome/issues/1583)) ([9920cc8](https://github.com/gridsome/gridsome/commit/9920cc8ba4f81b431e1a3bb7bd1aa47f979b0d36))
* upgrade to vue 2.7 ([6528b8b](https://github.com/gridsome/gridsome/commit/6528b8b4a139fc3e135bce03638c50c2ff6b5ce6))
* **config:** `emptyOutputDir` config ([aea2af0](https://github.com/gridsome/gridsome/commit/aea2af0eaa645453d22e545f687270085248e298))
* **develop:** webpack-dev-server for local dev ([#1470](https://github.com/gridsome/gridsome/issues/1470)) ([27011c6](https://github.com/gridsome/gridsome/commit/27011c61e1c4c95b2ecd5d5a246aebfc526983e3))
* **graphql:** `position` argument for images ([#1471](https://github.com/gridsome/gridsome/issues/1471)) ([61dc649](https://github.com/gridsome/gridsome/commit/61dc64963449cc009b63c70f18961e536a4c00e0))
* typescript support ([#1467](https://github.com/gridsome/gridsome/issues/1467)) ([b14defb](https://github.com/gridsome/gridsome/commit/b14defbe1afdc87f579d34729cd5496fbfd277d8))
* webpack 5 ([#1523](https://github.com/gridsome/gridsome/issues/1523)) ([93344f3](https://github.com/gridsome/gridsome/commit/93344f31416f04cfd54e0d987b24162a5218ba60))
* **develop:** https option for develop command ([#961](https://github.com/gridsome/gridsome/issues/961)) ([65ef93b](https://github.com/gridsome/gridsome/commit/65ef93b54be21f44f3133e05a79f995275e701cd))
* **g-image:** generate placeholder with blurhash ([97006f6](https://github.com/gridsome/gridsome/commit/97006f60751fb2d9fa7b7d6070695cc1c275324f))
* **g-image:** trace and dominant placeholder types ([57809a7](https://github.com/gridsome/gridsome/commit/57809a7534d47785d8802c8099cc2853c55227a5))
* **graphql:** upgrade to graphql v15 ([58292d8](https://github.com/gridsome/gridsome/commit/58292d82ed45eeb79abdbe31c7beac750cb31528))
* **gridsome:** add pnp support ([cd8f298](https://github.com/gridsome/gridsome/commit/cd8f298af8527e20e7443e2ba5dc3ddf85a25d7d))
* **page-query:** include graphql with src attribute ([#806](https://github.com/gridsome/gridsome/issues/806)) ([6dd86f0](https://github.com/gridsome/gridsome/commit/6dd86f0369d2668d97f86cd1305cf934c5f002af))
* make core-js imports absolute ([7e00df1](https://github.com/gridsome/gridsome/commit/7e00df1212882b5ee682e0cb5ffaaddb815f9602))
* **sass-loader:** support for sass-loader@8 and above ([#1108](https://github.com/gridsome/gridsome/issues/1108)) ([34e980f](https://github.com/gridsome/gridsome/commit/34e980f16a486cb0dfd40008a33fb2bc48cbc6c9))


### Performance Improvements

* stream images while processing them ([d6e34f4](https://github.com/gridsome/gridsome/commit/d6e34f4281657b4a4402de7d093aad02170fb420))
* **build:** improve render queue performance ([25ae955](https://github.com/gridsome/gridsome/commit/25ae955e14b25bd56a52a74749d633c203ab97c6))
* **store:** disable adaptive binary indices ([#1190](https://github.com/gridsome/gridsome/issues/1190)) ([83d7c67](https://github.com/gridsome/gridsome/commit/83d7c67daeb454e0b6c64dada25dc655b7f8baec))


### BREAKING CHANGES

* **app:** use `v-catch-links` to make internal links in custom HTML use the Vue router





## [0.7.23](https://github.com/gridsome/gridsome/compare/gridsome@0.7.22...gridsome@0.7.23) (2020-11-22)


### Bug Fixes

* **develop:** guard against sockjs `null` argument ([#1383](https://github.com/gridsome/gridsome/issues/1383)) ([ed99c62](https://github.com/gridsome/gridsome/commit/ed99c62fc81c7886484a55493c5502cb900832ea))
* **g-image:** support uppercase file extensions ([#1381](https://github.com/gridsome/gridsome/issues/1381)) ([063c984](https://github.com/gridsome/gridsome/commit/063c98444d3e3c59c0536e5b3b784dedc5d9e109))





## [0.7.22](https://github.com/gridsome/gridsome/compare/gridsome@0.7.21...gridsome@0.7.22) (2020-11-04)


### Bug Fixes

* **g-image:** proper immediate typing and behaviour ([#1372](https://github.com/gridsome/gridsome/issues/1372)) ([a4c9d1f](https://github.com/gridsome/gridsome/commit/a4c9d1f061427a50ae84b3dea3f2881e0562cbd3))
* **g-link:** add support for v-html ([#1373](https://github.com/gridsome/gridsome/issues/1373)) ([3762ecd](https://github.com/gridsome/gridsome/commit/3762ecd1d5d16d91d2976ef2dbdcea86fb5f0dba))
* **pages:** dynamic route params in directories on windows ([#1359](https://github.com/gridsome/gridsome/issues/1359)) ([3d36051](https://github.com/gridsome/gridsome/commit/3d360512ed51045df876df426c450beb891d29e9))





## [0.7.21](https://github.com/gridsome/gridsome/compare/gridsome@0.7.20...gridsome@0.7.21) (2020-09-18)


### Bug Fixes

* **graphql:** convert to input type correctly ([#1338](https://github.com/gridsome/gridsome/issues/1338)) ([09478fc](https://github.com/gridsome/gridsome/commit/09478fc16b8701581e339aec8e09e6e5ab384d7f))
* **graphql:** prevent infinite loop while creating input types ([7e5f863](https://github.com/gridsome/gridsome/commit/7e5f863199d86b9d0eeb288719cbe96765cbc7ac))





## [0.7.20](https://github.com/gridsome/gridsome/compare/gridsome@0.7.19...gridsome@0.7.20) (2020-08-20)


### Bug Fixes

* **app:** clear cache if the request fails ([#1312](https://github.com/gridsome/gridsome/issues/1312)) ([f3f473e](https://github.com/gridsome/gridsome/commit/f3f473e9883bc7879f21b3c69522cf2c9a32a82f))
* **app:** decode anchor hash value ([#1281](https://github.com/gridsome/gridsome/issues/1281)) ([#1293](https://github.com/gridsome/gridsome/issues/1293)) ([b93eb39](https://github.com/gridsome/gridsome/commit/b93eb39ec41384f9ec1869650e29d783d93a5d48))
* **develop:** ensure dynamic page loads on first run ([6357f19](https://github.com/gridsome/gridsome/commit/6357f1934510e8fae2d950c6074818b35e70fcba))
* **g-image:** exclude base64 data when not lazy loading ([#1318](https://github.com/gridsome/gridsome/issues/1318)) ([be15ba8](https://github.com/gridsome/gridsome/commit/be15ba89518d73178613ca50d19cbe091363e6d0))





## [0.7.19](https://github.com/gridsome/gridsome/compare/gridsome@0.7.18...gridsome@0.7.19) (2020-07-08)


### Bug Fixes

* **g-image:** option for disabling compression ([#1256](https://github.com/gridsome/gridsome/issues/1256)) ([7e6691f](https://github.com/gridsome/gridsome/commit/7e6691febd5ba7de40b33a15de6940fead8316cd))
* **g-image:** prevent increased image sizes ([#1256](https://github.com/gridsome/gridsome/issues/1256)) ([20776c9](https://github.com/gridsome/gridsome/commit/20776c90e8ad48bbb653ed5358e303d44093750e))





## [0.7.18](https://github.com/gridsome/gridsome/compare/gridsome@0.7.17...gridsome@0.7.18) (2020-07-02)


### Bug Fixes

* **app:** redirect to fallback route if not found ([#1239](https://github.com/gridsome/gridsome/issues/1239)) ([41f2b0f](https://github.com/gridsome/gridsome/commit/41f2b0ff411b319cd2a018c5d1b8d256088d9e57))
* **app:** set custom classes for <Pager> links ([#1234](https://github.com/gridsome/gridsome/issues/1234)) ([f2ba2a3](https://github.com/gridsome/gridsome/commit/f2ba2a385591cf09bd07b64652ee314febd431ee))
* **build:** ensure routes always have the same order ([#1247](https://github.com/gridsome/gridsome/issues/1247)) ([da5674f](https://github.com/gridsome/gridsome/commit/da5674fd248fd518963328628d578c0c93451d95))
* **build:** keep webpack hash between builds ([#1247](https://github.com/gridsome/gridsome/issues/1247)) ([e184813](https://github.com/gridsome/gridsome/commit/e1848132f0466cb4bf2dc0a4bfe621cc9599e1ad))
* **develop:** audio/video playback issues in Chrome ([#1220](https://github.com/gridsome/gridsome/issues/1220)) ([3a3c235](https://github.com/gridsome/gridsome/commit/3a3c235331449011a05117667215b71f71b2416d))
* **develop:** fallback to url when no key param is set ([809aaf8](https://github.com/gridsome/gridsome/commit/809aaf8a8b40d07ef89c34c32bfe783e33b61f43))
* **graphql:** add missing ref exists functions ([#1252](https://github.com/gridsome/gridsome/issues/1252)) ([83b0f96](https://github.com/gridsome/gridsome/commit/83b0f966fcdd3ae6a1e0231985d45c3f2e74a308))
* **graphql:** ensure inferred fields are added to filters ([#718](https://github.com/gridsome/gridsome/issues/718)) ([18d0091](https://github.com/gridsome/gridsome/commit/18d009168c01955a1f006a1cbf95073e33634afc))


### Performance Improvements

* **build:** improve page-query runner ([e3a88be](https://github.com/gridsome/gridsome/commit/e3a88be673b58fd563c4528038e6dca77d5ec7fa))





## [0.7.17](https://github.com/gridsome/gridsome/compare/gridsome@0.7.16...gridsome@0.7.17) (2020-06-07)


### Performance Improvements

* **build:** improve page-query output performance ([#1190](https://github.com/gridsome/gridsome/issues/1190)) ([2d81133](https://github.com/gridsome/gridsome/commit/2d811337bb61627ebb51e90404fcb24425bffd1d))
* **g-image:** get dimensions from sharp metadata ([4f8ed20](https://github.com/gridsome/gridsome/commit/4f8ed20c30608fe624f3e3dad87174f600b50e1d))
* **graphql:** improve path argument performance ([#1190](https://github.com/gridsome/gridsome/issues/1190)) ([8f15b4c](https://github.com/gridsome/gridsome/commit/8f15b4c01e650476c174b3e1c8b0f00ee66dd739))
* **store:** disable adaptive indices for node index ([#1190](https://github.com/gridsome/gridsome/issues/1190)) ([52f90e4](https://github.com/gridsome/gridsome/commit/52f90e4196971411b1559e601b38abf798c63198))
* **templates:** cache date while generating paths ([#1190](https://github.com/gridsome/gridsome/issues/1190)) ([c4f17a0](https://github.com/gridsome/gridsome/commit/c4f17a020491d1d7238e416a9911f543aac4b3e1))





## [0.7.16](https://github.com/gridsome/gridsome/compare/gridsome@0.7.15...gridsome@0.7.16) (2020-06-03)


### Bug Fixes

* **graphql:** calculate pagination in dev mode ([#1198](https://github.com/gridsome/gridsome/issues/1198)) ([39e9381](https://github.com/gridsome/gridsome/commit/39e9381e764a634dd6af7e17fc085e66f7f1a674))





## [0.7.15](https://github.com/gridsome/gridsome/compare/gridsome@0.7.14...gridsome@0.7.15) (2020-05-26)


### Bug Fixes

* **app:** add extra debugging output on hash mismatch failure ([#1150](https://github.com/gridsome/gridsome/issues/1150)) ([dc1a3fe](https://github.com/gridsome/gridsome/commit/dc1a3fe528f61c97b1dab0b34fb93076a33cdf08))
* **app:** reduce generated code in routes.js ([#724](https://github.com/gridsome/gridsome/issues/724)) ([5e1d49a](https://github.com/gridsome/gridsome/commit/5e1d49ad1f0069bc4e7e73b05e2e3be72a31fbbe))
* **config:** skip undefined plugins ([3dc6b0f](https://github.com/gridsome/gridsome/commit/3dc6b0f74ddf20aacb774056d7c2e66e05a72209))
* **g-image:** rotate based on exif orientation ([#1178](https://github.com/gridsome/gridsome/issues/1178)) ([9e6e118](https://github.com/gridsome/gridsome/commit/9e6e1186ea3f06913a8843062dc86b0969b34d85))
* **graphql:** add exists filter query operator ([4777d0c](https://github.com/gridsome/gridsome/commit/4777d0ccd9b04201d63bc17bda520b622df4b304))
* **graphql:** allow GET request with query param ([#1127](https://github.com/gridsome/gridsome/issues/1127)) ([5a28064](https://github.com/gridsome/gridsome/commit/5a280646a368dd8b29ffa648405b6953451aa81a))
* **graphql:** exclude undefined variables in page-query ([f753a47](https://github.com/gridsome/gridsome/commit/f753a47f247828538dbb803a2b28bddc230e194c))
* **graphql:** use correct type for store.addReference() ([5b71d04](https://github.com/gridsome/gridsome/commit/5b71d04ddd23eaf0a5ba40fc56a93db77999cf87))





## [0.7.14](https://github.com/gridsome/gridsome/compare/gridsome@0.7.13...gridsome@0.7.14) (2020-04-18)


### Bug Fixes

* **app:** add trailing slash to paths in Pager component ([#1073](https://github.com/gridsome/gridsome/issues/1073)) ([a559bb8](https://github.com/gridsome/gridsome/commit/a559bb8138f5021c22d00777c7b6021c5a4f36dd))
* **app:** include pathPrefix when hard reloading app ([#1044](https://github.com/gridsome/gridsome/issues/1044)) ([4d22712](https://github.com/gridsome/gridsome/commit/4d2271222cb44e94b9e6f7c0ca04740226c0a7ce))
* **graphql:** pass operationName argument to graphql method ([#1047](https://github.com/gridsome/gridsome/issues/1047)) ([a5c2d3b](https://github.com/gridsome/gridsome/commit/a5c2d3b1b812f8f80f3f96b7fa30d30e1ed64035))





## [0.7.13](https://github.com/gridsome/gridsome/compare/gridsome@0.7.12...gridsome@0.7.13) (2020-02-18)


### Bug Fixes

* **app:** allow pascal cased g-link and g-image ([#985](https://github.com/gridsome/gridsome/issues/985)) ([b4805eb](https://github.com/gridsome/gridsome/commit/b4805eb3b01806fea53ced94e91a55b6754879a2))
* **app:** option for disabling global link catcher ([#959](https://github.com/gridsome/gridsome/issues/959)) ([3acbada](https://github.com/gridsome/gridsome/commit/3acbada56288327dee7118bde7b0d1e9b898bd5c))
* **build:** allow overriding cpu count with env var ([#923](https://github.com/gridsome/gridsome/issues/923)) ([12c4865](https://github.com/gridsome/gridsome/commit/12c486545170feb4096ffd88600e618873884a9a))
* **build:** handle some webpack errors properly ([#932](https://github.com/gridsome/gridsome/issues/932)) ([63bd6a3](https://github.com/gridsome/gridsome/commit/63bd6a3966db687fce74c5e13564d33451fe4748))
* **pages:** add missing find* API methods ([#927](https://github.com/gridsome/gridsome/issues/927)) ([bfc1104](https://github.com/gridsome/gridsome/commit/bfc1104b332c62f7c948c2e5bc14541df44099e5))
* **pages:** return if no page is found in `removePage()` ([#926](https://github.com/gridsome/gridsome/issues/926)) ([9d8aef7](https://github.com/gridsome/gridsome/commit/9d8aef77b5eae5be7776af93a72d1b336a58e8d1))
* **webpack:** ignore missing default export in main.js ([a81ed0e](https://github.com/gridsome/gridsome/commit/a81ed0e99a6cf78dffb5a42e5cfc0293b76f069e))





## [0.7.12](https://github.com/gridsome/gridsome/compare/gridsome@0.7.11...gridsome@0.7.12) (2019-12-13)


### Bug Fixes

* **build:** option for disabling hash in asset filenames ([#840](https://github.com/gridsome/gridsome/issues/840)) ([6765782](https://github.com/gridsome/gridsome/commit/6765782723ae1646a96903eebc15f045df062692))
* **webpack:** use devServer.watchOptions for dev middleware ([#865](https://github.com/gridsome/gridsome/issues/865)) ([0bedcdb](https://github.com/gridsome/gridsome/commit/0bedcdbf7abd02f340bd94b3a905325eda3c996f))





## [0.7.11](https://github.com/gridsome/gridsome/compare/gridsome@0.7.10...gridsome@0.7.11) (2019-11-19)


### Bug Fixes

* **app:** ensure favicon height is set ([5164258](https://github.com/gridsome/gridsome/commit/5164258))
* **g-image:** option for setting default blur ([#760](https://github.com/gridsome/gridsome/issues/760)) ([71421f3](https://github.com/gridsome/gridsome/commit/71421f3))
* **g-image:** set blank src if sets is empty ([#824](https://github.com/gridsome/gridsome/issues/824)) ([8ab30fc](https://github.com/gridsome/gridsome/commit/8ab30fc))
* **graphql:** createEnumType schema method ([#814](https://github.com/gridsome/gridsome/issues/814)) ([b09b116](https://github.com/gridsome/gridsome/commit/b09b116))





## [0.7.10](https://github.com/gridsome/gridsome/compare/gridsome@0.7.9...gridsome@0.7.10) (2019-11-06)


### Bug Fixes

* **app:** allow custom routes from router.addRoutes ([fc78a59](https://github.com/gridsome/gridsome/commit/fc78a59))
* **g-image:** include wanted width in srcset ([#797](https://github.com/gridsome/gridsome/issues/797)) ([26dc27b](https://github.com/gridsome/gridsome/commit/26dc27b))
* **g-image:** resize correctly when reusing image ([#797](https://github.com/gridsome/gridsome/issues/797)) ([8c2d834](https://github.com/gridsome/gridsome/commit/8c2d834))
* **graphql:** convert field to union if multiple typeNames ([8bf2931](https://github.com/gridsome/gridsome/commit/8bf2931))
* **store:** resolve absolute paths in fields correctly ([#792](https://github.com/gridsome/gridsome/issues/792)) ([beb9084](https://github.com/gridsome/gridsome/commit/beb9084))





## [0.7.9](https://github.com/gridsome/gridsome/compare/gridsome@0.7.8...gridsome@0.7.9) (2019-10-25)


### Bug Fixes

* **app:** don’t resolve constructor components ([#552](https://github.com/gridsome/gridsome/issues/552)) ([a4e22d6](https://github.com/gridsome/gridsome/commit/a4e22d6))
* **g-image:** always crop by given dimensions ([#759](https://github.com/gridsome/gridsome/issues/759)) ([97ca9db](https://github.com/gridsome/gridsome/commit/97ca9db))
* **g-link:** don't use router-link for mailto and tel links ([#755](https://github.com/gridsome/gridsome/issues/755)) ([d1b5779](https://github.com/gridsome/gridsome/commit/d1b5779))





## [0.7.8](https://github.com/gridsome/gridsome/compare/gridsome@0.7.7...gridsome@0.7.8) (2019-10-15)


### Bug Fixes

* **graphql:** apply extensions once per usage ([91f346e](https://github.com/gridsome/gridsome/commit/91f346e))
* **graphql:** filter collection by reference id ([#745](https://github.com/gridsome/gridsome/issues/745)) ([cbb009a](https://github.com/gridsome/gridsome/commit/cbb009a))
* **graphql:** keep extensions for third party fields ([b0e3cfb](https://github.com/gridsome/gridsome/commit/b0e3cfb))
* **graphql:** prevent overriding built-in directives ([878e947](https://github.com/gridsome/gridsome/commit/878e947))
* **store:** ensure reference node id’s are strings ([98a3edf](https://github.com/gridsome/gridsome/commit/98a3edf))
* **store:** require unique paths for templates only ([91225f1](https://github.com/gridsome/gridsome/commit/91225f1))





## [0.7.7](https://github.com/gridsome/gridsome/compare/gridsome@0.7.6...gridsome@0.7.7) (2019-10-01)


### Bug Fixes

* **assets:** better error message for broken images ([59919aa](https://github.com/gridsome/gridsome/commit/59919aa))
* **build:** validate page-query during build ([5fff97a](https://github.com/gridsome/gridsome/commit/5fff97a))
* **graphql:** don’t create empty fields in objects ([#713](https://github.com/gridsome/gridsome/issues/713)) ([b4776e2](https://github.com/gridsome/gridsome/commit/b4776e2))
* **graphql:** don’t create fields for lists with invalid values ([f635e8b](https://github.com/gridsome/gridsome/commit/f635e8b))
* **graphql:** set sdl type def with addReference ([619b510](https://github.com/gridsome/gridsome/commit/619b510))
* **graphql:** validate static queries ([b9e79f2](https://github.com/gridsome/gridsome/commit/b9e79f2))





## [0.7.6](https://github.com/gridsome/gridsome/compare/gridsome@0.7.5...gridsome@0.7.6) (2019-09-27)


### Bug Fixes

* **app:** don’t resolve links without path prefix ([66eb650](https://github.com/gridsome/gridsome/commit/66eb650))
* **app:** ignore NavigationDuplicated error ([#703](https://github.com/gridsome/gridsome/issues/703)) ([a000bfb](https://github.com/gridsome/gridsome/commit/a000bfb))
* **app:** prevent request to favicon.ico ([#711](https://github.com/gridsome/gridsome/issues/711)) ([28278f7](https://github.com/gridsome/gridsome/commit/28278f7))
* **graphql:** don’t create input types for unions ([c4ba3c5](https://github.com/gridsome/gridsome/commit/c4ba3c5))





## [0.7.5](https://github.com/gridsome/gridsome/compare/gridsome@0.7.4...gridsome@0.7.5) (2019-09-22)


### Bug Fixes

* **graphql:** add schema.createScalarType() method ([5f59747](https://github.com/gridsome/gridsome/commit/5f59747))
* **graphql:** don’t fix variables for other types ([#689](https://github.com/gridsome/gridsome/issues/689)) ([35cfd2b](https://github.com/gridsome/gridsome/commit/35cfd2b))





## [0.7.4](https://github.com/gridsome/gridsome/compare/gridsome@0.7.3...gridsome@0.7.4) (2019-09-20)


### Bug Fixes

* **develop:** show original error when no filename ([eb702d8](https://github.com/gridsome/gridsome/commit/eb702d8))
* **graphql:** auto create missing reference fields ([9a4d24c](https://github.com/gridsome/gridsome/commit/9a4d24c))
* **graphql:** don’t process invalid references ([b88960e](https://github.com/gridsome/gridsome/commit/b88960e))
* **graphql:** don’t transform missing input types ([6e2f28e](https://github.com/gridsome/gridsome/commit/6e2f28e))
* **graphql:** fix union fields by addReference() ([99e2ce8](https://github.com/gridsome/gridsome/commit/99e2ce8))
* **graphql:** ignore trailing slash for path argument ([2b5d17f](https://github.com/gridsome/gridsome/commit/2b5d17f))
* **pages:** show an error if component is not found ([654d075](https://github.com/gridsome/gridsome/commit/654d075))





## [0.7.3](https://github.com/gridsome/gridsome/compare/gridsome@0.7.2...gridsome@0.7.3) (2019-09-16)


### Bug Fixes

* **api:** allow arrow function as default export ([44d13bc](https://github.com/gridsome/gridsome/commit/44d13bc))
* **api:** use express app in configureServer ([#668](https://github.com/gridsome/gridsome/issues/668)) ([fff7a8f](https://github.com/gridsome/gridsome/commit/fff7a8f))
* **build:** support symlinks in static folder ([#671](https://github.com/gridsome/gridsome/issues/671)) ([d35ec39](https://github.com/gridsome/gridsome/commit/d35ec39))
* **build:** use pretty path in render queue ([699b027](https://github.com/gridsome/gridsome/commit/699b027))
* **graphql:** don’t fix unknown variable types ([8e45485](https://github.com/gridsome/gridsome/commit/8e45485))
* **graphql:** proxy invalid reference field names ([b23df81](https://github.com/gridsome/gridsome/commit/b23df81))
* **graphql:** update variables when query changes ([0fc0056](https://github.com/gridsome/gridsome/commit/0fc0056))
* **templates:** fix templates on windows ([a80fb76](https://github.com/gridsome/gridsome/commit/a80fb76))





## [0.7.2](https://github.com/gridsome/gridsome/compare/gridsome@0.7.1...gridsome@0.7.2) (2019-09-13)


### Bug Fixes

* **build:** ensure column width for deprecation notices ([50a6ebb](https://github.com/gridsome/gridsome/commit/50a6ebb))
* **develop:** refresh query results on navigation ([0ce8de3](https://github.com/gridsome/gridsome/commit/0ce8de3))
* **graphql:** don’t process empty object fields ([#662](https://github.com/gridsome/gridsome/issues/662)) ([7852e9e](https://github.com/gridsome/gridsome/commit/7852e9e))
* **graphql:** process object types only once ([11416ac](https://github.com/gridsome/gridsome/commit/11416ac))
* **graphql:** require resolve for custom resolvers ([63da3dd](https://github.com/gridsome/gridsome/commit/63da3dd))





## [0.7.1](https://github.com/gridsome/gridsome/compare/gridsome@0.7.0...gridsome@0.7.1) (2019-09-12)


### Bug Fixes

* **graphql:** fix metadata module error ([598de72](https://github.com/gridsome/gridsome/commit/598de72))
* **graphql:** return 404 for missing pages ([7e3fe84](https://github.com/gridsome/gridsome/commit/7e3fe84))
* **store:** keep custom _id field on node ([bee711c](https://github.com/gridsome/gridsome/commit/bee711c))
* **store:** return collection in getCollection action ([7f0a631](https://github.com/gridsome/gridsome/commit/7f0a631))
* **templates:** skip auto template if no node paths ([2e72f5f](https://github.com/gridsome/gridsome/commit/2e72f5f))





# [0.7.0](https://github.com/gridsome/gridsome/compare/gridsome@0.6.9...gridsome@0.7.0) (2019-09-11)


### Bug Fixes

* **app:** ensure siteUrl is set before checking url ([dfdfea9](https://github.com/gridsome/gridsome/commit/dfdfea9))
* **build:** show better error messages ([b71bcc6](https://github.com/gridsome/gridsome/commit/b71bcc6))
* **develop:** run sockjs on main port ([e78503b](https://github.com/gridsome/gridsome/commit/e78503b))
* **develop:** show deprecation notices ([#639](https://github.com/gridsome/gridsome/issues/639)) ([9ed78c9](https://github.com/gridsome/gridsome/commit/9ed78c9))
* **templates:** preserve trailing slash in routes ([f7b5397](https://github.com/gridsome/gridsome/commit/f7b5397))


### Features

* **app:** override App.vue component ([#635](https://github.com/gridsome/gridsome/issues/635)) ([fc9606d](https://github.com/gridsome/gridsome/commit/fc9606d))
* **app:** permalinks config ([#574](https://github.com/gridsome/gridsome/issues/574)) ([e89d80a](https://github.com/gridsome/gridsome/commit/e89d80a)), closes [#121](https://github.com/gridsome/gridsome/issues/121)
* **app:** upgrade to vue-meta v2.0 ([eac20ef](https://github.com/gridsome/gridsome/commit/eac20ef))
* **develop:** run site on local network ([a1d91f4](https://github.com/gridsome/gridsome/commit/a1d91f4))
* **graphql:** customize the schema ([#509](https://github.com/gridsome/gridsome/issues/509)) ([c4684b2](https://github.com/gridsome/gridsome/commit/c4684b2))
* **pages:** dynamic routing ([#570](https://github.com/gridsome/gridsome/issues/570)) ([0061019](https://github.com/gridsome/gridsome/commit/0061019))
* **pages:** trailing slash for page paths ([3116ed5](https://github.com/gridsome/gridsome/commit/3116ed5))
* **templates:** centralized templates config ([#571](https://github.com/gridsome/gridsome/issues/571)) ([04fa6d1](https://github.com/gridsome/gridsome/commit/04fa6d1))





## [0.6.9](https://github.com/gridsome/gridsome/compare/gridsome@0.6.8...gridsome@0.6.9) (2019-08-29)


### Bug Fixes

* **graphql:** ensure field value is array for lists ([8e02ccd](https://github.com/gridsome/gridsome/commit/8e02ccd))





## [0.6.8](https://github.com/gridsome/gridsome/compare/gridsome@0.6.7...gridsome@0.6.8) (2019-08-19)


### Bug Fixes

* **develop:** always use port from cli args ([d94c76c](https://github.com/gridsome/gridsome/commit/d94c76c)), closes [http-party/node-portfinder#84](https://github.com/http-party/node-portfinder/issues/84)
* **g-image:** fix size for fit inside and fit outside ([#608](https://github.com/gridsome/gridsome/issues/608)) ([ff88566](https://github.com/gridsome/gridsome/commit/ff88566))
* **graphql:** image background argument ([#596](https://github.com/gridsome/gridsome/issues/596)) ([1f7702c](https://github.com/gridsome/gridsome/commit/1f7702c))
* **graphql:** process images in list ([#609](https://github.com/gridsome/gridsome/issues/609)) ([97590d0](https://github.com/gridsome/gridsome/commit/97590d0))
* **store:** resolve absolute url paths ([990b673](https://github.com/gridsome/gridsome/commit/990b673))





## [0.6.7](https://github.com/gridsome/gridsome/compare/gridsome@0.6.6...gridsome@0.6.7) (2019-07-25)


### Bug Fixes

* **build:** don’t inline large data sets ([#462](https://github.com/gridsome/gridsome/issues/462)) ([88f28a7](https://github.com/gridsome/gridsome/commit/88f28a7))
* **config:** load custom favicon config ([#526](https://github.com/gridsome/gridsome/issues/526)) ([73a4c38](https://github.com/gridsome/gridsome/commit/73a4c38))
* **graphql:** return null if date value is null or falsy ([#527](https://github.com/gridsome/gridsome/issues/527)) ([3b4de3a](https://github.com/gridsome/gridsome/commit/3b4de3a))


### Performance Improvements

* **pages:** improve pages api performance ([#548](https://github.com/gridsome/gridsome/issues/548)) ([9bc4ddb](https://github.com/gridsome/gridsome/commit/9bc4ddb))





## [0.6.6](https://github.com/gridsome/gridsome/compare/gridsome@0.6.5...gridsome@0.6.6) (2019-07-05)


### Bug Fixes

* **app:** parse json regardless of content-type ([#534](https://github.com/gridsome/gridsome/issues/534)) ([f2d2d40](https://github.com/gridsome/gridsome/commit/f2d2d40))
* **develop:** show 404 for page/1 in development ([#515](https://github.com/gridsome/gridsome/issues/515)) ([9a10a37](https://github.com/gridsome/gridsome/commit/9a10a37))
* **store:** do not resolve emails ([#500](https://github.com/gridsome/gridsome/issues/500)) ([6105069](https://github.com/gridsome/gridsome/commit/6105069))





## [0.6.5](https://github.com/gridsome/gridsome/compare/gridsome@0.6.4...gridsome@0.6.5) (2019-06-25)


### Bug Fixes

* **app:** don’t fetch data if no context in development ([0850875](https://github.com/gridsome/gridsome/commit/0850875))
* **app:** don’t use empty siteDescription ([#511](https://github.com/gridsome/gridsome/issues/511), [#516](https://github.com/gridsome/gridsome/issues/516)) ([346279d](https://github.com/gridsome/gridsome/commit/346279d))
* **app:** improve IE11 compatibility ([39b5114](https://github.com/gridsome/gridsome/commit/39b5114))
* **app:** reload when assets are missing ([#488](https://github.com/gridsome/gridsome/issues/488)) ([db86a09](https://github.com/gridsome/gridsome/commit/db86a09))
* **app:** use xhr for better IE compatibility ([81b5e84](https://github.com/gridsome/gridsome/commit/81b5e84))
* **build:** stabilize image processing worker ([#501](https://github.com/gridsome/gridsome/issues/501)) ([9d66273](https://github.com/gridsome/gridsome/commit/9d66273))
* **build:** warm up sharp to prevent xmllib error ([918e76b](https://github.com/gridsome/gridsome/commit/918e76b))
* **develop:** request graphql endpoint without page path ([#518](https://github.com/gridsome/gridsome/issues/518)) ([d9c0eec](https://github.com/gridsome/gridsome/commit/d9c0eec))
* **graphql:** resolve deprecated node.fields field ([#477](https://github.com/gridsome/gridsome/issues/477)) ([36911bd](https://github.com/gridsome/gridsome/commit/36911bd))





## [0.6.4](https://github.com/gridsome/gridsome/compare/gridsome@0.6.3...gridsome@0.6.4) (2019-06-07)


### Bug Fixes

* **app:** don’t prefetch already loaded data ([025ab83](https://github.com/gridsome/gridsome/commit/025ab83))
* **app:** prevent images from loading twice ([#486](https://github.com/gridsome/gridsome/issues/486)) ([d44b5ac](https://github.com/gridsome/gridsome/commit/d44b5ac)), closes [#438](https://github.com/gridsome/gridsome/issues/438)
* **app:** respect active link class options ([#478](https://github.com/gridsome/gridsome/issues/478)) ([f27cfd6](https://github.com/gridsome/gridsome/commit/f27cfd6))
* **build:** don’t write out empty data files ([55f323d](https://github.com/gridsome/gridsome/commit/55f323d))
* **webpack:** inject promise polyfill ([#480](https://github.com/gridsome/gridsome/issues/480)) ([ae29fea](https://github.com/gridsome/gridsome/commit/ae29fea))





## [0.6.3](https://github.com/gridsome/gridsome/compare/gridsome@0.6.2...gridsome@0.6.3) (2019-05-27)


### Bug Fixes

* **webpack:** externalize included dependencies only ([adbff52](https://github.com/gridsome/gridsome/commit/adbff52))





## [0.6.2](https://github.com/gridsome/gridsome/compare/gridsome@0.6.1...gridsome@0.6.2) (2019-05-20)


### Bug Fixes

* **app:** include query params in html links ([f0b162e](https://github.com/gridsome/gridsome/commit/f0b162e))
* **app:** prevent infinite loop for 404 ([#387](https://github.com/gridsome/gridsome/issues/387)) ([698f8b3](https://github.com/gridsome/gridsome/commit/698f8b3))
* **app:** resolve pagination with trailing slash ([#430](https://github.com/gridsome/gridsome/issues/430)) ([a035311](https://github.com/gridsome/gridsome/commit/a035311))
* **build:** ensure page context is an object ([#434](https://github.com/gridsome/gridsome/issues/434)) ([65bc3ed](https://github.com/gridsome/gridsome/commit/65bc3ed))
* **explore:** set correct mode for explore command ([#435](https://github.com/gridsome/gridsome/issues/435)) ([08b312e](https://github.com/gridsome/gridsome/commit/08b312e))
* **store:** do not slugify id in routes ([#429](https://github.com/gridsome/gridsome/issues/429)) ([308beff](https://github.com/gridsome/gridsome/commit/308beff))
* **store:** use custom year, month or day fields if they exist ([91728ef](https://github.com/gridsome/gridsome/commit/91728ef))





## [0.6.1](https://github.com/gridsome/gridsome/compare/gridsome@0.6.0...gridsome@0.6.1) (2019-05-13)


### Bug Fixes

* **app:** prevent cyclic dependency ([#421](https://github.com/gridsome/gridsome/issues/421)) ([3574efa](https://github.com/gridsome/gridsome/commit/3574efa))
* **graphql:** use correct typeName for belongsTo pagination ([#422](https://github.com/gridsome/gridsome/issues/422)) ([b06310f](https://github.com/gridsome/gridsome/commit/b06310f))
* **pages:** set page context in dev mode ([#417](https://github.com/gridsome/gridsome/issues/417)) ([a7a6e17](https://github.com/gridsome/gridsome/commit/a7a6e17))
* **store:** create reference to node instance ([81bb047](https://github.com/gridsome/gridsome/commit/81bb047))





# [0.6.0](https://github.com/gridsome/gridsome/compare/gridsome@0.5.8...gridsome@0.6.0) (2019-05-10)


### Bug Fixes

* **assets:** encode generated urls ([#393](https://github.com/gridsome/gridsome/issues/393)) ([b6994c8](https://github.com/gridsome/gridsome/commit/b6994c8))
* **build:** keep dist folder between builds ([#409](https://github.com/gridsome/gridsome/issues/409)) ([1ef584b](https://github.com/gridsome/gridsome/commit/1ef584b))
* **build:** set correct dest path for files ([#221](https://github.com/gridsome/gridsome/issues/221)) ([f9dad9e](https://github.com/gridsome/gridsome/commit/f9dad9e))
* **graphql:** do not camelCase field names automatically ([#351](https://github.com/gridsome/gridsome/issues/351)) ([4e54c5c](https://github.com/gridsome/gridsome/commit/4e54c5c))
* **graphql:** ensure totalPages count is not null ([ae75b39](https://github.com/gridsome/gridsome/commit/ae75b39))


### Features

* **api:** helper method for resolving paths ([db3546f](https://github.com/gridsome/gridsome/commit/db3546f))
* **app:** method for fetching page data ([2a624ab](https://github.com/gridsome/gridsome/commit/2a624ab))
* **app:** range option for Pager component ([#344](https://github.com/gridsome/gridsome/issues/344)) ([77dab89](https://github.com/gridsome/gridsome/commit/77dab89))
* **graphql:** add metaData from config ([#225](https://github.com/gridsome/gridsome/issues/225)) ([b90d490](https://github.com/gridsome/gridsome/commit/b90d490))
* **graphql:** advanced sort argument ([#247](https://github.com/gridsome/gridsome/issues/247)) ([9b0907e](https://github.com/gridsome/gridsome/commit/9b0907e))
* **graphql:** limit argument for content types and belongsTo ([7756620](https://github.com/gridsome/gridsome/commit/7756620))
* **pages:** create managed pages ([a9042b0](https://github.com/gridsome/gridsome/commit/a9042b0))
* **pages:** pages api ([#309](https://github.com/gridsome/gridsome/issues/309)) ([5c6a45c](https://github.com/gridsome/gridsome/commit/5c6a45c))
* **store:** methods for retrieving nodes ([7b442a2](https://github.com/gridsome/gridsome/commit/7b442a2))
* **webpack:** configure webpack ([#342](https://github.com/gridsome/gridsome/issues/342)) ([ac9fc5a](https://github.com/gridsome/gridsome/commit/ac9fc5a))





## [0.5.8](https://github.com/gridsome/gridsome/compare/gridsome@0.5.7...gridsome@0.5.8) (2019-04-18)


### Bug Fixes

* **app:** don’t handle external links with router ([#367](https://github.com/gridsome/gridsome/issues/367)) ([bfb2a79](https://github.com/gridsome/gridsome/commit/bfb2a79))





## [0.5.7](https://github.com/gridsome/gridsome/compare/gridsome@0.5.6...gridsome@0.5.7) (2019-04-09)


### Bug Fixes

* **app:** don't resolve url for different port ([#350](https://github.com/gridsome/gridsome/issues/350)) ([a6ab23f](https://github.com/gridsome/gridsome/commit/a6ab23f))
* **g-image:** alt attribute for noscript image ([#353](https://github.com/gridsome/gridsome/issues/353)) ([fcfcf36](https://github.com/gridsome/gridsome/commit/fcfcf36))
* **graphql:** prefer float when mixed number types ([#332](https://github.com/gridsome/gridsome/issues/332)) ([b311850](https://github.com/gridsome/gridsome/commit/b311850))





## [0.5.6](https://github.com/gridsome/gridsome/compare/gridsome@0.5.5...gridsome@0.5.6) (2019-03-29)


### Bug Fixes

* **app:** allow absolute path to custom favicon ([53a755c](https://github.com/gridsome/gridsome/commit/53a755c))
* **app:** allow css.split option to be true ([#266](https://github.com/gridsome/gridsome/issues/266)) ([a0fcd10](https://github.com/gridsome/gridsome/commit/a0fcd10))
* **app:** make routes appear in vue-devtools ([#322](https://github.com/gridsome/gridsome/issues/322)) ([f1a865c](https://github.com/gridsome/gridsome/commit/f1a865c))
* **develop:** allow OPTIONS method request to /___graphql ([#271](https://github.com/gridsome/gridsome/issues/271)) ([f1ec997](https://github.com/gridsome/gridsome/commit/f1ec997))
* **g-image:** increase max image width ([#286](https://github.com/gridsome/gridsome/issues/286)) ([8a7ae89](https://github.com/gridsome/gridsome/commit/8a7ae89))
* **graphql:** allow requests without variables ([#323](https://github.com/gridsome/gridsome/issues/323)) ([8184834](https://github.com/gridsome/gridsome/commit/8184834))
* **store:** handle route params starting with raw correctly ([#295](https://github.com/gridsome/gridsome/issues/295)) ([931937c](https://github.com/gridsome/gridsome/commit/931937c))
* **store:** prioritize node.id over node.fields.id ([3d7c180](https://github.com/gridsome/gridsome/commit/3d7c180))
* **store:** support repeated segments in dynamic routes ([#279](https://github.com/gridsome/gridsome/issues/279)) ([2259f85](https://github.com/gridsome/gridsome/commit/2259f85))





## [0.5.5](https://github.com/gridsome/gridsome/compare/gridsome@0.5.4...gridsome@0.5.5) (2019-03-08)


### Bug Fixes

* **app:** don’t preload /404 without page-query ([5835733](https://github.com/gridsome/gridsome/commit/5835733))
* **app:** only intercept left clicks on links ([#236](https://github.com/gridsome/gridsome/issues/236)) ([78413dc](https://github.com/gridsome/gridsome/commit/78413dc))
* **build:** render template with static route and pagination once ([2f4d93a](https://github.com/gridsome/gridsome/commit/2f4d93a))
* **develop:** show /404 for non existing paths ([b18e8e9](https://github.com/gridsome/gridsome/commit/b18e8e9))
* **develop:** update static-query when source changes ([d867e93](https://github.com/gridsome/gridsome/commit/d867e93))
* **graphq:** siteDescription as metaData ([#260](https://github.com/gridsome/gridsome/issues/260)) ([640f72d](https://github.com/gridsome/gridsome/commit/640f72d))
* **pager:** bind linkClass to an object ([#257](https://github.com/gridsome/gridsome/issues/257)) ([6765a3d](https://github.com/gridsome/gridsome/commit/6765a3d))
* **store:** keep references for empty arrays ([ec6fcf9](https://github.com/gridsome/gridsome/commit/ec6fcf9))
* **webpack:** combine all css in one file ([#230](https://github.com/gridsome/gridsome/issues/230)) ([952148d](https://github.com/gridsome/gridsome/commit/952148d))
* **webpack:** support webp images ([#227](https://github.com/gridsome/gridsome/issues/227)) ([72123f7](https://github.com/gridsome/gridsome/commit/72123f7))
* count minimum one physical cpu ([#255](https://github.com/gridsome/gridsome/issues/255)) ([91444c7](https://github.com/gridsome/gridsome/commit/91444c7))
* pin jest-worker version until fix is published ([#252](https://github.com/gridsome/gridsome/issues/252)) ([c0d15b6](https://github.com/gridsome/gridsome/commit/c0d15b6))


### Performance Improvements

* **graphql:** improve belongsTo query performance ([bcdacce](https://github.com/gridsome/gridsome/commit/bcdacce))





<a name="0.5.4"></a>
## [0.5.4](https://github.com/gridsome/gridsome/compare/gridsome@0.5.3...gridsome@0.5.4) (2019-02-27)


### Bug Fixes

* **build:** ensure data directory exists before building ([#93](https://github.com/gridsome/gridsome/issues/93)) ([3453aff](https://github.com/gridsome/gridsome/commit/3453aff))
* **graphql:** don’t process non graphql requests ([#220](https://github.com/gridsome/gridsome/issues/220)) ([c276b98](https://github.com/gridsome/gridsome/commit/c276b98))





<a name="0.5.3"></a>
## [0.5.3](https://github.com/gridsome/gridsome/compare/gridsome@0.5.2...gridsome@0.5.3) (2019-02-26)


### Bug Fixes

* **app:** fetch data properly for homepage ([#218](https://github.com/gridsome/gridsome/issues/218)) ([fd72abc](https://github.com/gridsome/gridsome/commit/fd72abc))





<a name="0.5.2"></a>
## [0.5.2](https://github.com/gridsome/gridsome/compare/gridsome@0.5.1...gridsome@0.5.2) (2019-02-26)


### Bug Fixes

* **app:** preload data for links in view ([35411aa](https://github.com/gridsome/gridsome/commit/35411aa))
* **app:** unslash path before fetching data ([7c086a7](https://github.com/gridsome/gridsome/commit/7c086a7))





<a name="0.5.1"></a>
## [0.5.1](https://github.com/gridsome/gridsome/compare/gridsome@0.5.0...gridsome@0.5.1) (2019-02-26)


### Bug Fixes

* **app:** keep original path when showing 404 ([f0efbaa](https://github.com/gridsome/gridsome/commit/f0efbaa))
* **build:** fail if path resolves to 404 ([#218](https://github.com/gridsome/gridsome/issues/218)) ([b3b7add](https://github.com/gridsome/gridsome/commit/b3b7add))
* **build:** put images in correct folder when pathPrefix is used ([#221](https://github.com/gridsome/gridsome/issues/221)) ([497998c](https://github.com/gridsome/gridsome/commit/497998c))
* **build:** query context for templates with static route ([a962482](https://github.com/gridsome/gridsome/commit/a962482))
* **build:** render pagination correctly for root path ([#218](https://github.com/gridsome/gridsome/issues/218)) ([1ee57fe](https://github.com/gridsome/gridsome/commit/1ee57fe))
* **g-image:** add static classes to noscript image ([#203](https://github.com/gridsome/gridsome/issues/203)) ([c4036b8](https://github.com/gridsome/gridsome/commit/c4036b8))
* **g-image:** refresh when src updates on same element ([7128fd6](https://github.com/gridsome/gridsome/commit/7128fd6))
* **g-image:** remove duplicate class names ([2de526f](https://github.com/gridsome/gridsome/commit/2de526f))
* **graphql:** don’t fail when invalid page-query ([d143767](https://github.com/gridsome/gridsome/commit/d143767))
* **graphql:** improve graphql error handling ([#204](https://github.com/gridsome/gridsome/issues/204)) ([767b674](https://github.com/gridsome/gridsome/commit/767b674))
* **store:** include GraphQLJSON type in addSchemaField ([73e332c](https://github.com/gridsome/gridsome/commit/73e332c))
* **webpack:** don’t fail if g-image or g-link has no attrs ([5267a78](https://github.com/gridsome/gridsome/commit/5267a78))





<a name="0.5.0"></a>
# [0.5.0](https://github.com/gridsome/gridsome/compare/gridsome@0.4.7...gridsome@0.5.0) (2019-02-19)


### Bug Fixes

* **app:** fix cyclic dependency when importing Pager ([#109](https://github.com/gridsome/gridsome/issues/109)) ([b8247af](https://github.com/gridsome/gridsome/commit/b8247af))
* **app:** parse dates as UTC ([bb1972d](https://github.com/gridsome/gridsome/commit/bb1972d))
* **build:** create new Vue instance before each route ([424e678](https://github.com/gridsome/gridsome/commit/424e678))
* **build:** ensure 404 route for /404 page ([70698e0](https://github.com/gridsome/gridsome/commit/70698e0))
* **g-image:** behave properly inside v-for ([#185](https://github.com/gridsome/gridsome/issues/185)) ([e3c2aba](https://github.com/gridsome/gridsome/commit/e3c2aba))
* **g-image:** pass custom blur to asset queue ([1f9ce9a](https://github.com/gridsome/gridsome/commit/1f9ce9a))
* **graphql:** do not send page param in path ([61cdf9c](https://github.com/gridsome/gridsome/commit/61cdf9c))
* **graphql:** don’t convert URLs or filenames to object ([be08c52](https://github.com/gridsome/gridsome/commit/be08c52))
* **graphql:** handle date types correctly ([53f963d](https://github.com/gridsome/gridsome/commit/53f963d))
* **graphql:** improved error handling ([0dad580](https://github.com/gridsome/gridsome/commit/0dad580))
* **graphql:** merge all entries in arrays ([#184](https://github.com/gridsome/gridsome/issues/184)) ([80952d6](https://github.com/gridsome/gridsome/commit/80952d6))
* **graphql:** return null for missing references ([8d920fc](https://github.com/gridsome/gridsome/commit/8d920fc))
* **graphql:** sort by custom field value ([cfcefaf](https://github.com/gridsome/gridsome/commit/cfcefaf))
* **store:** allow regex wildcard route param ([f283526](https://github.com/gridsome/gridsome/commit/f283526))


### Features

* **app:** override active link classes for Pager ([#143](https://github.com/gridsome/gridsome/issues/143)) ([6a5159d](https://github.com/gridsome/gridsome/commit/6a5159d))
* **app:** override default index.html template ([#162](https://github.com/gridsome/gridsome/issues/162)) ([4cdd326](https://github.com/gridsome/gridsome/commit/4cdd326))
* **app:** siteDescription as description meta tag ([#70](https://github.com/gridsome/gridsome/issues/70)) ([6fa118c](https://github.com/gridsome/gridsome/commit/6fa118c))
* **app:** upgrade to Vue 2.6 ([f1ab4e1](https://github.com/gridsome/gridsome/commit/f1ab4e1))
* **build:** generate 404.html file ([#75](https://github.com/gridsome/gridsome/issues/75)) ([59988e5](https://github.com/gridsome/gridsome/commit/59988e5))
* **develop:** configureServer hook ([029e431](https://github.com/gridsome/gridsome/commit/029e431))
* **g-link:** rel noopener for external links ([#104](https://github.com/gridsome/gridsome/issues/104)) ([9f11efb](https://github.com/gridsome/gridsome/commit/9f11efb))
* **graphql:** belongsTo field for listing references ([#119](https://github.com/gridsome/gridsome/issues/119)) ([2ef275f](https://github.com/gridsome/gridsome/commit/2ef275f))
* **graphql:** current node as query variables ([#77](https://github.com/gridsome/gridsome/issues/77)) ([1beece4](https://github.com/gridsome/gridsome/commit/1beece4))
* **graphql:** filter argument ([#84](https://github.com/gridsome/gridsome/issues/84)) ([692f6cb](https://github.com/gridsome/gridsome/commit/692f6cb))
* **router:** deep node fields as route params ([#115](https://github.com/gridsome/gridsome/issues/115)) ([2d2ec44](https://github.com/gridsome/gridsome/commit/2d2ec44))
* **store:** helper for creating refs in sub fields ([b9d7add](https://github.com/gridsome/gridsome/commit/b9d7add))
* **webpack:** add custom css loader options ([#46](https://github.com/gridsome/gridsome/issues/46)) ([cf7a505](https://github.com/gridsome/gridsome/commit/cf7a505))
* **webpack:** enviroment variables and support for dotenv files ([#123](https://github.com/gridsome/gridsome/issues/123)) ([c236d8b](https://github.com/gridsome/gridsome/commit/c236d8b))
* **webpack:** use [@vue](https://github.com/vue)/babel-preset-app ([e51e363](https://github.com/gridsome/gridsome/commit/e51e363))





<a name="0.4.7"></a>
## [0.4.7](https://github.com/gridsome/gridsome/compare/gridsome@0.4.6...gridsome@0.4.7) (2019-02-04)


### Bug Fixes

* **app:** add key to viewport meta ([#169](https://github.com/gridsome/gridsome/issues/169)) ([c7f6dfa](https://github.com/gridsome/gridsome/commit/c7f6dfa))
* **store:** pass resolveAbsolutePaths correctly ([6164464](https://github.com/gridsome/gridsome/commit/6164464))
* **webpack:** remove duplicate style links (163) ([5ce0106](https://github.com/gridsome/gridsome/commit/5ce0106))





<a name="0.4.6"></a>
## [0.4.6](https://github.com/gridsome/gridsome/compare/gridsome@0.4.5...gridsome@0.4.6) (2019-01-30)


### Bug Fixes

* **app:** add format-detection meta tag ([#145](https://github.com/gridsome/gridsome/issues/145)) ([f7f94ae](https://github.com/gridsome/gridsome/commit/f7f94ae))
* **app:** simplify IntersectionObserver check ([#153](https://github.com/gridsome/gridsome/issues/153)) ([5a0d729](https://github.com/gridsome/gridsome/commit/5a0d729))
* **build:** throw error if something fails in main.js ([bb62605](https://github.com/gridsome/gridsome/commit/bb62605))
* **g-image:** observe images in v-html ([#158](https://github.com/gridsome/gridsome/issues/158)) ([07821da](https://github.com/gridsome/gridsome/commit/07821da))
* **g-image:** run onload event once ([ca6f015](https://github.com/gridsome/gridsome/commit/ca6f015)), closes [#93](https://github.com/gridsome/gridsome/issues/93)
* **webpack:** don’t cache static-query ([#160](https://github.com/gridsome/gridsome/issues/160)) ([0352f99](https://github.com/gridsome/gridsome/commit/0352f99))





<a name="0.4.5"></a>
## [0.4.5](https://github.com/gridsome/gridsome/compare/gridsome@0.4.4...gridsome@0.4.5) (2019-01-26)


### Bug Fixes

* **app:** custom favicon path ([#149](https://github.com/gridsome/gridsome/issues/149)) ([f6b6b3d](https://github.com/gridsome/gridsome/commit/f6b6b3d)), closes [#138](https://github.com/gridsome/gridsome/issues/138)
* **g-image:** bind custom classes to object ([#151](https://github.com/gridsome/gridsome/issues/151)) ([10150ca](https://github.com/gridsome/gridsome/commit/10150ca))





<a name="0.4.4"></a>
## [0.4.4](https://github.com/gridsome/gridsome/compare/gridsome@0.4.3...gridsome@0.4.4) (2019-01-15)


### Bug Fixes

* **graphql:** merge ref fields correctly ([#128](https://github.com/gridsome/gridsome/issues/128), [#129](https://github.com/gridsome/gridsome/issues/129)) ([ffb29ee](https://github.com/gridsome/gridsome/commit/ffb29ee))
* **webpack:** cache graphql loader results ([6e794ab](https://github.com/gridsome/gridsome/commit/6e794ab))
* **webpack:** transpile custom blocks ([#130](https://github.com/gridsome/gridsome/issues/130)) ([c81fee4](https://github.com/gridsome/gridsome/commit/c81fee4))





<a name="0.4.3"></a>
## [0.4.3](https://github.com/gridsome/gridsome/compare/gridsome@0.4.2...gridsome@0.4.3) (2019-01-09)


### Bug Fixes

* **webpack:** fix config for IE support ([e403f4c](https://github.com/gridsome/gridsome/commit/e403f4c))





<a name="0.4.2"></a>
## [0.4.2](https://github.com/gridsome/gridsome/compare/gridsome@0.4.1...gridsome@0.4.2) (2019-01-07)


### Bug Fixes

* **route:** allow node props as route params ([1658fde](https://github.com/gridsome/gridsome/commit/1658fde))
* **store:** update node content and excerpt ([637e0e4](https://github.com/gridsome/gridsome/commit/637e0e4))





<a name="0.4.1"></a>
## [0.4.1](https://github.com/gridsome/gridsome/compare/gridsome@0.4.0...gridsome@0.4.1) (2019-01-03)


### Bug Fixes

* **config:** customizing host and port ([bc44a64](https://github.com/gridsome/gridsome/commit/bc44a64))
* **config:** use host and port from project config ([7936aa7](https://github.com/gridsome/gridsome/commit/7936aa7))
* **graphql:** fix deprecated references api ([cb6f245](https://github.com/gridsome/gridsome/commit/cb6f245))
* **image:** don’t re-render when parent updates ([#93](https://github.com/gridsome/gridsome/issues/93)) ([c813d70](https://github.com/gridsome/gridsome/commit/c813d70))
* **pathPrefix:** don’t create subfolder ([#85](https://github.com/gridsome/gridsome/issues/85)) ([96bfbed](https://github.com/gridsome/gridsome/commit/96bfbed))
* **router:** add leading slash to routes ([4024ace](https://github.com/gridsome/gridsome/commit/4024ace))





<a name="0.4.0"></a>
# [0.4.0](https://github.com/gridsome/gridsome/compare/gridsome@0.3.6...gridsome@0.4.0) (2018-12-19)


### Bug Fixes

* **app:** use default link behavior if 404 ([f9aeed7](https://github.com/gridsome/gridsome/commit/f9aeed7))
* **g-link:** customizable active classes ([#65](https://github.com/gridsome/gridsome/issues/65)) ([0ee5273](https://github.com/gridsome/gridsome/commit/0ee5273))
* **g-link:** link to local files ([ece2de5](https://github.com/gridsome/gridsome/commit/ece2de5))
* **graphql:** include empty string type in schema ([44b68b2](https://github.com/gridsome/gridsome/commit/44b68b2))
* **graphql:** return null for missing images ([39c5a92](https://github.com/gridsome/gridsome/commit/39c5a92))
* **graphql:** warn when missing reference ([a6f7857](https://github.com/gridsome/gridsome/commit/a6f7857))
* **router:** fetch data for paths with hash ([19a0c78](https://github.com/gridsome/gridsome/commit/19a0c78))
* **store:** dont process null value as an object ([a05bb5a](https://github.com/gridsome/gridsome/commit/a05bb5a))


### Features

* **build:** image processing cache ([#57](https://github.com/gridsome/gridsome/issues/57)) ([0a9e449](https://github.com/gridsome/gridsome/commit/0a9e449))
* **graphql:** add custom metadata ([#54](https://github.com/gridsome/gridsome/issues/54)) ([7b35378](https://github.com/gridsome/gridsome/commit/7b35378))
* **graphql:** reference with multiple node types ([#50](https://github.com/gridsome/gridsome/issues/50)) ([185297f](https://github.com/gridsome/gridsome/commit/185297f))
* **image:** crop by width and height ([#78](https://github.com/gridsome/gridsome/issues/78)) ([001aa0b](https://github.com/gridsome/gridsome/commit/001aa0b))
* **router:** custom fields as params ([#53](https://github.com/gridsome/gridsome/issues/53)) ([f53f67f](https://github.com/gridsome/gridsome/commit/f53f67f))
* **webpack:** runtimeCompiler config ([cdb676f](https://github.com/gridsome/gridsome/commit/cdb676f))
* **webpack:** transpileDependencies config ([36e4932](https://github.com/gridsome/gridsome/commit/36e4932))





<a name="0.3.6"></a>
## [0.3.6](https://github.com/gridsome/gridsome/compare/gridsome@0.3.5...gridsome@0.3.6) (2018-12-10)


### Bug Fixes

* **graphql:** dont infer filename as file type ([3a04df9](https://github.com/gridsome/gridsome/commit/3a04df9))
* **image:** exclude unecessary data ([574928c](https://github.com/gridsome/gridsome/commit/574928c))





<a name="0.3.5"></a>
## [0.3.5](https://github.com/gridsome/gridsome/compare/gridsome@0.3.4...gridsome@0.3.5) (2018-12-05)


### Bug Fixes

* **api:** pass graphql object to addSchemaField ([#64](https://github.com/gridsome/gridsome/issues/64)) ([f6fd2a8](https://github.com/gridsome/gridsome/commit/f6fd2a8))
* **build:** fix beforeProcessAssets hook name ([8eafe68](https://github.com/gridsome/gridsome/commit/8eafe68))
* **favicon:** set mime type for icons in head ([bface4d](https://github.com/gridsome/gridsome/commit/bface4d))
* **graphql:** do not use file type for urls ([fd14b44](https://github.com/gridsome/gridsome/commit/fd14b44))
* **graphql:** fix order argument for collections ([3e6a1fa](https://github.com/gridsome/gridsome/commit/3e6a1fa))
* **graphql:** get node by id ([ba83545](https://github.com/gridsome/gridsome/commit/ba83545))
* **graphql:** transform nested invalid field names ([5555354](https://github.com/gridsome/gridsome/commit/5555354))
* **touchicon:** use correct sizes when custom icon ([db1c349](https://github.com/gridsome/gridsome/commit/db1c349))





<a name="0.3.4"></a>
## [0.3.4](https://github.com/gridsome/gridsome/compare/gridsome@0.3.3...gridsome@0.3.4) (2018-11-22)


### Bug Fixes

* **graphql:** do not use file type if no extension ([3b1fb7c](https://github.com/gridsome/gridsome/commit/3b1fb7c))
* **webpack:** allow async chainWebpack ([a0caa84](https://github.com/gridsome/gridsome/commit/a0caa84))





<a name="0.3.3"></a>
## [0.3.3](https://github.com/gridsome/gridsome/compare/gridsome@0.3.2...gridsome@0.3.3) (2018-11-16)


### Bug Fixes

* re-create routes after a node.path change ([b6e16c9](https://github.com/gridsome/gridsome/commit/b6e16c9))





<a name="0.3.2"></a>
## [0.3.2](https://github.com/gridsome/gridsome/compare/gridsome@0.3.1...gridsome@0.3.2) (2018-11-16)


### Bug Fixes

* **graphql:** merge nested object fields ([f2e9d4a](https://github.com/gridsome/gridsome/commit/f2e9d4a))
* **webpack:** absolute path to 404 fallback ([97e5e36](https://github.com/gridsome/gridsome/commit/97e5e36)), closes [#43](https://github.com/gridsome/gridsome/issues/43)
* **webpack:** load local babel config files ([975bfea](https://github.com/gridsome/gridsome/commit/975bfea))





<a name="0.3.1"></a>
## [0.3.1](https://github.com/gridsome/gridsome/compare/gridsome@0.3.0...gridsome@0.3.1) (2018-11-14)


### Bug Fixes

* **graphql:** get sub fields from object fields ([039a532](https://github.com/gridsome/gridsome/commit/039a532))
* **graphql:** return correct dates ([1965091](https://github.com/gridsome/gridsome/commit/1965091))
* **ssr:** render body scripts from vue-meta ([b4b50bd](https://github.com/gridsome/gridsome/commit/b4b50bd))
* **webpack:** run chainWebpack after all plugins ([2cc5850](https://github.com/gridsome/gridsome/commit/2cc5850))





<a name="0.3.0"></a>
# [0.3.0](https://github.com/gridsome/gridsome/compare/gridsome@0.2.5...gridsome@0.3.0) (2018-11-11)


### Bug Fixes

* clear errors in terminal when resolved ([832e7de](https://github.com/gridsome/gridsome/commit/832e7de))
* dont fail when missing favicon.png ([829091b](https://github.com/gridsome/gridsome/commit/829091b))
* handle urls in process queue ([60623ee](https://github.com/gridsome/gridsome/commit/60623ee))
* **image:** render fallback as html string ([738ef23](https://github.com/gridsome/gridsome/commit/738ef23))
* **store:** warn and skip when duplicate path detected ([215b3e9](https://github.com/gridsome/gridsome/commit/215b3e9))
* keep hash when resolving raw html links ([87860ab](https://github.com/gridsome/gridsome/commit/87860ab))
* lazy load external image urls ([4f7f867](https://github.com/gridsome/gridsome/commit/4f7f867))
* send context to transformer ([7b50bae](https://github.com/gridsome/gridsome/commit/7b50bae))
* send graphql to createSchema api ([86363c3](https://github.com/gridsome/gridsome/commit/86363c3))
* update routes when source path changes ([85171cf](https://github.com/gridsome/gridsome/commit/85171cf))


### Features

* addReference and addSchemaField ([c159ee5](https://github.com/gridsome/gridsome/commit/c159ee5))
* build hooks ([32774f0](https://github.com/gridsome/gridsome/commit/32774f0))
* cleaner graphql schema ([#31](https://github.com/gridsome/gridsome/issues/31)) ([98420a2](https://github.com/gridsome/gridsome/commit/98420a2))
* client plugin api ([caa6a17](https://github.com/gridsome/gridsome/commit/caa6a17))
* copy linked files ([7dd26f2](https://github.com/gridsome/gridsome/commit/7dd26f2))
* plugin api ([7a7889b](https://github.com/gridsome/gridsome/commit/7a7889b))
* **contentful:** use new plugin api ([eaf6092](https://github.com/gridsome/gridsome/commit/eaf6092))
* **graphql:** createSchema api [wip] ([c5d6d6b](https://github.com/gridsome/gridsome/commit/c5d6d6b))
* **graphql:** date field type ([d9f8335](https://github.com/gridsome/gridsome/commit/d9f8335))
* **graphql:** file type ([05f6c98](https://github.com/gridsome/gridsome/commit/05f6c98))
* **graphql:** image arguments ([e38b243](https://github.com/gridsome/gridsome/commit/e38b243))
* **graphql:** image type ([#25](https://github.com/gridsome/gridsome/issues/25)) ([316c91d](https://github.com/gridsome/gridsome/commit/316c91d))
* **graphql:** merge third party schemas ([1f33169](https://github.com/gridsome/gridsome/commit/1f33169))
* resolve file paths ([#26](https://github.com/gridsome/gridsome/issues/26)) ([a4baf68](https://github.com/gridsome/gridsome/commit/a4baf68))
* store api ([15d1c97](https://github.com/gridsome/gridsome/commit/15d1c97))
* **store:** set content and excerpt on node ([43c4236](https://github.com/gridsome/gridsome/commit/43c4236))
* support local plugins ([#22](https://github.com/gridsome/gridsome/issues/22)) ([568207f](https://github.com/gridsome/gridsome/commit/568207f))





<a name="0.2.5"></a>
## [0.2.5](https://github.com/gridsome/gridsome/compare/gridsome@0.2.4...gridsome@0.2.5) (2018-10-30)


### Bug Fixes

* prioritize static files ([6326958](https://github.com/gridsome/gridsome/commit/6326958))
* **image:** add more attributes to markup ([5c5052d](https://github.com/gridsome/gridsome/commit/5c5052d))
* send context to transofmers ([0b5840e](https://github.com/gridsome/gridsome/commit/0b5840e))


<a name="0.2.4"></a>
## [0.2.4](https://github.com/gridsome/gridsome/compare/gridsome@0.2.3...gridsome@0.2.4) (2018-10-22)


### Bug Fixes

* **build:** clear cached data files ([909caa0](https://github.com/gridsome/gridsome/commit/909caa0))
* **build:** use correct path for pagination ([e8a642c](https://github.com/gridsome/gridsome/commit/e8a642c))


<a name="0.2.3"></a>
## [0.2.3](https://github.com/gridsome/gridsome/compare/gridsome@0.2.2...gridsome@0.2.3) (2018-10-20)


### Bug Fixes

* don’t create routes for missing content types ([9eb216e](https://github.com/gridsome/gridsome/commit/9eb216e))
* **image:** send quality attr to worker ([4fd5151](https://github.com/gridsome/gridsome/commit/4fd5151))


<a name="0.2.2"></a>
## [0.2.2](https://github.com/gridsome/gridsome/compare/gridsome@0.2.1...gridsome@0.2.2) (2018-10-17)


### Bug Fixes

* forward slash component file path ([5c8e0d6](https://github.com/gridsome/gridsome/commit/5c8e0d6))
* hot reload page-query in windows ([f1ab80a](https://github.com/gridsome/gridsome/commit/f1ab80a))
* make paths in loaders work in windows ([7e27ca1](https://github.com/gridsome/gridsome/commit/7e27ca1))


<a name="0.2.1"></a>
## [0.2.1](https://github.com/gridsome/gridsome/compare/gridsome@0.2.0...gridsome@0.2.1) (2018-10-16)


### Bug Fixes

* ensure cache dir exists ([f243338](https://github.com/gridsome/gridsome/commit/f243338))
* use correct paths on windows ([fd624df](https://github.com/gridsome/gridsome/commit/fd624df))


<a name="0.2.0"></a>
# [0.2.0](https://github.com/gridsome/gridsome/compare/gridsome@0.1.2...gridsome@0.2.0) (2018-10-15)


### Bug Fixes

* **app:** use pathPrefix option ([7edfb79](https://github.com/gridsome/gridsome/commit/7edfb79))
* **build:** adjustments for better render times ([290e92d](https://github.com/gridsome/gridsome/commit/290e92d))
* **build:** check if static dir exists ([e42ca05](https://github.com/gridsome/gridsome/commit/e42ca05))
* **build:** keep leading slash for paged paths ([a2abccc](https://github.com/gridsome/gridsome/commit/a2abccc))
* **build:** show error stack form render failures ([5ba558e](https://github.com/gridsome/gridsome/commit/5ba558e))
* freeze base config object to prevent changes ([5fad26f](https://github.com/gridsome/gridsome/commit/5fad26f))
* replace path prefix correctly in links ([90dc133](https://github.com/gridsome/gridsome/commit/90dc133))
* **build:** use correct manifest path ([7a204be](https://github.com/gridsome/gridsome/commit/7a204be))
* **develop:** exclude dev middleware for playground route ([cff46b9](https://github.com/gridsome/gridsome/commit/cff46b9))
* **graphql:** hot reload page-query changes ([017aa95](https://github.com/gridsome/gridsome/commit/017aa95))
* **image:** hot reload after changes ([b4d83e7](https://github.com/gridsome/gridsome/commit/b4d83e7)), closes [#3](https://github.com/gridsome/gridsome/issues/3)
* **webpack:** page data importer in separate chunk ([34b8244](https://github.com/gridsome/gridsome/commit/34b8244))


### Features

* dir for static files ([4185564](https://github.com/gridsome/gridsome/commit/4185564))


<a name="0.1.2"></a>
## [0.1.2](https://github.com/gridsome/gridsome/compare/gridsome@0.1.1...gridsome@0.1.2) (2018-09-27)


### Bug Fixes

* show system info at startup ([de9793e](https://github.com/gridsome/gridsome/commit/de9793e))
* stop worker if any errors ([9890a26](https://github.com/gridsome/gridsome/commit/9890a26))
* **build:** better error if render fails ([7158300](https://github.com/gridsome/gridsome/commit/7158300))
* **build:** dont prefetch data chunks ([46e80a4](https://github.com/gridsome/gridsome/commit/46e80a4))
* **build:** output paths for html and data ([d167e8e](https://github.com/gridsome/gridsome/commit/d167e8e))
* **critical:** use htmlOutput ([c2c9670](https://github.com/gridsome/gridsome/commit/c2c9670))
* **webpack:** alias to gridsome app ([3891e87](https://github.com/gridsome/gridsome/commit/3891e87))


<a name="0.1.1"></a>
## [0.1.1](https://github.com/gridsome/gridsome/compare/gridsome@0.1.0...gridsome@0.1.1) (2018-09-26)


### Bug Fixes

* **cli:** show stack when failing ([7507051](https://github.com/gridsome/gridsome/commit/7507051))
* **data:** strip trailing slash before import ([35fc653](https://github.com/gridsome/gridsome/commit/35fc653))
* **renderer:** protect agains failing ssr vue-meta ([c9ad300](https://github.com/gridsome/gridsome/commit/c9ad300))


<a name="0.1.0"></a>
# [0.1.0](https://github.com/gridsome/gridsome/compare/gridsome@0.0.6...gridsome@0.1.0) (2018-09-26)


### Bug Fixes

* **app:** dont sanitize inline styles and scripts ([eaac209](https://github.com/gridsome/gridsome/commit/eaac209))
* **babel:** dont load config files ([c891593](https://github.com/gridsome/gridsome/commit/c891593))
* **cli:** stop if not in a gridsome dir ([8c29072](https://github.com/gridsome/gridsome/commit/8c29072))
* **graphql:** dont run empty page query ([9cc7176](https://github.com/gridsome/gridsome/commit/9cc7176))
* **image:** dont add lazy class when no srcset ([f3e4257](https://github.com/gridsome/gridsome/commit/f3e4257))
* **image:** init observer in client only ([4c4dad9](https://github.com/gridsome/gridsome/commit/4c4dad9))
* **image:** re-observe after hot-reload ([dfeeb90](https://github.com/gridsome/gridsome/commit/dfeeb90))


### Features

* GRIDSOME_MODE env variable ([561e72c](https://github.com/gridsome/gridsome/commit/561e72c))
* **app:** send isServer and isClient to main.js ([fe01c8e](https://github.com/gridsome/gridsome/commit/fe01c8e))
* **cli:** gridsome serve ([a91c7fc](https://github.com/gridsome/gridsome/commit/a91c7fc))
* **env:** rename to isClient and isServer ([90880c6](https://github.com/gridsome/gridsome/commit/90880c6))
* **graphql:** rename graphql block to page-query ([8bf5e1a](https://github.com/gridsome/gridsome/commit/8bf5e1a))
* **image:** generate blured inline svg ([bd54dfe](https://github.com/gridsome/gridsome/commit/bd54dfe))


<a name="0.0.6"></a>
## [0.0.6](https://github.com/gridsome/gridsome/compare/gridsome@0.0.5...gridsome@0.0.6) (2018-09-18)


### Bug Fixes

* **worker:** set jpeg quality ([31f8929](https://github.com/gridsome/gridsome/commit/31f8929))


<a name="0.0.5"></a>
## [0.0.5](https://github.com/gridsome/gridsome/compare/gridsome@0.0.4...gridsome@0.0.5) (2018-09-18)


### Bug Fixes

* **app:** prevent duplicate router.push ([508dd58](https://github.com/gridsome/gridsome/commit/508dd58))
* **image:** resize by width attribute + test ([7ac63a7](https://github.com/gridsome/gridsome/commit/7ac63a7))
* **worker:** resize images correctly ([61d2e74](https://github.com/gridsome/gridsome/commit/61d2e74))


### Features

* **app:** browser field in package json ([3e87581](https://github.com/gridsome/gridsome/commit/3e87581))
* **app:** gen favicon and touchicon sizes [#4](https://github.com/gridsome/gridsome/issues/4) ([3448301](https://github.com/gridsome/gridsome/commit/3448301))
* **webpack:** alias ~ to src dir ([81c1a5f](https://github.com/gridsome/gridsome/commit/81c1a5f))


<a name="0.0.4"></a>
## [0.0.4](https://github.com/gridsome/gridsome/compare/gridsome@0.0.3...gridsome@0.0.4) (2018-09-17)

**Note:** Version bump only for package gridsome


<a name="0.0.3"></a>
## [0.0.3](https://github.com/gridsome/gridsome/compare/142896c2454016dc989a7872faffec7263fc658c...gridsome@0.0.3) (2018-09-17)


### Bug Fixes

* webpack progress in tty only ([bab7e8a](https://github.com/gridsome/gridsome/commit/bab7e8a))



<a name="0.0.2"></a>
## [0.0.2](https://github.com/gridsome/gridsome/compare/142896c2454016dc989a7872faffec7263fc658c...gridsome@0.0.3) (2018-09-16)


### Bug Fixes

* add local bin to core package ([0bab302](https://github.com/gridsome/gridsome/commit/0bab302))
