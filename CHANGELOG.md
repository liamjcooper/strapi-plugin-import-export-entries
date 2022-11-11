# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [1.18.2](https://github.com/Baboo7/strapi-plugin-import-export-entries/compare/v1.18.1...v1.18.2) (2022-11-11)

### 1.18.1 (2022-11-11)


### 🐞 Bug Fixes

* application/vnd.ms-excel not supported. ([2ff0804](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/2ff0804b33379ba29c3cc2a8c8b9e68882d33051))
* **convert-data:** Export all entity attributes ([edd8a18](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/edd8a18a65ef2dec5fecd607867843e202c756c4))
* **convert-data:** Export relations as id ([bb0e540](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/bb0e540755bbc24fab5e9dd2332cf709fddb7625))
* **convert-data:** Stringify objects when export in csv ([b2106bc](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/b2106bcc01b9c072b907b5cb233728416f86575d))
* Define const ([1cd1585](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/1cd1585c269a73a1ec04366b1d66303bb6629901))
* **doc:** Make relations import clearer ([cf88780](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/cf887805be3f8194f8c86763e0e14607c0ecb7cb))
* **doc:** Set anchor to section ([435b5f9](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/435b5f9b8b3b34166d35d755ac64184ac50a01ff))
* **Editor:** Load monaco editor locally ([6bf1e15](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/6bf1e1594fb58fb068bff04a6bfc64288d88da77))
* **eslint:** Add jest config ([8f2d37c](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/8f2d37c63be61c2443b8d834a56e5359327b783b))
* **export-v2:** Export components for simple single and collection types ([c954791](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/c9547913b4699da87fac2f5d16345a59669600f7))
* **export-v2:** Export single type localized ([09dc3cc](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/09dc3ccaac27921c6c5f2c9fc822886784c3eaf3))
* **export:** Adapt sort query to entity service ([94c77eb](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/94c77eb02aeff92d0c60d9bc8848944ac72bfee3))
* **export:** Apply filters fix, replaceAll replaced with replace method for CSV conversion ([696254d](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/696254d5ce4f1432e31ab0bed06d76cb9070b46a))
* **export:** Export dynamic zone ([635dc72](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/635dc724cad3652ecb8db6fd22faead815464d11))
* **export:** Handle export relations as ids for one to many relations ([44f25b5](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/44f25b5ccd46ae60c28e32eb480b38411291379b))
* **export:** Handle null when export relations as id ([b01d246](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/b01d2460f10b4768389736b2ff3a722b7c4ea69c))
* **export:** Sub populate seo component ([ab5d227](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/ab5d227bffa0592bce855ebdc7ce2d655edaf55e))
* **file:** Set empty caption and alternative text ([b9ad57c](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/b9ad57c4dfc645ac6707e7e9a9961080eb3d6aa9))
* **file:** Set right file name ([113fed1](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/113fed10f9df8822fe94ddd6979ea3eb2b2a60d4))
* Have component export/import compatible with entity service ([5006837](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/5006837327e63fd48322a177a63ee7aab5d8f1bb))
* **import-v2:** Fail when missing required field ([fda6ca2](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/fda6ca2c856a29cb88f1d93ba08925b3bd71b989))
* **import-v2:** Import collection types localized ([4a2c913](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/4a2c9131a27e1c3f3e0175cc3aa25cf7751014f3))
* **import-v2:** Import single type ([35b54c5](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/35b54c5d4ec730f9159059589a0ba1c522b36565))
* **import-v2:** Import single type with specified id ([1e66da1](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/1e66da1a4500f20acd27d17b4ad2c66d6d806cbf))
* **import-v2:** Set components for simple single and collection types ([366461f](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/366461f6c548cc808d2a0fd4823c333e58d08d99))
* **import-v2:** Sync primary key sequence for postgres database ([5220b64](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/5220b6456169be6357c2e092cec13c0e4f8c310a))
* **ImportEditor:** Make import options more obvious ([e13fa70](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/e13fa70b72d50fa451c4faa54bc127cf89e316c9))
* **import:** Handle import of one to many relations ([af6daab](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/af6daab950e71a3959d263c7d59981b6b92c6007))
* **import:** Import components and dynamic zones sequentially ([6d5f2f1](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/6d5f2f1f8ae13b5d067fb843d32b443c59bad3af))
* **import:** Import entries with dependencies ([413362b](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/413362bc141ca096b28e36601ab787e7961f3eaf))
* **import:** Import media ([c8f0aad](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/c8f0aad9d82c5951dd87739286ef49c435896a04))
* **import:** Import/Set media by id, url or object ([c85bfe2](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/c85bfe2c6a7999f540ab6c88021b477007b4bab2))
* **ImportModal:** Handle error payload too large ([2b0159f](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/2b0159f67d9d3ed4c178f2c1081c78a3339bde97))
* **import:** Support import of dynamic zones ([1ec2b04](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/1ec2b046aec5176f5741b9087bbe27f844b7b232))
* **import:** Support import of relations defined in any order ([9a481a5](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/9a481a58738c9f4c1554d8f4b1d8d2f561222e37))
* **import:** Use current admin user id for create/update fields ([fc0408a](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/fc0408ad3c772e44f7cad29bfd490a46b27a07b2))
* **README:** Update discord invite link ([4b1be2c](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/4b1be2c58a49b8a13610969ceb0218b4f983b63f))
* **test:** Await database cleanup ([f47fb89](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/f47fb891cea3edaf9e7713c1fcc69dcd95a2365f))
* Update plugin name ([20a4b6d](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/20a4b6dd2dbefefea2be200ada3fb7160c9ae785))
* Update request urls ([f27b3c9](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/f27b3c96769daa6b73ce0339017783e7335ad709))
* **utils:** Remove non existent exports ([6dfef02](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/6dfef02e78296dc484523028ef8b81c70c8be63f))


