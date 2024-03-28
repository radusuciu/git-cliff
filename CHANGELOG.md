[![animation](https://raw.githubusercontent.com/orhun/git-cliff/main/website/static/img/git-cliff-anim.gif)](https://git-cliff.org)

## [2.2.1](https://github.com/radusuciu/git-cliff/compare/v2.1.2..v2.2.1) - 2024-03-28

### ⛰️  Features

- *(changelog)* Make rendering errors more verbose - ([7ee3c86](https://github.com/radusuciu/git-cliff/commit/7ee3c860afac12238d37141566759c17b38ac594))
- *(ci)* Test that python wheels can be built and installed - ([9676315](https://github.com/radusuciu/git-cliff/commit/9676315e7e809c01045a8fe0d8b9cf4220c8477d))
- *(config)* Support detecting config from project manifest ([#571](https://github.com/orhun/git-cliff/issues/571)) - ([9eb3d65](https://github.com/radusuciu/git-cliff/commit/9eb3d65945d70d04a99a2ea7a3042c404ea6f78b))
- *(release)* Make the bump version rules configurable ([#530](https://github.com/orhun/git-cliff/issues/530)) - ([152414c](https://github.com/radusuciu/git-cliff/commit/152414cb817778a2deca320c034a97284d520d30))

### 🐛 Bug Fixes

- *(changelog)* Update the commit processing order ([#556](https://github.com/orhun/git-cliff/issues/556)) - ([c5ef9ab](https://github.com/radusuciu/git-cliff/commit/c5ef9ab2916552b92875a67ebb41460b9928a7fc))
- *(changelog)* Return the last version if there is nothing to bump - ([45c87f2](https://github.com/radusuciu/git-cliff/commit/45c87f2f307e8441c128b81835b662362e6b380a))
- *(ci)* Remove specific maturin requirement from `pyproject.toml` - ([5df8731](https://github.com/radusuciu/git-cliff/commit/5df87314f61f2423cc0084ec1c9ae83ffafd979c))
- *(ci)* Do not list maturin as a build dependency - ([a50210d](https://github.com/radusuciu/git-cliff/commit/a50210d33b386b8cfb1a3c1d71d851fb1f45d582))
- *(ci)* Remove check for non-existent matrix property - ([2cd6e34](https://github.com/radusuciu/git-cliff/commit/2cd6e34b1e54ab3040c137b527035f532fc006e7))
- *(command)* Add missing environment variables for Windows ([#532](https://github.com/orhun/git-cliff/issues/532)) - ([9722784](https://github.com/radusuciu/git-cliff/commit/972278439613d6187699fec02db8e1c4826ec92b))
- *(commit)* Trim the text before matching with commit parser ([#573](https://github.com/orhun/git-cliff/issues/573)) - ([4971b23](https://github.com/radusuciu/git-cliff/commit/4971b236ace1d6a8af96f4527256ceeb8c8c4551))
- *(config)* Drop extra '(' in first commit URL in github-keepachangelog ([#535](https://github.com/orhun/git-cliff/issues/535)) - ([8b3d09f](https://github.com/radusuciu/git-cliff/commit/8b3d09f7766f8dc2ae5ac1f5afab0dc51283ef3d))
- *(npm)* Fix authenticating for `yarn npm publish` ([#574](https://github.com/orhun/git-cliff/issues/574)) - ([5a0ce6a](https://github.com/radusuciu/git-cliff/commit/5a0ce6acc1dab99698db73315215322d922dfde3))
- *(release)* Fix typo in the installation of typos-cli ([#545](https://github.com/orhun/git-cliff/issues/545)) - ([700281a](https://github.com/radusuciu/git-cliff/commit/700281a25be52d896329027672a26b722c359283))

### 📚 Documentation

- *(website)* Fix the documentation for `--include-path` ([#567](https://github.com/orhun/git-cliff/issues/567)) - ([4a7aa7e](https://github.com/radusuciu/git-cliff/commit/4a7aa7e91f78d8d436842d289f5f61a4bd8e5a2f))
- *(website)* Update setup-git-cliff action documentation - ([4f46396](https://github.com/radusuciu/git-cliff/commit/4f4639647bc73428c71ab1944b3e330023961924))
- *(website)* Add documentation for taiki-e/install-action ([#563](https://github.com/orhun/git-cliff/issues/563)) - ([85db777](https://github.com/radusuciu/git-cliff/commit/85db77760914a2ac5e35d919613b744af15d0b05))

### ⚙️ Miscellaneous Tasks

- *(ci)* Temporarily disable semver checks - ([f26fbe0](https://github.com/radusuciu/git-cliff/commit/f26fbe09ffc4ad0bf24260d7bd8a93d991817a2a))
- *(ci)* Comment on pull requests about semver checks - ([ccdc152](https://github.com/radusuciu/git-cliff/commit/ccdc15217cfcc1c1c3bf09d4d997f7f99526b10e))
- *(config)* Skip clippy commits in changelog - ([830528c](https://github.com/radusuciu/git-cliff/commit/830528c0c0c8d45362869df54c835afab2936c90))
- *(github)* Remove cname - ([679aa46](https://github.com/radusuciu/git-cliff/commit/679aa4671984c8a5c1f5ea6929afa3fc26f667fc))
- *(github)* Update funding options - ([4bedf76](https://github.com/radusuciu/git-cliff/commit/4bedf764e33454d44db9020a0dd3149df09489e2))
- *(github)* Use form based issue templates ([#529](https://github.com/orhun/git-cliff/issues/529)) - ([8f8e221](https://github.com/radusuciu/git-cliff/commit/8f8e2215636262b21074963ac0d846edc55a80ab))
- *(npm)* Publish rc version for prereleases ([#528](https://github.com/orhun/git-cliff/issues/528)) - ([16bea51](https://github.com/radusuciu/git-cliff/commit/16bea5179a89af26dd0bfb07c7d6b7d1efa3c54e))
- *(pypi)* Update maturin version ([#539](https://github.com/orhun/git-cliff/issues/539)) - ([10b7ab8](https://github.com/radusuciu/git-cliff/commit/10b7ab829f30beba19d13437ebafc35b9bb38476))
- *(website)* Allow deploying website manually - ([0b64bc0](https://github.com/radusuciu/git-cliff/commit/0b64bc032523f6565e47352cccd0d92f8bf9eae9))
- *(website)* Only deploy website when there is a new release - ([8651832](https://github.com/radusuciu/git-cliff/commit/8651832926afa83dac4b9cbb5d298bbea5e7af6d))

## [2.1.2](https://github.com/radusuciu/git-cliff/compare/v2.0.4..v2.1.2) - 2024-03-03

### ⛰️  Features

- *(args)* Add `--tag-pattern` argument ([#526](https://github.com/orhun/git-cliff/issues/526)) - ([b4e7a34](https://github.com/radusuciu/git-cliff/commit/b4e7a3400f0675bba63339cd89513ffcb7acb688))
- *(npm)* Add programmatic API for TypeScript ([#523](https://github.com/orhun/git-cliff/issues/523)) - ([8b33267](https://github.com/radusuciu/git-cliff/commit/8b332679677ab7690d718d0d81954bff8d4cc585))

### 🐛 Bug Fixes

- *(cd)* Set the correct GitHub repository URL - ([7f379a9](https://github.com/radusuciu/git-cliff/commit/7f379a9c8377baa206d05c5cb0dfc6150905b19a))
- *(cd)* Set a flag as a workaround for the NPM package - ([717abce](https://github.com/radusuciu/git-cliff/commit/717abce767906f752408e2745f47d0fc9013699c))
- *(cd)* Set node version to 18 for building NPM packages - ([5dd0d2e](https://github.com/radusuciu/git-cliff/commit/5dd0d2ebf8f1e9fa81d8b933c33ed62654039ce6))
- *(cd)* Explicitly set the Homebrew formula path - ([8d2f1fa](https://github.com/radusuciu/git-cliff/commit/8d2f1fab2b70da990921dfc55202ef1413ec63f1))
- *(cd)* Set the GitHub repository explicitly - ([0e46500](https://github.com/radusuciu/git-cliff/commit/0e46500199f9b7cc7c83a51499f6e90a2adf5888))
- *(config)* Fix commit parser regex in the default config - ([110b9b8](https://github.com/radusuciu/git-cliff/commit/110b9b8d2676800ebe169287fa5d2a93c9f6b55f))
- *(github)* Sanitize the GitHub token in debug logs - ([be34949](https://github.com/radusuciu/git-cliff/commit/be34949df76f9f174dce0b9e593bda594a9d33a5))

### 🚜 Refactor

- *(cd)* Simplify checking pre-releases - ([87a04fb](https://github.com/radusuciu/git-cliff/commit/87a04fb437ce8d74c53461f2a46316ff611f074f))
- *(changelog)* Do not output to stdout when prepend is used - ([8ee0da1](https://github.com/radusuciu/git-cliff/commit/8ee0da1f74a0f2cae699ce19accc073434f5b538))

### 📚 Documentation

- *(website)* Add tip about skipping commits by PR label - ([6d3354c](https://github.com/radusuciu/git-cliff/commit/6d3354ca1b0e401e5374f0cd28b2f96753ac4f2b))
- *(website)* Add instructions for installing from WinGet ([#520](https://github.com/orhun/git-cliff/issues/520)) - ([eeaa406](https://github.com/radusuciu/git-cliff/commit/eeaa40673fbf28eafef462fbc61506e7d9f97678))

### 🎨 Styling

- *(website)* Use a short link for reporting issues - ([ba83c8a](https://github.com/radusuciu/git-cliff/commit/ba83c8ae71b838137682ff0c92424e064ca4f62e))

### ⚙️ Miscellaneous Tasks

- *(ci)* Auto-bump the homebrew formula - ([61d055b](https://github.com/radusuciu/git-cliff/commit/61d055b9169b9eb3d5a458b1dc1cb6ff8d919807))
- *(ci)* Enable default features for windows builds - ([18f4923](https://github.com/radusuciu/git-cliff/commit/18f4923897a4f54ebe9870014463a67f3a655c9d))
- *(ci)* Check semver violations via CI - ([a25a114](https://github.com/radusuciu/git-cliff/commit/a25a1148d92ee07402c9069eaad74574e392339c))
- *(fixtures)* Enable verbose logging for output - ([2927231](https://github.com/radusuciu/git-cliff/commit/292723109f328f96b84a629d61fd38b02ceef4e8))

## [2.0.4](https://github.com/radusuciu/git-cliff/compare/v2.0.2..v2.0.4) - 2024-02-22

### ⛰️  Features

- *(docker)* Enable github feature for the docker image - ([bc882e3](https://github.com/radusuciu/git-cliff/commit/bc882e3884ca8ce1391fc70e3dcaa02204de0dd4))
- *(github)* Support overriding the GitHub API URL ([#512](https://github.com/orhun/git-cliff/issues/512)) - ([8199699](https://github.com/radusuciu/git-cliff/commit/819969924bbad25484971c84a4c8d02ae48f1db9))

### 🐛 Bug Fixes

- *(cd)* Do not execute commands for the release changelog - ([1aaa9b2](https://github.com/radusuciu/git-cliff/commit/1aaa9b2150f539116007afc199f57a61bbe4ee20))

### 📚 Documentation

- *(website)* Add instructions for installing from conda-forge ([#511](https://github.com/orhun/git-cliff/issues/511)) - ([75a04bb](https://github.com/radusuciu/git-cliff/commit/75a04bb1b0d929f03a2bd224fc728dcf14b6e896))

### ⚙️ Miscellaneous Tasks

- *(config)* Add animation to the header of the changelog - ([4f741a7](https://github.com/radusuciu/git-cliff/commit/4f741a7c9ebd52404503c60dc91e053f1b9c0171))
- *(website)* Bump the version of git-cliff-action - ([f255ad3](https://github.com/radusuciu/git-cliff/commit/f255ad38b2640b3f42a40eda3b76cddb6c06d2ff))
- *(website)* Add announcement bar for the new release - ([1d32a14](https://github.com/radusuciu/git-cliff/commit/1d32a14175355ef83dbaa0dd80f17a9c2493e7de))

## [2.0.2](https://github.com/radusuciu/git-cliff/compare/v2.0.1..v2.0.2) - 2024-02-19

### 📚 Documentation

- *(release)* Add note about GitHub variables - ([54e21de](https://github.com/radusuciu/git-cliff/commit/54e21de5eebe61f23328e92c6fb8f8de7fd900fd))

## [2.0.1](https://github.com/radusuciu/git-cliff/compare/v2.0.0..v2.0.1) - 2024-02-19

### ⚙️ Miscellaneous Tasks

- *(cd)* Disable PyPI builds for linux-x86-glibc - ([30d8e41](https://github.com/radusuciu/git-cliff/commit/30d8e41b06e2b277e700731fe193906e49e2509a))

## [2.0.0](https://github.com/radusuciu/git-cliff/compare/v1.4.0..v2.0.0) - 2024-02-19

### ⛰️  Features

- *(args)* Add `--no-exec` flag for skipping command execution ([#458](https://github.com/orhun/git-cliff/issues/458)) - ([7ae77ff](https://github.com/radusuciu/git-cliff/commit/7ae77ff0e0a22b5f5e42737204cbf0ab8680f9d7))
- *(args)* Add `-x` short argument for `--context` - ([327512a](https://github.com/radusuciu/git-cliff/commit/327512a9d522e67252becd46628ef5ebe95539d7))
- *(args)* Support initialization with built-in templates ([#370](https://github.com/orhun/git-cliff/issues/370)) - ([4bee628](https://github.com/radusuciu/git-cliff/commit/4bee628867a242a0165829db2ca70bfba964e345))
- *(args)* Allow returning the bumped version ([#362](https://github.com/orhun/git-cliff/issues/362)) - ([5e01e4c](https://github.com/radusuciu/git-cliff/commit/5e01e4c775d1e3e7d2caa52d5bafed99dcfa0660))
- *(args)* Set `CHANGELOG.md` as default missing value for output option ([#354](https://github.com/orhun/git-cliff/issues/354)) - ([04d149e](https://github.com/radusuciu/git-cliff/commit/04d149e1245d892a50307f9637b5f665b47b50d4))
- *(changelog)* Set the timestamp of the previous release - ([d408e63](https://github.com/radusuciu/git-cliff/commit/d408e6377a5157f6d285b2733e6640d36316cfd4))
- *(changelog)* Improve skipping via `.cliffignore` and `--skip-commit` ([#413](https://github.com/orhun/git-cliff/issues/413)) - ([faa00c6](https://github.com/radusuciu/git-cliff/commit/faa00c6e6cee3c4fa7bd06e5dd409d81ca4b6b8f))
- *(changelog)* Support tag prefixes with `--bump` ([#347](https://github.com/orhun/git-cliff/issues/347)) - ([2399e57](https://github.com/radusuciu/git-cliff/commit/2399e57fd3b715875d5dc3897fad85a70cc199eb))
- *(changelog)* [**breaking**] Set tag to `0.0.1` via `--bump` if no tags exist - ([3291eb9](https://github.com/radusuciu/git-cliff/commit/3291eb99acf228086633852fac9b78c30e0db673))
- *(changelog)* [**breaking**] Support templating in the footer ([#369](https://github.com/orhun/git-cliff/issues/369)) - ([0945fa8](https://github.com/radusuciu/git-cliff/commit/0945fa806cc1714f92277142d974e4591c55e04f))
- *(commit)* Add merge_commit flag to the context ([#389](https://github.com/orhun/git-cliff/issues/389)) - ([dd27a9a](https://github.com/radusuciu/git-cliff/commit/dd27a9a404272f3e4ea40bbfcb30a07929014442))
- *(github)* [**breaking**] Support integration with GitHub repos ([#363](https://github.com/orhun/git-cliff/issues/363)) - ([5238326](https://github.com/radusuciu/git-cliff/commit/52383267905e8d007b60e4b2e21cbe2280952d72))
- *(parser)* Support using SHA1 of the commit ([#385](https://github.com/orhun/git-cliff/issues/385)) - ([1039f85](https://github.com/radusuciu/git-cliff/commit/1039f8575ad5e956355bfbf0394e49d8557faa2e))
- *(parser)* Support using regex scope values ([#372](https://github.com/orhun/git-cliff/issues/372)) - ([19e65c2](https://github.com/radusuciu/git-cliff/commit/19e65c25b3631004bdd032ee36eccdf79dfb618d))
- *(template)* Support using PR labels in the GitHub template ([#467](https://github.com/orhun/git-cliff/issues/467)) - ([30d15bb](https://github.com/radusuciu/git-cliff/commit/30d15bbab77efecda9941bf885cb93bedbd0563c))
- *(template)* Support using PR title in the GitHub template ([#418](https://github.com/orhun/git-cliff/issues/418)) - ([6f32f33](https://github.com/radusuciu/git-cliff/commit/6f32f3376e2b0b85206bc33795be57b0dad16afe))
- *(website)* Add search bar to the website - ([2d30491](https://github.com/radusuciu/git-cliff/commit/2d30491bdb7914229ba417e29aa5b813b056b6ef))

### 🐛 Bug Fixes

- *(cd)* Use workaround for linux-arm64-glibc maturin builds - ([dc79ed5](https://github.com/radusuciu/git-cliff/commit/dc79ed5fe25afd6255b2d93d06d2b47016769c4b))
- *(cd)* Disable PyPI publish for linux-arm64-glibc - ([e24af12](https://github.com/radusuciu/git-cliff/commit/e24af123dbd2c242f2aa98c67f98cc82ae9a3f78))
- *(cd)* Avoid creating artifacts with the same name - ([1647fd8](https://github.com/radusuciu/git-cliff/commit/1647fd82e901f66e3ca00fae2688fd31fe238149))
- *(cd)* Fix embedding examples for crates.io release - ([46b7d88](https://github.com/radusuciu/git-cliff/commit/46b7d880cf4f6e2ed30946f7f10a46d82f96af9a))
- *(changelog)* Fix previous version links ([#364](https://github.com/orhun/git-cliff/issues/364)) - ([44c93b7](https://github.com/radusuciu/git-cliff/commit/44c93b7c704b01d371eb826fc9ffcb459f7370b1))
- *(changelog)* Set the correct previous tag when a custom tag is given - ([6203f77](https://github.com/radusuciu/git-cliff/commit/6203f77dab5c19981f9dc8f8408c97344eb73003))
- *(ci)* Update cargo-msrv arguments - ([131dd10](https://github.com/radusuciu/git-cliff/commit/131dd10c53087ce1ceaea07f030478fca393c253))
- *(cli)* Fix broken pipe when stdout is interrupted ([#407](https://github.com/orhun/git-cliff/issues/407)) - ([bdce4b5](https://github.com/radusuciu/git-cliff/commit/bdce4b504e0b1984283ad056931fc4fe7b893dc3))
- *(commit)* Trim the trailing newline from message ([#403](https://github.com/orhun/git-cliff/issues/403)) - ([514ca4b](https://github.com/radusuciu/git-cliff/commit/514ca4bda172d8fdfb612dd28f4bde8aae9e29fe))
- *(git)* Sort commits in topological order ([#415](https://github.com/orhun/git-cliff/issues/415)) - ([29bf355](https://github.com/radusuciu/git-cliff/commit/29bf355205da4860ceb3777de983beb93ec47a08))
- *(links)* Skip checking the GitHub commit URLs - ([273d6dc](https://github.com/radusuciu/git-cliff/commit/273d6dc14b000ab556ac7af5732e75f8857020f7))
- *(website)* Use node version 18 - ([46dcce3](https://github.com/radusuciu/git-cliff/commit/46dcce38444132f851bc9dff2bdd994632c56e1c))
- *(website)* Use prism-react-renderer v2 with docusaurus - ([664ff9b](https://github.com/radusuciu/git-cliff/commit/664ff9bc14e2da3c44b7cf5f11c780223c25ce53))
- Allow version bump with a single previous release - ([d65aec9](https://github.com/radusuciu/git-cliff/commit/d65aec9d249b3ad941ccfac77c3248d12d3d30d3))

### 🚜 Refactor

- *(changelog)* Support `--bump` for processed releases ([#408](https://github.com/orhun/git-cliff/issues/408)) - ([89e4c72](https://github.com/radusuciu/git-cliff/commit/89e4c729a915d456c1b83f666637bf85c7125350))
- *(ci)* Use hardcoded workspace members for cargo-msrv command - ([ec6035a](https://github.com/radusuciu/git-cliff/commit/ec6035a7e77c60e8b7f752619aeee36f08c80aad))
- *(ci)* Simplify cargo-msrv installation - ([f04bf6e](https://github.com/radusuciu/git-cliff/commit/f04bf6eca155eec32f82aca482e5c00ab16d61a9))
- *(config)* Use postprocessors for checking the typos - ([764e858](https://github.com/radusuciu/git-cliff/commit/764e858a1e948dbc507cde3264a72e3458c98833))
- *(config)* Remove unnecessary newline from configs - ([8edec7f](https://github.com/radusuciu/git-cliff/commit/8edec7fd50f703811d55f14a3c5f0fd02b43d9e7))

### 📚 Documentation

- *(configuration)* Fix typo ([#466](https://github.com/orhun/git-cliff/issues/466)) - ([34a58e6](https://github.com/radusuciu/git-cliff/commit/34a58e6e2bea34bbcc5190fd10fddd0fb3e7e73f))
- *(fixtures)* Add instructions for adding new fixtures - ([8290769](https://github.com/radusuciu/git-cliff/commit/82907693c19a38699c57f9206564e8a9c7d9d705))
- *(readme)* Mention RustLab 2023 talk - ([668a957](https://github.com/radusuciu/git-cliff/commit/668a95774c076b53f719cdd0708b9385168dbc6e))
- *(readme)* Use the raw link for the animation - ([2c524b8](https://github.com/radusuciu/git-cliff/commit/2c524b8e64a8d248a6345b4eee3afbde21bf38a8))
- *(security)* Update security policy - ([fcaa502](https://github.com/radusuciu/git-cliff/commit/fcaa5021083ff7cb8f70044801fff19e1b012493))
- *(website)* Add highlights for 2.0.0 ([#504](https://github.com/orhun/git-cliff/issues/504)) - ([49684d0](https://github.com/radusuciu/git-cliff/commit/49684d0fd8a6876cf09f29f3b860c2851fe7a992))
- *(website)* Improve matching gitmoji tip ([#486](https://github.com/orhun/git-cliff/issues/486)) - ([0731646](https://github.com/radusuciu/git-cliff/commit/0731646c26142a92f90a6b567dfeee877d45f3c5))
- *(website)* Add tips and tricks section - ([82e93c2](https://github.com/radusuciu/git-cliff/commit/82e93c26deaa0eeebe0f46f91fa2d35154bcfe2c))
- *(website)* Add tip about link parsers - ([4bd47a6](https://github.com/radusuciu/git-cliff/commit/4bd47a69e9d0fbd2656fb43abab930225411259b))
- *(website)* Add git-cliff animation to the website ([#404](https://github.com/orhun/git-cliff/issues/404)) - ([0561124](https://github.com/radusuciu/git-cliff/commit/05611245d9ee42d5eff7e2a64eb041b452129356))
- *(website)* Split the configuration section - ([67486cc](https://github.com/radusuciu/git-cliff/commit/67486ccb72882562d94718afc4f5db3b631d49f6))
- *(website)* Add installation instructions for Homebrew ([#357](https://github.com/orhun/git-cliff/issues/357)) - ([b2f8091](https://github.com/radusuciu/git-cliff/commit/b2f8091bd485a81add367a8a01066c7957e45772))

### 🎨 Styling

- *(website)* Add GitHub logo to the header - ([1da7cac](https://github.com/radusuciu/git-cliff/commit/1da7cac7ce5df4de0a49ddbb9a52621ffa849124))
- *(website)* [**breaking**] Use dark theme as default - ([dcc5116](https://github.com/radusuciu/git-cliff/commit/dcc511609f42a7ae10069cd31a50540a77b59234))

### 🧪 Testing

- *(changelog)* Use the correct version for missing tags - ([0ca4cdb](https://github.com/radusuciu/git-cliff/commit/0ca4cdb45d9f910adb4d52cb6c58ec6539dabca6))
- *(fixture)* Update the date for example test fixture - ([991a035](https://github.com/radusuciu/git-cliff/commit/991a035e0e070416bbde7769ac3646ae563d1f13))
- *(fixture)* Add test fixture for bumping version - ([c94cb6a](https://github.com/radusuciu/git-cliff/commit/c94cb6a37ae268953ab29dd35cb43b6a4fec47cc))
- *(fixtures)* Update the bumped value output to add prefix - ([f635bae](https://github.com/radusuciu/git-cliff/commit/f635bae964386c42474659f3d7903258f4ef8ee9))

### ⚙️ Miscellaneous Tasks

- *(changelog)* Disable the default behavior of next-version ([#343](https://github.com/orhun/git-cliff/issues/343)) - ([4eef684](https://github.com/radusuciu/git-cliff/commit/4eef684c568ad16357e5d256180a51b1a46dd0cb))
- *(changelog)* Use 0.1.0 as default next release if no tag is found - ([3123fd2](https://github.com/radusuciu/git-cliff/commit/3123fd2eac0da0e800923d8b9f3c86bc6814edd4))
- *(command)* Explicitly set the directory of command to current dir - ([722efd6](https://github.com/radusuciu/git-cliff/commit/722efd6598a580f995bf282184c400c095c49eae))
- *(config)* Skip dependabot commits for dev updates - ([7f89160](https://github.com/radusuciu/git-cliff/commit/7f891602e4818f612ef928e84488053c7aad56d9))
- *(config)* Revamp the configuration files - ([9500bf8](https://github.com/radusuciu/git-cliff/commit/9500bf8ef88df8ff0fbfaf08d2eb531d09e472ef))
- *(dependabot)* Group the dependency updates for creating less PRs - ([c6a92bf](https://github.com/radusuciu/git-cliff/commit/c6a92bf6871a436e60ca9774d0b0df770727e664))
- *(docker)* Update versions in Dockerfile - ([51198a5](https://github.com/radusuciu/git-cliff/commit/51198a5a56ca1f8a09d527c37695231520a130d4))
- *(embed)* Do not allow missing docs - ([7754cab](https://github.com/radusuciu/git-cliff/commit/7754cab1c8a53ce8703596bbc921a2a3867a4155))
- *(example)* Use full links in GitHub templates ([#503](https://github.com/orhun/git-cliff/issues/503)) - ([a521891](https://github.com/radusuciu/git-cliff/commit/a521891b557772451f37a791bde04067d3f20626))
- *(example)* Remove limited commits example - ([8e1e0d7](https://github.com/radusuciu/git-cliff/commit/8e1e0d73c3bb7a0294bc20c01a0a6800ebbfbb1a))
- *(github)* Update templates about GitHub integration - ([3f5107a](https://github.com/radusuciu/git-cliff/commit/3f5107a02c3bb50bbd7712e81c95eeb7344e01f6))
- *(mergify)* Don't update PRs for the main branch - ([96a220c](https://github.com/radusuciu/git-cliff/commit/96a220c8e9b665f96c6794ca423f04464007fe0f))
- *(project)* Add readme to core package - ([9e6bad2](https://github.com/radusuciu/git-cliff/commit/9e6bad28db23b39311c4231c96f1d7805296c3b9))
- *(project)* Bump MSRV to 1.74.1 - ([bd5e4d2](https://github.com/radusuciu/git-cliff/commit/bd5e4d2217c307177f6f1de99cae5f5ae5024b33))
- *(project)* Update copyright years - ([edc6bc0](https://github.com/radusuciu/git-cliff/commit/edc6bc0adbf2952b8a532a44ccf11f6f1b5448f2))
- *(website)* Fix URLs in navigation bar ([#438](https://github.com/orhun/git-cliff/issues/438)) - ([70cab99](https://github.com/radusuciu/git-cliff/commit/70cab990cce4ba4e9077fb69cef385e2ec209080))
- *(website)* Rename the header for GitHub integration - ([3fd9476](https://github.com/radusuciu/git-cliff/commit/3fd9476a565212343d3af4e2d7387d7ef265b4f1))
- *(website)* Fix broken anchors - ([34593dd](https://github.com/radusuciu/git-cliff/commit/34593dd46f3ce0f0ab809416fc37294a62658036))
- *(website)* Bump docusaurus to 3.1.0 - ([af4482b](https://github.com/radusuciu/git-cliff/commit/af4482b4158ccdee71912d78f5fb0a1c280e6ed6))
- *(website)* Update the titles for distro installations - ([ff2881b](https://github.com/radusuciu/git-cliff/commit/ff2881bebd1020420db04927b2ac7893edf973a6))
- *(website)* Add Mastodon link to the website - ([2e761c9](https://github.com/radusuciu/git-cliff/commit/2e761c936dbe54b1c9a683f67d4556d2e64b2fec))

### ◀️ Revert

- *(config)* Use postprocessors for checking the typos - ([5212cc9](https://github.com/radusuciu/git-cliff/commit/5212cc9446bc1389274516ed3d7eb7b334b1b606))

## [1.4.0](https://github.com/radusuciu/git-cliff/compare/v1.3.0..v1.4.0) - 2023-10-29

### ⛰️  Features

- *(args)* Support tilde for options ([#266](https://github.com/orhun/git-cliff/issues/266)) - ([8698bc2](https://github.com/radusuciu/git-cliff/commit/8698bc2ce4d58fdeb9563c18f7430798b6359029))
- *(changelog)* Support bumping the semantic version via `--bump` ([#309](https://github.com/orhun/git-cliff/issues/309)) - ([bcfcd1f](https://github.com/radusuciu/git-cliff/commit/bcfcd1fd59fa2c1ef3222d588f3a563c3e10027e))
- *(ci)* Add 'typos' check ([#317](https://github.com/orhun/git-cliff/issues/317)) - ([88c34ab](https://github.com/radusuciu/git-cliff/commit/88c34abe2c6572d401e0bd77d2aec4138bd2c88b))
- *(ci)* Distribute RPM package ([#159](https://github.com/orhun/git-cliff/issues/159)) - ([baf4da8](https://github.com/radusuciu/git-cliff/commit/baf4da80639682628ca4ae538b4555ff1b6262da))
- *(command)* Log the output of failed external commands - ([205cdbb](https://github.com/radusuciu/git-cliff/commit/205cdbb391b03244abaf2e5e0651976544c78ff4))
- *(config)* [**breaking**] Support regex in 'tag_pattern' configuration ([#318](https://github.com/orhun/git-cliff/issues/318)) - ([3c2fb60](https://github.com/radusuciu/git-cliff/commit/3c2fb6072612a38ab7c6ea41e7c2ae34435fde99))
- *(config)* Add field and value matchers to the commit parser ([#312](https://github.com/orhun/git-cliff/issues/312)) - ([04fbcb8](https://github.com/radusuciu/git-cliff/commit/04fbcb88a5cb85a2f192b3ecc7261bd55548be9e))

### 🐛 Bug Fixes

- *(ci)* Update cargo-tarpaulin arguments - ([83a0371](https://github.com/radusuciu/git-cliff/commit/83a03711185df20f37bbcbad955e7783b8bdb662))

### 🚜 Refactor

- *(ci)* Simplify cargo-tarpaulin installation - ([95f8d53](https://github.com/radusuciu/git-cliff/commit/95f8d53ac158d81433f6a49cf0794d92b0eb21ef))

### 📚 Documentation

- *(blog)* Fix the TOML format in 1.4.0 blog post - ([4d691d2](https://github.com/radusuciu/git-cliff/commit/4d691d2620f6fcd574c2be64c6a8f6023db063c2))
- *(blog)* Add blog post for 1.4.0 release - ([e3f1b3b](https://github.com/radusuciu/git-cliff/commit/e3f1b3bdb3d7f8a0dce695fed18077aacdc1d3bd))
- *(changelog)* Fix typos ([#316](https://github.com/orhun/git-cliff/issues/316)) - ([edd3c30](https://github.com/radusuciu/git-cliff/commit/edd3c30000af1542c0df5b3ca5e0ea4fcc6efb74))
- *(config)* Update the comment for tag_pattern - ([596fd4d](https://github.com/radusuciu/git-cliff/commit/596fd4d14d57ce6357c299181c523a00af11b36c))
- *(core)* Update the doc comment for commit preprocessors - ([7faccc6](https://github.com/radusuciu/git-cliff/commit/7faccc65a87fe29aa26cdfce63880899a0e8bf3d))
- *(image)* Use images from the repository - ([91c0cda](https://github.com/radusuciu/git-cliff/commit/91c0cda9dc79740d322275f45184facfc8300163))
- *(installation)* Update instructions for Arch Linux - ([291a928](https://github.com/radusuciu/git-cliff/commit/291a9282888547b4c45d64ccb8f1495448544201))
- *(installation)* Add instructions for Alpine Linux - ([3199bba](https://github.com/radusuciu/git-cliff/commit/3199bba672e8045141debf1268873811f17ac405))
- *(lib)* Extract feature documentation from Cargo.toml - ([1f8098c](https://github.com/radusuciu/git-cliff/commit/1f8098cd7f0f5473a3a7f847aaaa62b1cfdc7759))
- *(lib)* Add logo and favicon to docs.rs page - ([32b1fe1](https://github.com/radusuciu/git-cliff/commit/32b1fe1556e25c2a29adffe0a68e68183bc9ae63))
- *(license)* Re-license under the MIT + Apache 2.0 license ([#303](https://github.com/orhun/git-cliff/issues/303)) - ([cd56344](https://github.com/radusuciu/git-cliff/commit/cd563444dec852bacc2586dea55a7b0d5dcdc844))
- *(readme)* Add link to emacs package support git-cliff ([#307](https://github.com/orhun/git-cliff/issues/307)) - ([fa471c7](https://github.com/radusuciu/git-cliff/commit/fa471c7178dce184ca6fe5bbb24b9c2db96d68ce))
- *(website)* Fix typos in configuration docs ([#329](https://github.com/orhun/git-cliff/issues/329)) - ([d863c94](https://github.com/radusuciu/git-cliff/commit/d863c9481a7882a1a1ecc59050c2d30b2b9a1728))
- *(website)* Add instructions for installing the latest git version - ([be87608](https://github.com/radusuciu/git-cliff/commit/be87608002d6beba58368af4fed73e746cde352a))
- Update Tera links to the new URL ([#272](https://github.com/orhun/git-cliff/issues/272)) - ([890de00](https://github.com/radusuciu/git-cliff/commit/890de0007e108059378b134e9b9d0af2a6965027))

### ⚙️ Miscellaneous Tasks

- *(ci)* Update the link checker configuration ([#315](https://github.com/orhun/git-cliff/issues/315)) - ([32cbea8](https://github.com/radusuciu/git-cliff/commit/32cbea8e48300746879e754618672c5a1270ba95))
- *(config)* Update tag_pattern value for backwards compatibility - ([2c621f7](https://github.com/radusuciu/git-cliff/commit/2c621f71e6cdca05b17516d2a9ba80fbabd4d3f8))
- *(img)* Add more images - ([2792362](https://github.com/radusuciu/git-cliff/commit/2792362a52a8fc862fa7899cda911ce7e56786b1))
- *(img)* Add git-cliff logo - ([51f5e5b](https://github.com/radusuciu/git-cliff/commit/51f5e5b16f7f509c59bd1d6e990989ba33581e7b))
- *(release)* Update cargo-deb usage - ([213f383](https://github.com/radusuciu/git-cliff/commit/213f383b54c9a40a351f341c28bbdf03b73f701d))
- *(website)* Update the tracking link - ([eb9f8e9](https://github.com/radusuciu/git-cliff/commit/eb9f8e970d2adcb6c6f512b20ca8a9f77d09ff54))
- Remove GPL code ([#293](https://github.com/orhun/git-cliff/issues/293)) - ([e3606ba](https://github.com/radusuciu/git-cliff/commit/e3606babdf35022b662c870cb720c1f5339e1543))

### ◀️ Revert

- *(args)* Update clap and clap extras to v4 ([#137](https://github.com/orhun/git-cliff/issues/137)) ([#292](https://github.com/orhun/git-cliff/issues/292)) - ([fb4c733](https://github.com/radusuciu/git-cliff/commit/fb4c733a70a4dbc25060481ee5f3c644bb0bb83b))

## [1.3.0](https://github.com/radusuciu/git-cliff/compare/v1.2.0..v1.3.0) - 2023-08-31

### 🚜 Refactor

- *(docker)* Avoid copying volume inside container ([#142](https://github.com/orhun/git-cliff/issues/142)) - ([65d365c](https://github.com/radusuciu/git-cliff/commit/65d365c7b521e30ebc173d97f10c41da604582ae))

### 🧪 Testing

- *(repo)* Add an informative error message to failing test - ([7d7470b](https://github.com/radusuciu/git-cliff/commit/7d7470b2d0d030135aab09369d6484837c2bd6c7))

### ⚙️ Miscellaneous Tasks

- *(core)* Make git2 optional - ([5fdf39a](https://github.com/radusuciu/git-cliff/commit/5fdf39ae32441ce70a942e577e31ba0cd2323137))
- *(github)* Add config for welcome bot - ([a4725d4](https://github.com/radusuciu/git-cliff/commit/a4725d4ce43340cdb0483ac2bb7566c00dc7a991))
- Check without default features - ([e323621](https://github.com/radusuciu/git-cliff/commit/e323621094141acaab360d6fa42990c7cdd4bac4))

<!-- generated by git-cliff -->
