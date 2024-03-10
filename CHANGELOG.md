# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

Generated by [`auto-changelog`](https://github.com/CookPete/auto-changelog).

## [Unreleased](https://github.com/alecdibble/tabtabtab/compare/v3.0.2...HEAD)

### Commits

- Add ability to pass shell type in init function [`b91070b`](https://github.com/alecdibble/tabtabtab/commit/b91070bf0ab326b2c4e564aba18800a83974f378)
- Updates to support nama [`6c53925`](https://github.com/alecdibble/tabtabtab/commit/6c53925c887832271f86413996f4a3490be5248b)
- Updates to support multiple tabtabtab installations at once [`589a7d7`](https://github.com/alecdibble/tabtabtab/commit/589a7d79f290f86b732417573c30e662cb8f6eac)

## [v3.0.2](https://github.com/alecdibble/tabtabtab/compare/v3.0.1-beta...v3.0.2) - 2018-10-06

### Commits

- feat: add tabtab.uninstall() [`23907cd`](https://github.com/alecdibble/tabtabtab/commit/23907cdfbe16e17aefa171a750550c6fc7af42db)
- docs: update doc files [`c18b614`](https://github.com/alecdibble/tabtabtab/commit/c18b61417bb782de9469547424b502796788a593)

## [v3.0.1-beta](https://github.com/alecdibble/tabtabtab/compare/v3.0.0-beta...v3.0.1-beta) - 2018-10-05

### Fixed

- Fixing check of filename when installing [`#47`](https://github.com/alecdibble/tabtabtab/issues/47)

### Commits

- Begin to write uninstall method [`e143f80`](https://github.com/alecdibble/tabtabtab/commit/e143f80909cfc06ab223c41a41ae4bc7ec1f9e1a)
- npm: remove assert-rejects [`399a3da`](https://github.com/alecdibble/tabtabtab/commit/399a3da9216d565d61c101f3d97f082d83809228)
- example: adding uninstall-completion to example [`c48223a`](https://github.com/alecdibble/tabtabtab/commit/c48223ae3ca204f322b523c14b887689e6ea23ee)

## [v3.0.0-beta](https://github.com/alecdibble/tabtabtab/compare/v2.2.2...v3.0.0-beta) - 2018-10-04

### Merged

- installer: ensure successful status/$? [`#38`](https://github.com/alecdibble/tabtabtab/pull/38)
- Remove `npmlog`. [`#31`](https://github.com/alecdibble/tabtabtab/pull/31)
- Fix wrong shell reference [`#35`](https://github.com/alecdibble/tabtabtab/pull/35)

### Commits

- npm: setup nyc [`1f86b2a`](https://github.com/alecdibble/tabtabtab/commit/1f86b2a0a57a136de6299a472336e7d05ecf8004)
- first cleanup [`c89f237`](https://github.com/alecdibble/tabtabtab/commit/c89f237f2a7539a9a205bf0a23cc817c2ea8e4d8)
- setup npm-watch [`a47d73a`](https://github.com/alecdibble/tabtabtab/commit/a47d73ad4be0c215be20389a7c42a975702ccd2c)
- npm: remove reactify, reset babel [`da65059`](https://github.com/alecdibble/tabtabtab/commit/da65059e87bbda4b1feefbb94820e71d373a6d73)
- npm: update dependencies [`dd19437`](https://github.com/alecdibble/tabtabtab/commit/dd1943774f36b8d9910f9bef4b161beff6a44f43)
- eslint: setup eslint and config [`64f3364`](https://github.com/alecdibble/tabtabtab/commit/64f33648ac9131b26ff3d404501ff0b1807984b9)
- npm: update dependencies [`63cd043`](https://github.com/alecdibble/tabtabtab/commit/63cd043b02797ace9022276917f9dc63587c3831)
- ci: setup nyc and coverage scripts [`e6fe55a`](https://github.com/alecdibble/tabtabtab/commit/e6fe55ab9a7438341cd074262c1732bce0bcc9d7)
- feat: tabtab.install() with prompt (wip) [`f599724`](https://github.com/alecdibble/tabtabtab/commit/f5997246c19e042e9d30654662df53a73882df0d)
- ci: disable nyc for now [`c1e1806`](https://github.com/alecdibble/tabtabtab/commit/c1e180654579890d09e5352522526af4b0992492)
- log: better handling of descriptions [`12d5897`](https://github.com/alecdibble/tabtabtab/commit/12d5897e38958a64f4c05b0ffa4a36210b4efdc8)
- es6: replace vars by const/let [`71ad75a`](https://github.com/alecdibble/tabtabtab/commit/71ad75a882e7fd4ee5bc834fe809192ce0ecfa22)
- feat: avoid adding multiple lines to SHELL scripts [`036d9c0`](https://github.com/alecdibble/tabtabtab/commit/036d9c036b77c0b47469ae38960bfe77401c04de)
- feat: add necessary completion lines in shell config [`2030676`](https://github.com/alecdibble/tabtabtab/commit/20306764122aa7534e26094adaad8049b38d22f7)
- log: fix TABTAB_DEBUG and use it in tests [`dbd6ffb`](https://github.com/alecdibble/tabtabtab/commit/dbd6ffb4e97a0db6eac40b646b93e567996d0e5d)
- examples: add tabtab-test-complete to serve as completion tests [`c0423dc`](https://github.com/alecdibble/tabtabtab/commit/c0423dca0556e1fe6b724ba9806ff9185c650acc)
- cli: test out completions [`c861535`](https://github.com/alecdibble/tabtabtab/commit/c8615352664e19b0f8966cfcd38ee844927f1d51)
- eslint: fix all eslint errros and update config [`bbf2a5b`](https://github.com/alecdibble/tabtabtab/commit/bbf2a5bbdfc2ff317debe93485478f86867098a1)
- fix: ensure fileformat is unix and remove code related to bash-completion [`9b83d76`](https://github.com/alecdibble/tabtabtab/commit/9b83d765c8cb10102bac19113786c0cb9fca2751)
- npm: setup prettier [`a2cd163`](https://github.com/alecdibble/tabtabtab/commit/a2cd163ae19fd465816654ac61f071ddf8744e66)
- node: support for version 10, 8 and 7 [`c01b443`](https://github.com/alecdibble/tabtabtab/commit/c01b44301de30f1be0c0ff7322c5b3357dadd8f2)
- example: remove completion script, all in one [`fae0553`](https://github.com/alecdibble/tabtabtab/commit/fae05531d957c454de732f2de1567731e93783bb)
- completion: now emits the whole line (breaking change) [`75c7b6a`](https://github.com/alecdibble/tabtabtab/commit/75c7b6ac5b96bb85c0ac7047ba6d0a3f82e3e0dd)
- log: slight change to tabtab.log [`1aa7d1a`](https://github.com/alecdibble/tabtabtab/commit/1aa7d1a8146a29f4a0fd454ac6df12ac8f7c8e63)
- eslint: include test dir as well [`345d191`](https://github.com/alecdibble/tabtabtab/commit/345d191a9046a514f52b4af7652abc60dd1477ae)
- babel: remove babel continuation [`6f279be`](https://github.com/alecdibble/tabtabtab/commit/6f279be38b197f3f9e9fcf13feceefb48f9638a9)
- npm: remove prettier / es6-promisify [`b5ab126`](https://github.com/alecdibble/tabtabtab/commit/b5ab126d95d4706a7c4a4da63f031e17b40cfdc8)
- babel: start to remove babel [`7f19043`](https://github.com/alecdibble/tabtabtab/commit/7f19043c2be3461f0d98434a428c46a74a0da186)
- bash: handle semicolon [`51f1de7`](https://github.com/alecdibble/tabtabtab/commit/51f1de7f215dacba5b321daf615ad31d1579eadb)
- fix: a bit more debugging and fix entry point [`4875c90`](https://github.com/alecdibble/tabtabtab/commit/4875c906ea3efa8eb7ccdffcb6a807e0a96f28a7)
- debug: use tabtab debug in all files [`e81aa93`](https://github.com/alecdibble/tabtabtab/commit/e81aa931c8a4996d015de54e287dd3117e2e676b)
- Add .babelrc with preset env [`5f0eaf1`](https://github.com/alecdibble/tabtabtab/commit/5f0eaf1fab2515f26cd9002d8d9552ddbc3843b9)
- complete: always trigger original event based on options.name [`ca0ab39`](https://github.com/alecdibble/tabtabtab/commit/ca0ab3953733e560f4993f26ba2bece54b3516ee)
- debug: dont log into console [`db192d7`](https://github.com/alecdibble/tabtabtab/commit/db192d76419c5773ba899970d0b3c63a1bf413f8)
- parseEnv: change signature to only take environment [`3e60094`](https://github.com/alecdibble/tabtabtab/commit/3e60094f00e6f357da627b7aa13f8dfd055a936d)
- ci: remove npm prune [`7a319e2`](https://github.com/alecdibble/tabtabtab/commit/7a319e22c1f9b83c8e876b21095980b7513ab560)
- debug: change debug for parseEnv, too verbose [`627ef79`](https://github.com/alecdibble/tabtabtab/commit/627ef79636acc116c1da065720b907e5644a3cbc)
- ci(package.json): run nyc on tests [`eff6e95`](https://github.com/alecdibble/tabtabtab/commit/eff6e9552cf75232d04445474f975f5b2a1b0b10)
- mocha: increase timeout to avoid failure on node 6 [`fc97626`](https://github.com/alecdibble/tabtabtab/commit/fc976262a37d6da3ef86eea7ff39883c6c8872fe)
- Do NOT test with cache for the moment [`3cf9115`](https://github.com/alecdibble/tabtabtab/commit/3cf911529cbe32dd32300a008f605b723869fb03)
- ci: forget about node 6 for the moment [`aa7ade3`](https://github.com/alecdibble/tabtabtab/commit/aa7ade38aefd2cd1cf2a06a0544e37d8820d7833)
- commands: remove options.auto mandatory in uninstall [`36dce25`](https://github.com/alecdibble/tabtabtab/commit/36dce25198e582b629a779d8e4e8a0cd37ac7df9)
- uninstall: use default options on uninstall [`7e179b6`](https://github.com/alecdibble/tabtabtab/commit/7e179b6fa3e743e514fcbda9171c059530de9aa6)
- fix: package.json syntax [`0a0238b`](https://github.com/alecdibble/tabtabtab/commit/0a0238bac7d56d0bfbe229a0adcce862c4bb52cf)
- Update package.json [`f3a9580`](https://github.com/alecdibble/tabtabtab/commit/f3a95802b777a5cbc94ea144a5cdee9f168f265c)
- add .gitattributes to force unix line endings [`9a7440e`](https://github.com/alecdibble/tabtabtab/commit/9a7440edeaaef13b04cfba2af67365cf2a90c6bb)

## [v2.2.2](https://github.com/alecdibble/tabtabtab/compare/v2.2.1...v2.2.2) - 2017-01-06

### Merged

- fix(win32): fix usage of SHELL environment variable when it is not set [`#30`](https://github.com/alecdibble/tabtabtab/pull/30)

## [v2.2.1](https://github.com/alecdibble/tabtabtab/compare/v2.2.0...v2.2.1) - 2016-10-13

### Commits

- fix: create duplicate-free version of completion items accross evt listeners [`dc8b587`](https://github.com/alecdibble/tabtabtab/commit/dc8b58795d57a010800e1f858580217d141aef8e)

## [v2.2.0](https://github.com/alecdibble/tabtabtab/compare/v2.1.1...v2.2.0) - 2016-10-11

### Commits

- feat(fish): handle description by adding a tab character between name and description [`9290dcc`](https://github.com/alecdibble/tabtabtab/commit/9290dcc042db1bf960ba0b91dd55696660cb9970)

## [v2.1.1](https://github.com/alecdibble/tabtabtab/compare/v2.1.0...v2.1.1) - 2016-10-09

### Commits

- fix(zsh): fix uninstall typo in zshrc (instead of zshhrc) [`3d29317`](https://github.com/alecdibble/tabtabtab/commit/3d293170db57a4c74d8ced7a919e527178bfb2fc)

## [v2.1.0](https://github.com/alecdibble/tabtabtab/compare/v2.0.2...v2.1.0) - 2016-10-09

### Commits

- fix(fish): Disable description in fish completion per command / options [`1f04613`](https://github.com/alecdibble/tabtabtab/commit/1f04613f5db70e0aaa265df7f8397fcd7f962a76)
- fix(fish): fix COMP_LINE by appending a space so that prev is correctly positioned [`861f8ef`](https://github.com/alecdibble/tabtabtab/commit/861f8ef2290b2cf61d238a8ff1b648d2712fb359)
- feat(fish): prevent filenames from being completed [`282b941`](https://github.com/alecdibble/tabtabtab/commit/282b94122938c0e26db8a54f30c0e94a1fb2e694)

## [v2.0.2](https://github.com/alecdibble/tabtabtab/compare/v2.0.1...v2.0.2) - 2016-10-06

### Commits

- fix: have output done after recv to handle async completion handler [`d8596ed`](https://github.com/alecdibble/tabtabtab/commit/d8596edb4e1c8be8cd66c22c350e87b49f00aa95)
- Remove bake from package.json [`c306bce`](https://github.com/alecdibble/tabtabtab/commit/c306bcefc044e488ba3b99df968b5f291001fb2f)

## [v2.0.1](https://github.com/alecdibble/tabtabtab/compare/v2.0.0...v2.0.1) - 2016-10-06

### Commits

- Remove src/ folder and babel compiled files [`8531a62`](https://github.com/alecdibble/tabtabtab/commit/8531a62fa8b35a3ffedcde58f1838420fdbd238a)
- rm Makefile [`d717594`](https://github.com/alecdibble/tabtabtab/commit/d717594ef80d3e74e4b6968ff65b8ffdfbd37ebd)
- fix: have uninstall command working as expected by fixing regexp [`21e2de6`](https://github.com/alecdibble/tabtabtab/commit/21e2de6b95688b72b5cddbf549c119b62770c96a)

## [v2.0.0](https://github.com/alecdibble/tabtabtab/compare/v1.4.3...v2.0.0) - 2016-09-30

## [v1.4.3](https://github.com/alecdibble/tabtabtab/compare/v1.4.2...v1.4.3) - 2016-09-30

### Merged

- allow installing on a `windows` system when running in a `git bash` [`#27`](https://github.com/alecdibble/tabtabtab/pull/27)
- add $CURSOR for position in zsh.sh script [`#24`](https://github.com/alecdibble/tabtabtab/pull/24)

### Fixed

- add $cursor for position in zsh.sh script [`#23`](https://github.com/alecdibble/tabtabtab/issues/23)

### Commits

- add babel'ed files to `src` folder so that you can directly install it from github [`4cd37ec`](https://github.com/alecdibble/tabtabtab/commit/4cd37ecc2772964a79209500a2a60de03a14b2ec)
- src: update build [`1c5619d`](https://github.com/alecdibble/tabtabtab/commit/1c5619db8348dca61833620ee46c142a880bff36)

## [v1.4.2](https://github.com/alecdibble/tabtabtab/compare/v1.4.1...v1.4.2) - 2016-05-21

### Commits

- fix(babel): remove transform-runtime plugin [`845eb54`](https://github.com/alecdibble/tabtabtab/commit/845eb54c2c31ed28a3e0dfd668341831fbb86d5a)

## [v1.4.1](https://github.com/alecdibble/tabtabtab/compare/v1.4.0...v1.4.1) - 2016-05-21

## [v1.4.0](https://github.com/alecdibble/tabtabtab/compare/v1.3.0...v1.4.0) - 2016-05-21

### Fixed

- feat(description): Handle zsh description using _describe fn [`#19`](https://github.com/alecdibble/tabtabtab/issues/19)

### Commits

- rework cache, fix bash completion handling [`b7cecf7`](https://github.com/alecdibble/tabtabtab/commit/b7cecf7bd7e7ff8325a3f7643d4faf9fce2d4e77)
- feat(uninstall): Implement uninstall command and --auto flag [`de37993`](https://github.com/alecdibble/tabtabtab/commit/de3799343d5d30835383250887531c29c11f91ae)
- fix(completion): gather results and write only once to STDOUT [`b928bc9`](https://github.com/alecdibble/tabtabtab/commit/b928bc987e2f9116325040deb4dbe65e203868e8)
- Fix zsh template script [`a22e6b0`](https://github.com/alecdibble/tabtabtab/commit/a22e6b049b0ad67874a7b79010c111f0e96a0bec)
- zsh: check for compdef [`f216888`](https://github.com/alecdibble/tabtabtab/commit/f216888de7200ca7155c0de0ae0f238c993a81ed)
- fix: Skip completion install for win32 platform or unknown shell [`c4f6073`](https://github.com/alecdibble/tabtabtab/commit/c4f6073c1a25413eecbc2519712ab20ca05d6fdd)
- babel: add plugin default transform [`1dcc302`](https://github.com/alecdibble/tabtabtab/commit/1dcc3024edc44eb8f5edaa189a24f6c4faec3466)
- fix(bash): Silently fail if pkg-config bash-completion exists with non 0 [`0765749`](https://github.com/alecdibble/tabtabtab/commit/07657490f381d147072064adb64edc30c5541acf)
- feat(debug): automatically JSON.stringify non string objects [`e4423f8`](https://github.com/alecdibble/tabtabtab/commit/e4423f81f85ae74ea348c5f325e4fe7eff3b6cdf)

## [v1.3.0](https://github.com/alecdibble/tabtabtab/compare/v1.2.1...v1.3.0) - 2016-05-08

### Fixed

- feat(cache): Implement cache TTL (default: 5 min) [`#20`](https://github.com/alecdibble/tabtabtab/issues/20)
- feat(cache): Add option to enable / disable cache [`#20`](https://github.com/alecdibble/tabtabtab/issues/20)

## [v1.2.1](https://github.com/alecdibble/tabtabtab/compare/v1.2.0...v1.2.1) - 2016-05-08

## [v1.2.0](https://github.com/alecdibble/tabtabtab/compare/v1.1.1...v1.2.0) - 2016-05-08

### Commits

- feat: implement a basic cache mechanism [`bb4216c`](https://github.com/alecdibble/tabtabtab/commit/bb4216c5b4abe5236ed5c03d96575e8d678c13d0)
- fix: Use Object.assign polyfill to run on older version of node [`157057a`](https://github.com/alecdibble/tabtabtab/commit/157057a0f25bca2a6ab9ee5f3a2b0d6005c1f724)

## [v1.1.1](https://github.com/alecdibble/tabtabtab/compare/v1.1.0...v1.1.1) - 2016-05-01

### Commits

- fix: more generic assert on prompt [`bbcd350`](https://github.com/alecdibble/tabtabtab/commit/bbcd350379a1d5bf40fe2381d5fc7544b054d58b)

## [v1.1.0](https://github.com/alecdibble/tabtabtab/compare/v1.0.5...v1.1.0) - 2016-05-01

### Commits

- example: have yo-complete based on yeoman-environment and parse-help [`115fdae`](https://github.com/alecdibble/tabtabtab/commit/115fdaec737ea64e3016b113b5b77360c38637fb)
- Add notes on debug and log output [`e42149a`](https://github.com/alecdibble/tabtabtab/commit/e42149a1349331ab6bea22497731b2e8a55e8d37)
- feat(completion): Enhance package.json completion to support last word [`ce794d4`](https://github.com/alecdibble/tabtabtab/commit/ce794d4a3a14e6f7519e027c240b9b7c0f536a96)
- feat(completion): Emit completion events along package.json results [`2ed8ef5`](https://github.com/alecdibble/tabtabtab/commit/2ed8ef560610db0c1da05b14f6a0e79197333858)
- fish - set default description to package name [`9f8e934`](https://github.com/alecdibble/tabtabtab/commit/9f8e9345657fc99655ddef6eef40c16a38c848c8)
- fix(fish): Better handling of description [`779a188`](https://github.com/alecdibble/tabtabtab/commit/779a188d5dbc3dd591938a56e2c9babf28249be3)

## [v1.0.5](https://github.com/alecdibble/tabtabtab/compare/v1.0.4...v1.0.5) - 2016-04-30

### Commits

- release: git push tags && npm publish [`29035d8`](https://github.com/alecdibble/tabtabtab/commit/29035d8d5ddc0c57c75b101ce0dd827e543bb1ef)

## [v1.0.4](https://github.com/alecdibble/tabtabtab/compare/v1.0.3...v1.0.4) - 2016-04-30

### Commits

- Change standard-version msg [`d1d19f6`](https://github.com/alecdibble/tabtabtab/commit/d1d19f6b15705bbc50a8f953f2e8a0738b2159fa)

## [v1.0.3](https://github.com/alecdibble/tabtabtab/compare/v1.0.1...v1.0.3) - 2016-04-30

### Commits

- chore(release): 1.0.3 [`dbbdcac`](https://github.com/alecdibble/tabtabtab/commit/dbbdcac74412ccc5ef00d42dd3544d9b01f5bfcc)
- fix(babel): Add babel as prepublish step [`97fc9ce`](https://github.com/alecdibble/tabtabtab/commit/97fc9ceec13931d8b40aeb15297af9edeb6db6a9)

## [v1.0.1](https://github.com/alecdibble/tabtabtab/compare/v1.0.0...v1.0.1) - 2016-04-29

### Merged

- fix: zsh (on osx anyway) seems to require a space before the ]] [`#16`](https://github.com/alecdibble/tabtabtab/pull/16)

### Commits

- examples: add yo-complete example [`1a18381`](https://github.com/alecdibble/tabtabtab/commit/1a1838146065230a488e2e1de3deedef224f448b)
- fix: fix fish shell script to properly escape variables [`6f9664e`](https://github.com/alecdibble/tabtabtab/commit/6f9664e49cd4626409f87c009103f9bc23ae5c70)
- bash: apply same spacing before closing ] [`50f0340`](https://github.com/alecdibble/tabtabtab/commit/50f034057d14cc5535804afc9d968cc813490087)
- zsh (on osx anyway seems to require a space before the ]] [`1f9f983`](https://github.com/alecdibble/tabtabtab/commit/1f9f983194a664cb385bbd1b0ba55b833b7c3249)

## [v1.0.0](https://github.com/alecdibble/tabtabtab/compare/v1.0.0-pre...v1.0.0) - 2016-04-26

### Commits

- Check in examples [`82de5ef`](https://github.com/alecdibble/tabtabtab/commit/82de5ef2cd8bab7c2b5ebe30cce90a786e268ccb)
- fix: check in example and fix bower-complete package.json [`c46185f`](https://github.com/alecdibble/tabtabtab/commit/c46185ffd6663dc3fd9508a1c86583e5788f6477)

## [v1.0.0-pre](https://github.com/alecdibble/tabtabtab/compare/v0.0.4...v1.0.0-pre) - 2016-04-26

### Commits

- Main API and plumbing system done [`c3cba1d`](https://github.com/alecdibble/tabtabtab/commit/c3cba1d0cccb98717340e1f594c21a09a97747b9)
- Cleanup old dir [`45b09af`](https://github.com/alecdibble/tabtabtab/commit/45b09af17c7897573097bb3de774d731c948f1df)
- Prompt user for completion script installation method [`73f6090`](https://github.com/alecdibble/tabtabtab/commit/73f60907f17dfb2d66d7c26fba8ac9d3f9b7ff88)
- rm old completion file [`cef3c00`](https://github.com/alecdibble/tabtabtab/commit/cef3c003b1ee85ca1cbc991b63587547de4ed3a8)
- Update docs, less verbose debug output [`927e08c`](https://github.com/alecdibble/tabtabtab/commit/927e08c39d0a76191dac37b7433b39da4fa80974)
- Init v1 [`3314024`](https://github.com/alecdibble/tabtabtab/commit/331402462a639f2111c2df3112d6ad3b29a8b5d3)
- TomDocify [`9587418`](https://github.com/alecdibble/tabtabtab/commit/95874188b01421e1850fc344c70a91c50755cb82)
- Init command plumbing system [`0361905`](https://github.com/alecdibble/tabtabtab/commit/0361905bf777b9014003b012387193b8dfdd4d97)
- Implement fish bridge, template system depending on $SHELL [`1823230`](https://github.com/alecdibble/tabtabtab/commit/18232300a0bb80d2c715a9b87f4eab69a239f744)
- Shell adapters, handle bash / zsh / fish [`ab90a1a`](https://github.com/alecdibble/tabtabtab/commit/ab90a1ae2920eb2a15913da85bfb9225194af7aa)
- More docs [`a483822`](https://github.com/alecdibble/tabtabtab/commit/a483822ab72a20dfc1783a432d4490f4cb897b43)
- install - check for existing content before writing [`2250e08`](https://github.com/alecdibble/tabtabtab/commit/2250e0830943d59ea0a3d490aaa49f3454aec088)
- More docs [`731222e`](https://github.com/alecdibble/tabtabtab/commit/731222e68dbe912cfd85366093c16c251f04c875)
- Implement json based completion results [`5421395`](https://github.com/alecdibble/tabtabtab/commit/542139513e576c79f48acfcbc8ffff013dcad148)
- Support completion item description for fish, still need work to do on zsh [`5dfc6f0`](https://github.com/alecdibble/tabtabtab/commit/5dfc6f031ae6f18caa90f3d15e3e9b6346a6704d)
- wip install / uninstall [`16cdf73`](https://github.com/alecdibble/tabtabtab/commit/16cdf7390e42ccab025563df427b4dc03e0dd890)
- Handle permission issue [`c44ef31`](https://github.com/alecdibble/tabtabtab/commit/c44ef315f7c10278bd5bd39bf56fbfff27e48f75)
- Ensure directory exists before writing [`bed76b3`](https://github.com/alecdibble/tabtabtab/commit/bed76b35a0795230b15d6df08396cf2e9f6e0fc0)
- Event chaining, walking up the line untill it find a listener [`3c4241c`](https://github.com/alecdibble/tabtabtab/commit/3c4241c51d68a33b52c287818d98c5d88ff93c91)
- API example [`4c4d86c`](https://github.com/alecdibble/tabtabtab/commit/4c4d86c876bdf47b286d3eaf196a51a4aabe342c)
- docs task [`305b0b4`](https://github.com/alecdibble/tabtabtab/commit/305b0b4f0015a39cbc71843d2207f4b02bd0517a)
- ghpages task [`62c4362`](https://github.com/alecdibble/tabtabtab/commit/62c4362434a76fd1657059ccc2d0c7968ecd858d)
- doc -wrong prefix [`2c8b91a`](https://github.com/alecdibble/tabtabtab/commit/2c8b91a817044328c598f0b004d96388369565f4)
- travis - run mocha with babel-node [`962127c`](https://github.com/alecdibble/tabtabtab/commit/962127c3824615bca48cf008c6d73559c08610a4)
- travis [`5fe6b73`](https://github.com/alecdibble/tabtabtab/commit/5fe6b73e0a970cb31e962f8c1a350ec5e9495095)
- badge version [`751af46`](https://github.com/alecdibble/tabtabtab/commit/751af468b68d9140e3fd1144ec0139427e37c076)
- travis - add babelrc file [`8a2a29b`](https://github.com/alecdibble/tabtabtab/commit/8a2a29b4a2f4a9b0f100ec3d87e4b7a08f943f4b)
- travis - babel compile before test [`ddac422`](https://github.com/alecdibble/tabtabtab/commit/ddac4220c10f255ba82562f79d78964dbea5162c)
- Move old stuff to .old [`94369a0`](https://github.com/alecdibble/tabtabtab/commit/94369a065d98d52ed4b1b4daef52157112084ee8)
- init completion directory registry [`3f92281`](https://github.com/alecdibble/tabtabtab/commit/3f92281dff40f56364bf3dec070d179452ed1839)
- Check in screenshots [`b7e3724`](https://github.com/alecdibble/tabtabtab/commit/b7e37248108f24aba9d9e41becdadc80e1db72c8)
- Move old stuff [`a53de4a`](https://github.com/alecdibble/tabtabtab/commit/a53de4a509f653fb361d961ea3fc98e174ddc81c)

## [v0.0.4](https://github.com/alecdibble/tabtabtab/compare/v0.0.3...v0.0.4) - 2015-06-06

### Merged

- Issues with tabtab in zsh. [`#10`](https://github.com/alecdibble/tabtabtab/pull/10)
- Fix typo [`#11`](https://github.com/alecdibble/tabtabtab/pull/11)

### Commits

- Updated the completion script to match current npm output. [`be1c512`](https://github.com/alecdibble/tabtabtab/commit/be1c512fde5d7c64e9725e3cdf89e343ac8945b7)
- Added default filesystem matching. [`f57a254`](https://github.com/alecdibble/tabtabtab/commit/f57a2545ed45b2ceaef74d9f559e5588fce7d585)
- :book: Fix typo [`45c6ead`](https://github.com/alecdibble/tabtabtab/commit/45c6eadc3eeadaea4994a66272210e81ec9e17a6)
- Didn't realize the line had {completer} before. Changing back. [`10f3472`](https://github.com/alecdibble/tabtabtab/commit/10f3472f1886ac3a4a6c9929a3ceefcb6223d242)
- Added back new line. [`c74f7ab`](https://github.com/alecdibble/tabtabtab/commit/c74f7ab23bc37818d997578c7ba607c2f8c00a86)

## [v0.0.3](https://github.com/alecdibble/tabtabtab/compare/v0.0.2...v0.0.3) - 2015-01-26

### Merged

- Allow completing long options [`#5`](https://github.com/alecdibble/tabtabtab/pull/5)
- Catching EPIPE error caused by `source` closing file descriptor before reading it [`#4`](https://github.com/alecdibble/tabtabtab/pull/4)

### Fixed

- Fix #3 - Add license info [`#3`](https://github.com/alecdibble/tabtabtab/issues/3)

### Commits

- rm old .pkgrc file [`42bcf50`](https://github.com/alecdibble/tabtabtab/commit/42bcf50dbf2b4d6a6533c08f56534e08f17847f7)
- Catching error caused by `source` closing file argument before reading from it. [`4fca6aa`](https://github.com/alecdibble/tabtabtab/commit/4fca6aaf04b30b04e3c66e46dd87b90c43b49bbc)
- travis - node 0.10 [`e13de5b`](https://github.com/alecdibble/tabtabtab/commit/e13de5b9ab83e480ba1c77a2fa7e9aeb57df3cdb)

## [v0.0.2](https://github.com/alecdibble/tabtabtab/compare/v0.0.1...v0.0.2) - 2012-02-08

### Commits

- tidy up the whole mess. remove unused / unnecessary code [`6a1e9c3`](https://github.com/alecdibble/tabtabtab/commit/6a1e9c3879a454b1db4f277e26c1e4555390516a)
- add missing devDependency [`fab4faf`](https://github.com/alecdibble/tabtabtab/commit/fab4faf8115416902c64539472881c18d86d47eb)
- bumping version [`cd56910`](https://github.com/alecdibble/tabtabtab/commit/cd56910a847e3d77a5b3a8ed168ff81659f8bccd)
- correct abbrev with `-` in it [`0b51ad8`](https://github.com/alecdibble/tabtabtab/commit/0b51ad8140f152cdbbd15ed9bdbab46309cb8b82)

## v0.0.1 - 2011-11-11

### Commits

- edit package.json [`9be6eba`](https://github.com/alecdibble/tabtabtab/commit/9be6eba26133bed9d21bd0b5329dcc39b00d2449)
- return warn messages as state [`8da7d5b`](https://github.com/alecdibble/tabtabtab/commit/8da7d5bc2dc6cf781e7065790964f259c214db36)
- warn without exiting with error, and ensure numbers on parsed env [`34a2ede`](https://github.com/alecdibble/tabtabtab/commit/34a2ede7ebb5d0f21ad8021c712adaf87dc056a8)
- rm gendoc script [`06d3a7a`](https://github.com/alecdibble/tabtabtab/commit/06d3a7a4772edbc684d4777c88b9b84ef882dd0c)
- add gendoc script [`dbd4739`](https://github.com/alecdibble/tabtabtab/commit/dbd4739c965529be5f71e6fa30b2765e5efc2ea5)
- package.json: specify directories for the docs task [`08a25ef`](https://github.com/alecdibble/tabtabtab/commit/08a25ef1f829612fd8cf96b16e545bad42d82f49)
- add some completion install/uninstall docs [`46d324a`](https://github.com/alecdibble/tabtabtab/commit/46d324a9d72ecb9bcaa42d37d24c006b7b41e189)
- rename to tabtab and edit test assert to use dynamic path [`061a357`](https://github.com/alecdibble/tabtabtab/commit/061a357ae5af36541a52bf205b610aba0700ba01)
- add vows test suite for completion output and install/uninstall cmd [`029de43`](https://github.com/alecdibble/tabtabtab/commit/029de431ac136a92cf8498011c6937e08feb9da0)
- edit docs.js comments and rm lib/cli.js (was empty anyway) [`4abc675`](https://github.com/alecdibble/tabtabtab/commit/4abc675573a6b9107be8eb6caa2636cb400c46aa)
- add pkgrc help command [`fff228f`](https://github.com/alecdibble/tabtabtab/commit/fff228f68060ba567a463c1445c5f31c1654dd3b)
- add install/uninstall helper [`6cfb0ee`](https://github.com/alecdibble/tabtabtab/commit/6cfb0ee6a40684e918463b30b15240c939c132a3)
- some docs, have more to write [`9ccd0d7`](https://github.com/alecdibble/tabtabtab/commit/9ccd0d7841fad68552bee1d638b3fb2a51ac260d)
- add play-complete script, completion from `play help` output [`f8347bb`](https://github.com/alecdibble/tabtabtab/commit/f8347bb7d4d9949b758eb1a0b7b4ebf800f3bd9d)
- Use readline's default filename completion if no matches. [`5ea2d4c`](https://github.com/alecdibble/tabtabtab/commit/5ea2d4cb8a3159551e508906019ef698dcab1469)
- log instruction on examples when not called within completion context [`bfc6ad0`](https://github.com/alecdibble/tabtabtab/commit/bfc6ad064152268c23ec6557073e0ab84894224b)
- parse ``` and ~~~~ special code marker in markdowns [`31ee00f`](https://github.com/alecdibble/tabtabtab/commit/31ee00fad380e363fe9767df2d778326bbf0f846)
- add help module, takes a file input (md, js or cs) and man a generated manpage [`11d5d70`](https://github.com/alecdibble/tabtabtab/commit/11d5d70559205d16fd792f10c644f3c3d91ce779)
- add basic script for vagrant completion [`5a8fd4d`](https://github.com/alecdibble/tabtabtab/commit/5a8fd4dce74ed6275f1a4ecf56e7c0473a88fc31)
- move helper functions to completion module [`5fc9fa0`](https://github.com/alecdibble/tabtabtab/commit/5fc9fa058f37b8b8d5a7028c13ea1ad814c9de5b)
- add cake/rake completion, very similar [`92f125f`](https://github.com/alecdibble/tabtabtab/commit/92f125f4bcc4dc7adc3e245754b656e104355c60)
- add completer options, decouple completed process from completer process [`c864c9d`](https://github.com/alecdibble/tabtabtab/commit/c864c9d66e7900a179f00195f43d9bcb4ccada49)
- completion: add cakefile completion, testing options/tasks completion [`33c272b`](https://github.com/alecdibble/tabtabtab/commit/33c272b5be8641c7be1ffd447aa616dba9e9d00c)
- completion: add optimist completion, have to parse out the help output [`6c1b1bb`](https://github.com/alecdibble/tabtabtab/commit/6c1b1bb49cfc9ad641e350a09b3fcb1fb240a20d)
- completion: add basic abbrev support and test with nopt/commander opt [`a857dd2`](https://github.com/alecdibble/tabtabtab/commit/a857dd28b167d15b2c8ef45baaf3e3d02e23046a)
- played a little with nopt/commander options and basic completion [`c6fa6de`](https://github.com/alecdibble/tabtabtab/commit/c6fa6de2860e050dde8b02e8cff71f17d5f041d4)
- add prev to options parsed from compgen [`cfb2894`](https://github.com/alecdibble/tabtabtab/commit/cfb2894f5c4cd8c0f56dad31e7662fbf6c2bae87)
- add some commander/optimist/nopt examples script [`22e0681`](https://github.com/alecdibble/tabtabtab/commit/22e06814744b52c7d3b4450ea52c1cd5e1ab7f0d)
- completion - install instruction and simple line parsing/callback api [`ce1f1f3`](https://github.com/alecdibble/tabtabtab/commit/ce1f1f3960939b0a50c2806feddf8640893d69cd)
- completion start [`94b103f`](https://github.com/alecdibble/tabtabtab/commit/94b103f086f9d22d4a77a7de450976349a2e2a52)
- initial config work, merge of global/local rc file [`64a0f7a`](https://github.com/alecdibble/tabtabtab/commit/64a0f7a268398ddea17163f9edae4e64cb51fbc6)
- a start [`a46ca29`](https://github.com/alecdibble/tabtabtab/commit/a46ca2996264c6c4b2bf300855bdd11f3f4dadb1)