### 🛠 Refacto

* Create export content on server side ([bea392f](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/bea392fd56e6c91806d58caf3715a4b2763754c7))
* **data-converter:** Refacto to export service ([229a72d](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/229a72da253734223fb9f943af01755b855be5d3))
* **export-v2:** Move merge function to objects lib ([885d49e](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/885d49e6f14a628e3ac860e94c369e092c8ba146))
* **export:** Extend query safely ([04ba64e](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/04ba64ea49cecac1ffbd9802d363944705c141d7))
* **ExportModal:** Use preferences ([074e19f](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/074e19f716aac6048980687914a431d9e13506d0))
* **export:** Move populate from schema to service ([44d42ad](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/44d42ad9f76fb54ae65d5ecf733b44e3eb7028a0))
* **import-v2:** Find collection type entry before update ([ff6ef95](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/ff6ef95631f7cf8c9da1a03e76a54fbaebdca5cb))
* **import-v2:** Remove id field for single type ([0070693](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/007069377be471f11c629e199c34fa4ec6e2e480))
* **import-v2:** Rename variables ([a42dd13](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/a42dd13b67e079c3ac9a36ce909890f3830439c9))
* **import:** Create parser utils ([b63e9b8](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/b63e9b8d782b06ea28a6b89eaf7204992b1f18ad))
* **import:** Factorize slug in tests ([0edbccb](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/0edbccb86b6d8a176dd92fa9c21c8e8b16de1a00))
* **import:** Move import data endpoint to file ([c65cc8b](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/c65cc8b2418d0d7bfbfbc96154aea620ca42ea06))
* **import:** Remove catch error wrapper function ([b905897](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/b9058976b2566e97ea6ddd6be726d2f90bdd24df))
* **import:** Treat data of relation as immutable ([f9505b7](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/f9505b70623f759b73ca181cf045f1d25987d8c0))
* Rename files to kebab case ([753996a](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/753996ad08825ae9f59805bc4d542bfa9ce64281))
* Rename injected buttons component ([78d2d3d](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/78d2d3d0b39d80b7ec61485079b5bc8e6758b92c))
* **tests:** Auto require test files ([140e888](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/140e8886735ab6d59aba4a504158ada254affc6c))
* **tests:** Populate db where needed ([e263c6f](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/e263c6f4ccf4fdd12691aa943ae6aaaee64c4b7b))
* **tests:** Use shared slugs enum ([c2179a0](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/c2179a0e30a29451a3bc978509b15b7c0400636e))
* Update path of test database ([6ec2946](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/6ec294662568047464f4d41dfdfa0b42a21ee3f6))
* Use strapi model instead of db model ([cf5fee4](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/cf5fee4c4c9f88c6451cd04436d078d368973871))
* **useI18n:** Simplify translation ([cfb4de0](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/cfb4de0b76f18472d99fda709c7cdd1ce36773eb))
* **useSlug:** Get model slug only on collection and single type pages ([323de8d](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/323de8d5de6cdabfe70afd4f533333b68df8eb81))
* **utils:** Use jsdoc instead of enum ([36928f9](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/36928f9de70338919896839c784a12777b8e0c68))


### 🧪 Tests

* **collection-type:** Create localized collection type ([efa58f5](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/efa58f52f66b883d447bc7725a11b6cfa95eea83))
* **export-v2:** Should export collection type localized ([454e2d3](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/454e2d345b0cadaca40e69289a8db4e762ccc6ab))
* **export-v2:** Should export components for simple single and collection types ([c1e4528](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/c1e452841f68d3441caf560259e7a4b07ab53614))
* **export-v2:** Should export whole database ([7cab210](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/7cab210f31a3b9952de4ece2746f19a50812fe05))
* **export-v2:** Test export localizations of single type localized ([da8c434](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/da8c4344d104705e7eed5e3d226855eab57f0b8f))
* **export-v2:** Test export of single type localized ([0fd1b9e](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/0fd1b9e9c39f93d1fda62cf7c3a96f60d8dd5b03))
* Generate unique data ([22a26e5](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/22a26e5066383380e1fded3b925d66313e6fa235))
* **import-v2:** Should create or update standalone components ([97fb6b1](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/97fb6b140345caa0b412f7e8f696b93731fcc349))
* **import-v2:** Should fail to import when missing required field ([b4407c0](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/b4407c0e8036881d458fb9c5d0303c8790454bf3))
* **import-v2:** Should import collection type localized ([32f552a](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/32f552a9954e0c8c9af5778a4621b1fb4bae072c))
* **import-v2:** Should set components for simple single and collection types ([372f1e4](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/372f1e4a437ed7b0dc5965bf1c821c9b92cf644d))
* **import-v2:** Should update partially single types localized ([4618509](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/4618509adda06e08f58f95741ec3fce778a5c380))
* **import-v2:** Test import of single type ([6092b67](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/6092b67c6088d86e660a6194bee679c9323be0bb))
* **import-v2:** Test partial update of collection type ([3a2e8b3](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/3a2e8b393936846b13bb583e0b5d701d5a18b4fd))
* **import:** Comment limitation about single type localized ([a5576c1](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/a5576c1897cb1435e31ad35ceff949b994e7e225))
* **import:** Import single and collection types ([3f068dd](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/3f068dd8ae8ddca8255bafd2a0b83ea80696455a))
* **import:** Should create or update single type ([6aad02e](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/6aad02e1e6c3b3b5f70391294f8d95f1a51bb600))
* **import:** Should import relations in any order ([9ffaad0](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/9ffaad0b4340ec5e8d708596c618c29a96171b28))
* **strapi:** Cleanup components ([b86edaa](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/b86edaaee3046310acfb20ccbc96856a4c77ad78))


### ⚡️ Features

* **admin:** Display plugin homepage ([75b2569](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/75b25698fca9e119e4616f2157787f8246e799d5))
* Create endpoints to import/export data from content api ([5b3445e](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/5b3445ef78cb34204511d090bd267574eef03aff))
* **doc:** Add section about filtering and sorting exported data ([86e26cf](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/86e26cf96f946ad9eae55ead3a4cb5335baedc49))
* **doc:** Detail how to import media programmatically ([4297ce0](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/4297ce0ee4cf039178164ef66b7d74409cbf860b))
* **doc:** Update section to import media ([9fd57e2](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/9fd57e2df76cc3c56d6386fdb5c96d1accbfdd67))
* **export-v2:** Export locales ([103bfd6](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/103bfd655daddeff77d63f13d76bebfc826c708c))
* **export-v2:** Export single type ([6c3e54b](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/6c3e54bc417e6dc7b39e2afb732d32aa43744b2e))
* **export-v2:** Export whole database ([31e706a](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/31e706afcf5e6c7fe9207b22572bb4acfb24a856))
* **export:** Add deepness option ([71413a1](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/71413a13cf6317c0e48aa3e3aac120d8a26a16ab))
* **export:** Enable use of version 2 ([d9914eb](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/d9914eb29cd3789b839e7ddcec42f79fd5161a14))
* **export:** Export media with absolute url ([0f3cc9b](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/0f3cc9b783a1f40aa290e9f6bbc644193892bfee))
* **export:** Export relations as id ([c8f4955](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/c8f4955cc5357f4d0184bc3eaed349cf7019f32c))
* **export:** Export single types ([8d5fea1](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/8d5fea1a1b9e9b3d44e0f4f4622ea308bce9bf87))
* **export:** Implement v2 ([dbef311](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/dbef3110e375714532d3f89de5f2b3573f217438))
* **ExportModal:** Mark csv export as deprecated ([fbc64db](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/fbc64dbc4f691c1ca81e067b1b1c810cfefa2cb3))
* **ExportModal:** Set json v2 as default export format ([3783185](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/378318573d6fade3a2bb9fe9dc903da1a94db84d))
* **export:** Parametrize export deepness ([bba4fac](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/bba4face6215b9e8e962a04968a70bb7d1cf25c8))
* **export:** Support deepness when export from content-api ([91f12de](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/91f12de78067585adbe90ddf65cf054754ec3119))
* **export:** Support programmatic media export ([79dca02](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/79dca0226f8e7010897d70a517936a26c69b23bf))
* Expose import logic in service ([7b575b9](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/7b575b93a24b94e2b8a5f7c0a1c2e6767e977daf))
* **file:** Import with metadata ([8dafa56](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/8dafa5690c6dee3392c10ab3a43548ebb6c46592))
* **file:** Set id of imported file ([ad4ea5d](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/ad4ea5dd71222e4b80fad8bd9f94a71791149cb8))
* **HomePage:** Add help section ([fa08af1](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/fa08af17078508a374730d1c49bb9b16ee9fd36a))
* **HomePage:** Setup basic layout ([022b363](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/022b363323862a778cb89f3b5fed8abef3338158))
* Import / export data according to user permissions ([6aee52d](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/6aee52d795aea6fcc99a869e67e7933347d56847))
* **import:** Enable use of v2 ([1494612](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/149461229a1c319742cae227d24c0b72f155f9de))
* **import:** Implement v2 ([568a0a8](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/568a0a86e96a24028a1f8454c964dd8d0b500d28))
* **import:** Import single type ([dcc5cae](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/dcc5cae627e100032c1797dec8d40f3653ef04e8))
* **ImportModal:** Display sucess/partial failure states ([083ab31](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/083ab3192502806fe9626cc1dad56a1ce8e8537f))
* **ImportModal:** Refresh view on import success ([602a4d3](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/602a4d3c6a88859301939765b38cf2822acb6052))
* **import:** Select field used as identifier ([638115c](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/638115ce4df3012b5fa405a85d4838cdfc7e2022))
* **import:** Support programmatic media import ([4da97e6](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/4da97e6b10d679cf9af4b65cc108f9ffd82e571c))
* Inject import/export buttons into single type edit page ([105b088](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/105b088edfc8fafff91f285e5c395ed2a522a1ce))
* **package.json:** Enable plugin for node 18 ([eb532cf](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/eb532cf6965b01a104ceb93169d8ea7cb86ddb24))
* **package:** Define files to pack ([a3d32ec](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/a3d32ec51c3ddf76808a58742d1f3b05d4c0b946))
* **README:** Add contribute section ([bfabc11](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/bfabc11d4a1973924e9fb3e1c2121b95ca0196e5))
* **README:** Add feedback and related plugin sections ([3117c99](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/3117c99d96fe76134bd3a9d616bf82c47482cd01))
* **README:** Detail json v2 file structure ([91eda48](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/91eda48eadafe3dfbe96557721d98f2ba7b466cc))
* Setup tests ([8d044cf](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/8d044cf1e53a12f7c193c54e4e46855606c015bc))
* Test export v2 of single and collection types ([939a3c2](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/939a3c2b51428962bfc736c05ae746e51f43c2dd))
* **test:** Setup database before tests ([931566d](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/931566d7ce2d329601afd5a8870a141d16744826))
* **test:** Test export of single type ([0d2f052](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/0d2f052df8470eac9a28c88276fd47fed827692c))


### 🧹 Chores

* Add github CI ([d2f24cf](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/d2f24cf713b9cce0931dd5addffc6c523ac81896))
* **Alerts:** Clean imports ([252c09f](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/252c09fb0054e4c0a2da455df0b83cae8ac07dba))
* **CHANGELOG.md:** Lint ([cc77582](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/cc775825c7aea32d3978ac86a2920be79e12196b))
* **CHANGELOG.md:** Prettify ([22eb453](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/22eb4532e0e957d16b957d4216f933b44918235b))
* Clean code ([0c6ff42](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/0c6ff42e709487fa43d29ed1e5cbbda5fff06ab1))
* **dependencies:** Update ([dde8767](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/dde87674559f827ac516f3ea08aad56b806e190e))
* **doc:** Add feature ([37a01cb](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/37a01cb8929cc14ed47688abcc98e3a4ff65733f))
* **doc:** Add import example in usage section ([b9a4a18](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/b9a4a18d71d97dd563d69d816fc5d5211651e4bc))
* **doc:** Add screenshots ([194364e](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/194364e7565d7acd8548b92fb45e3baa34947d8c))
* **doc:** Add webhook section ([1fe7db6](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/1fe7db6845be918e32b7f3779efa28f72636d381))
* **doc:** Clarify plugin description ([0e0c6e5](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/0e0c6e5fe0d01c6d8803d35cea24b2a928b58559))
* **doc:** Create content api section ([5592a21](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/5592a21ee950edab49e6934135cc3b2afc5c0e94))
* **doc:** Describe how to solve the Payload too large error ([7eb3511](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/7eb3511aa4f16e827d3a4fef60cedf24e5b932ca))
* **doc:** Explain how to export whole database and setup preferences ([045c17b](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/045c17be383b8b43120a7f055f79b5e9b82555a5))
* **doc:** Explain how to import data ([fa462bc](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/fa462bc757a88b3de898c9851d829ba0a477ec2c))
* **doc:** Improve ([6fea3ee](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/6fea3ee3ef7b8ce99392ce7dafcfd04190e2c9cb))
* **doc:** Move features to the top ([a648096](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/a648096ee91f221491212b622067df9686f65e99))
* **doc:** Tweak ([981354d](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/981354d554a23156b221cd0f8550f36455ec0584))
* **doc:** Udpdate known limitations section ([e0e95ff](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/e0e95ff75b4c49486b0daa463668b1f521d06e14))
* **doc:** Update ([c160751](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/c160751c4927a80e9a1d12eefd05f3eb234d5b88))
* **doc:** Update ([fca65c4](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/fca65c4d91ec17d540ee371169925716471d3f31))
* **doc:** Update ([aa34ff6](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/aa34ff636dc6b54538fec74426acbd0e62a7649f))
* **doc:** Update config section ([af55ae4](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/af55ae41bbe8bd02a68664d1d69f043a217ebbfc))
* **doc:** Update import data section ([f84ac7e](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/f84ac7edb234f6f8a88ca521afb622ecb3be8939))
* **doc:** Update installation process ([9f71a53](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/9f71a5338cea53cf0b7f99a9213795b530788e2b))
* **doc:** Update installation section ([df9b8ee](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/df9b8ee4b95c473625f34466c0a73b9bbb57430f))
* **Editor:** Increase size ([de886da](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/de886dab2e5c1d4e9360042f9ad600d7002af4b4))
* **eslint:** Sort imports ([140ac0e](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/140ac0e310f07c57c920e5954628e73bbd93c896))
* **ExportModal:** Clean imports ([d3d91c8](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/d3d91c85076d8ac19cc88eb09044295d18f6e0e1))
* **ExportModal:** Update wording ([242ef0f](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/242ef0f87fc0a8d7fdcef1152b9f373d5aef27d2))
* Generate lock file ([d952282](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/d95228233b184d7389663b37ea8558f2f1c2ca58))
* **git:** Update gitignore ([55c3145](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/55c31458e40587bec72b77469cdafaf13437cb9a))
* **husky:** Send back to APA ([efbb795](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/efbb79554b0999c24dfbf9c3ba100dba29b24b90))
* **husky:** Setup husky ([dcfbb35](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/dcfbb35eb53b649704f719c86436d5cbddf03277))
* **import:** Improve doc ([14a8abe](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/14a8abea3841c0a68116aa10ad9235915c338d04))
* **libs:** Create method to check if object empty ([22b400f](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/22b400f72b0c113bfc4fd686f2f0562e13a013dc))
* Lint files ([acf9b0a](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/acf9b0a005bf82b76ae5c49161d6d2577474c598))
* Lint project ([d4bd0a9](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/d4bd0a9d20f48dc354b6e6b2e670731ed13a3cf3))
* Lint project ([ea58c99](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/ea58c99592b0bac2c3456ee0e664239503984f11))
* Lint project ([335dfed](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/335dfed396be0a8884f714ced69241add0ee7f95))
* **lint:** Configure linter and prettier ([4f250af](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/4f250af7f3491bcb63b2e38bbc6dbdfb29e9ff84))
* Log error when import fails ([050a1b3](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/050a1b35e714774a98edb502745d2886479cdb11))
* **objects:** Create helper to log objects ([370fc37](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/370fc37abfa3e893be58791c79e084dbc1277dbb))
* **package-lock.json:** Update node engine ([1dfff19](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/1dfff19112c25a85635b1afc5b8cc171f411a89b))
* **package:** Add standard version ([24739b1](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/24739b11af04019ec9684db0805c80f4c56f08fd))
* **package:** Update plugin description ([10395a6](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/10395a6e442ae6571772cee07979053fa673c3bf))
* **README.md:** Add section about known limitations ([2fcfeae](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/2fcfeaec58442d94caccf940d92d1b906381caaa))
* **README:** Fix typo ([d3de155](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/d3de155928acc55730c72659a89a2876cf5b7747))
* **README:** Update wording ([87536ef](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/87536ef83c3d89889e73bdec28ae09d8b9d4b475))
* **release:** 1.17.0 ([80d134b](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/80d134b591d76356696c0b01c082a2d6ab2cb66d))
* **release:** 1.17.1 ([3c6e0b8](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/3c6e0b8d2a1f56440606f2e2733c26a9bdaef49e))
* **release:** 1.17.2 ([425dc77](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/425dc77dc98e27b71a9ecf64e9179075d9749df0))
* **release:** 1.17.3 ([01b356f](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/01b356ffeb15d3f922aa6dedd5aeb4952b5f62b0))
* **release:** 1.18.0 ([44112f2](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/44112f2aa780743694ae922cc9c73e15d0545007))
* Set node version ([6495c11](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/6495c118b49df88eaf1e1de772626839e8f18d5d))
* Set plugin display name ([9d6a801](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/9d6a801537f64fc012564cd0ade3b3274caf9b27))
* **test:** Load strapi plugins ([f43609b](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/f43609bac660134e621d9cf1b461dfa5552024df))
* **tests:** Clean test app ([5244713](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/5244713f37e1b0ed4de6cebb49d4cfa189e905aa))
* Update issue templates ([93756f0](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/93756f00f662adb787da83d3f7fd32d5eb56b5a2))
* Use npm ([d2c39e1](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/d2c39e116a97c66f5968fafa6649cb6596f7a68d))

## [1.18.0](https://github.com/Baboo7/strapi-plugin-import-export-entries/compare/v1.17.3...v1.18.0) (2022-11-05)

### ⚡️ Features

- **admin:** Display plugin homepage ([75b2569](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/75b25698fca9e119e4616f2157787f8246e799d5))
- **export-v2:** Export whole database ([31e706a](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/31e706afcf5e6c7fe9207b22572bb4acfb24a856))
- **HomePage:** Add help section ([fa08af1](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/fa08af17078508a374730d1c49bb9b16ee9fd36a))
- **HomePage:** Setup basic layout ([022b363](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/022b363323862a778cb89f3b5fed8abef3338158))

### 🧪 Tests

- **export-v2:** Should export whole database ([7cab210](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/7cab210f31a3b9952de4ece2746f19a50812fe05))

### 🧹 Chores

- **CHANGELOG.md:** Lint ([cc77582](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/cc775825c7aea32d3978ac86a2920be79e12196b))
- **doc:** Explain how to export whole database and setup preferences ([045c17b](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/045c17be383b8b43120a7f055f79b5e9b82555a5))
- **doc:** Udpdate known limitations section ([e0e95ff](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/e0e95ff75b4c49486b0daa463668b1f521d06e14))
- **eslint:** Sort imports ([140ac0e](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/140ac0e310f07c57c920e5954628e73bbd93c896))
- **husky:** Send back to APA ([efbb795](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/efbb79554b0999c24dfbf9c3ba100dba29b24b90))
- Lint project ([d4bd0a9](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/d4bd0a9d20f48dc354b6e6b2e670731ed13a3cf3))

### 🛠 Refacto

- **ExportModal:** Use preferences ([074e19f](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/074e19f716aac6048980687914a431d9e13506d0))
- **useSlug:** Get model slug only on collection and single type pages ([323de8d](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/323de8d5de6cdabfe70afd4f533333b68df8eb81))

### [1.17.3](https://github.com/Baboo7/strapi-plugin-import-export-entries/compare/v1.17.2...v1.17.3) (2022-10-30)

### 🧹 Chores

- **git:** Update gitignore ([55c3145](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/55c31458e40587bec72b77469cdafaf13437cb9a))
- **husky:** Setup husky ([dcfbb35](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/dcfbb35eb53b649704f719c86436d5cbddf03277))

### 🧪 Tests

- **export-v2:** Should export components for simple single and collection types ([c1e4528](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/c1e452841f68d3441caf560259e7a4b07ab53614))
- Generate unique data ([22a26e5](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/22a26e5066383380e1fded3b925d66313e6fa235))
- **import-v2:** Should create or update standalone components ([97fb6b1](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/97fb6b140345caa0b412f7e8f696b93731fcc349))
- **import-v2:** Should set components for simple single and collection types ([372f1e4](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/372f1e4a437ed7b0dc5965bf1c821c9b92cf644d))
- **strapi:** Cleanup components ([b86edaa](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/b86edaaee3046310acfb20ccbc96856a4c77ad78))

### 🐞 Bug Fixes

- **export-v2:** Export components for simple single and collection types ([c954791](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/c9547913b4699da87fac2f5d16345a59669600f7))
- **import-v2:** Set components for simple single and collection types ([366461f](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/366461f6c548cc808d2a0fd4823c333e58d08d99))

### [1.17.2](https://github.com/Baboo7/strapi-plugin-import-export-entries/compare/v1.17.1...v1.17.2) (2022-10-30)

### 🧹 Chores

- **package-lock.json:** Update node engine ([1dfff19](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/1dfff19112c25a85635b1afc5b8cc171f411a89b))

### 🐞 Bug Fixes

- **import-v2:** Import collection types localized ([4a2c913](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/4a2c9131a27e1c3f3e0175cc3aa25cf7751014f3))

### 🛠 Refacto

- **import:** Factorize slug in tests ([0edbccb](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/0edbccb86b6d8a176dd92fa9c21c8e8b16de1a00))

### 🧪 Tests

- **collection-type:** Should create localized collection type ([efa58f5](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/efa58f52f66b883d447bc7725a11b6cfa95eea83))
- **export-v2:** Should export collection type localized ([454e2d3](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/454e2d345b0cadaca40e69289a8db4e762ccc6ab))
- **import-v2:** Should import collection type localized ([32f552a](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/32f552a9954e0c8c9af5778a4621b1fb4bae072c))
- **import-v2:** Should update partially single types localized ([4618509](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/4618509adda06e08f58f95741ec3fce778a5c380))

### [1.17.1](https://github.com/Baboo7/strapi-plugin-import-export-entries/compare/v1.17.0...v1.17.1) (2022-10-28)

### ⚡️ Features

- **package.json:** Enable plugin for node 18 ([eb532cf](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/eb532cf6965b01a104ceb93169d8ea7cb86ddb24))

### 🧪 Tests

- **import-v2:** Test partial update of collection type ([3a2e8b3](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/3a2e8b393936846b13bb583e0b5d701d5a18b4fd))

### 🐞 Bug Fixes

- **import-v2:** Sync primary key sequence for postgres database ([5220b64](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/5220b6456169be6357c2e092cec13c0e4f8c310a))

### 🛠 Refacto

- **import-v2:** Find collection type entry before update ([ff6ef95](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/ff6ef95631f7cf8c9da1a03e76a54fbaebdca5cb))
- **import-v2:** Remove id field for single type ([0070693](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/007069377be471f11c629e199c34fa4ec6e2e480))

### 🧹 Chores

- **README.md:** Add section about known limitations ([2fcfeae](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/2fcfeaec58442d94caccf940d92d1b906381caaa))

### [1.17.0](https://github.com/Baboo7/strapi-plugin-import-export-entries/compare/v1.16.2...v1.17.0) (2022-10-27)

### 🧹 Chores

- **package:** Add standard version ([24739b1](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/24739b11af04019ec9684db0805c80f4c56f08fd))
- **test:** Load strapi plugins ([f43609b](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/f43609bac660134e621d9cf1b461dfa5552024df))

### ⚡️ Features

- **ExportModal:** Mark csv export as deprecated ([fbc64db](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/fbc64dbc4f691c1ca81e067b1b1c810cfefa2cb3))
- **test:** Setup database before tests ([931566d](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/931566d7ce2d329601afd5a8870a141d16744826))

### 🐞 Bug Fixes

- **export-v2:** Export single type localized ([09dc3cc](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/09dc3ccaac27921c6c5f2c9fc822886784c3eaf3))
- **import-v2:** Import single type ([35b54c5](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/35b54c5d4ec730f9159059589a0ba1c522b36565))

### 🧪 Tests

- **export-v2:** Test export localizations of single type localized ([da8c434](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/da8c4344d104705e7eed5e3d226855eab57f0b8f))
- **export-v2:** Test export of single type localized ([0fd1b9e](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/0fd1b9e9c39f93d1fda62cf7c3a96f60d8dd5b03))
- **import-v2:** Test import of single type ([6092b67](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/6092b67c6088d86e660a6194bee679c9323be0bb))
- **import:** Comment limitation about single type localized ([a5576c1](https://github.com/Baboo7/strapi-plugin-import-export-entries/commits/a5576c1897cb1435e31ad35ceff949b994e7e225))
