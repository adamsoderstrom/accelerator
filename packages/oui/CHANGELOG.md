# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [4.0.2](https://github.com/noaignite/accelerator/compare/@noaignite/oui@4.0.1...@noaignite/oui@4.0.2) (2024-01-19)

**Note:** Version bump only for package @noaignite/oui





## [4.0.1](https://github.com/noaignite/accelerator/compare/@noaignite/oui@4.0.0...@noaignite/oui@4.0.1) (2023-03-02)

**Note:** Version bump only for package @noaignite/oui





# [4.0.0](https://github.com/noaignite/accelerator/compare/@noaignite/oui@3.3.4...@noaignite/oui@4.0.0) (2023-01-27)


### Features

* **AspectRatio:** remove component ([2393172](https://github.com/noaignite/accelerator/commit/23931722f5e2e9c6978fa2e3a2a108aa74454dd6))
* bump node engine to 14 ([72f5942](https://github.com/noaignite/accelerator/commit/72f594247b275a60b45890efc06d43c1241c6b24))
* **InView:** allow children to be of type function with inView as argument ([4695a02](https://github.com/noaignite/accelerator/commit/4695a02a0f07059ad11c864bd7b4af8fc0ae7f6f))
* **MediaBase, Media:** add native lazy loading and ability to set aspect ratio ([c6ec92f](https://github.com/noaignite/accelerator/commit/c6ec92fa03f08815b72c1ea0728468771bfaa7ae))
* **MediaReveal:** no longer composed with AspectRatio component ([da3048b](https://github.com/noaignite/accelerator/commit/da3048b5f0d5182e86b7c9b10b4fb86930571ae7))
* **ScrollProgress:** add requestAnimationFrame and a new friction prop ([1497a9e](https://github.com/noaignite/accelerator/commit/1497a9ef6f15e5598c9e574d7e2bbf7e6eb29077))
* **ScrollProgress:** friction & precision can now be strings and rename internal state vars ([e95ef5f](https://github.com/noaignite/accelerator/commit/e95ef5f341b9d507f1452a3a17dd2c9bea82e092))
* **utils:** add extra safety conditional and update util tests ([8616ac5](https://github.com/noaignite/accelerator/commit/8616ac540a72466ccc2a45712fb56ae4bae1ec36))


### BREAKING CHANGES

* **MediaBase, Media:** The Media component no longer accepts individual breakpoints as arrays and the
placeholder prop has been removed.
* **MediaReveal:** No longer takes width, height or ratio for styling aspect ratios
* **AspectRatio:** AspectRatio component has been removed.
* **ScrollProgress:** The bounds key has now been removed from the onChange callback arguments.
* Node 12 is no longer supported as it's no longer maintained





## [3.3.4](https://github.com/noaignite/accelerator/compare/@noaignite/oui@3.3.3...@noaignite/oui@3.3.4) (2022-11-04)

**Note:** Version bump only for package @noaignite/oui





## [3.3.3](https://github.com/noaignite/accelerator/compare/@noaignite/oui@3.3.2...@noaignite/oui@3.3.3) (2022-08-09)


### Bug Fixes

* **createMediaPreload:** now correctly renders single link tag when component is img ([68be150](https://github.com/noaignite/accelerator/commit/68be150e1c010835c7509d1216affa4edb78b4c9))





## [3.3.2](https://github.com/noaignite/accelerator/compare/@noaignite/oui@3.3.1...@noaignite/oui@3.3.2) (2022-06-08)

**Note:** Version bump only for package @noaignite/oui





## [3.3.1](https://github.com/noaignite/accelerator/compare/@noaignite/oui@3.3.0...@noaignite/oui@3.3.1) (2022-06-01)

**Note:** Version bump only for package @noaignite/oui





# [3.3.0](https://github.com/noaignite/accelerator/compare/@noaignite/oui@3.1.0...@noaignite/oui@3.3.0) (2022-03-07)


### Features

* **ImageZoom:** add onZoomIn & onZoomOut methods ([7a500e0](https://github.com/noaignite/accelerator/commit/7a500e09d6d62d399498e67e46a5c65cf9e7c846))
* **utils:** add new useLatest hook ([57cd417](https://github.com/noaignite/accelerator/commit/57cd417a8abab1a176fd06d74efbad321569306a))





# [3.2.0](https://github.com/noaignite/accelerator/compare/@noaignite/oui@3.1.0...@noaignite/oui@3.2.0) (2022-02-28)


### Features

* **ImageZoom:** add onZoomIn & onZoomOut methods ([7a500e0](https://github.com/noaignite/accelerator/commit/7a500e09d6d62d399498e67e46a5c65cf9e7c846))
* **utils:** add new useLatest hook ([57cd417](https://github.com/noaignite/accelerator/commit/57cd417a8abab1a176fd06d74efbad321569306a))





# [3.1.0](https://github.com/noaignite/accelerator/compare/@noaignite/oui@3.0.3...@noaignite/oui@3.1.0) (2022-02-15)


### Features

* **ImageZoom:** add touch support ([314630b](https://github.com/noaignite/accelerator/commit/314630b2833757cc0d2b34bc285dd0d8344bc402))
* **ImageZoom:** image is now 'climbable' on touch devices" ([2bea3a3](https://github.com/noaignite/accelerator/commit/2bea3a38d8a0e04a6a046218a86fc3ec2973bc43))





## [3.0.3](https://github.com/noaignite/accelerator/compare/@noaignite/oui@3.0.2...@noaignite/oui@3.0.3) (2022-01-24)

**Note:** Version bump only for package @noaignite/oui





## [3.0.2](https://github.com/noaignite/accelerator/compare/@noaignite/oui@3.0.1...@noaignite/oui@3.0.2) (2021-12-11)

**Note:** Version bump only for package @noaignite/oui





## [3.0.1](https://github.com/noaignite/oui/compare/@noaignite/oui@3.0.0...@noaignite/oui@3.0.1) (2021-12-02)


### Bug Fixes

* **ImageZoom, MediaReveal:** @mui/core was renamed to @mui/base ([2f9fefc](https://github.com/noaignite/oui/commit/2f9fefcff4c496276e2b41550d647bcdf164e259))





# [3.0.0](https://github.com/noaignite/oui/compare/@noaignite/oui@2.0.1...@noaignite/oui@3.0.0) (2021-12-02)


### Bug Fixes

* **ImageZoom:** add missing imageZoomClasses to components common exports file ([0718a8e](https://github.com/noaignite/oui/commit/0718a8ee0bece89ab3128b062d73d4dc936cca71))
* **MediaReveal:** correct name of get utility class helper ([7e550f5](https://github.com/noaignite/oui/commit/7e550f5fcdced3971a7d72317e1e13745229daab))


### Features

* **ImageZoom:** add new image zoom component ([c208255](https://github.com/noaignite/oui/commit/c20825523fe0f6ee98d8e1132aa1e94163108ffa))
* **utils:** add new getObserverInstance util to manage intersection observer instances ([1108465](https://github.com/noaignite/oui/commit/1108465302a8c3bd17ada411cb174cb8bab6448e))
* **MediaReveal:** now composed with AspectRatio adding additional functionality ([c6f8cd2](https://github.com/noaignite/oui/commit/c6f8cd20965de3dd905b55e1e3ecd8556b9afd52))
* **AspectRatio:** width, height & ratio now support more data types ([57b675e](https://github.com/noaignite/oui/commit/57b675e2945b2c1a2c9f5f024a306563e34febe9))
* **utils:** add new createMediaPreload util to match Media generatePreload interface ([9531eb3](https://github.com/noaignite/oui/commit/9531eb3fb9866d72c4ef6e8c1cc9fa27bc109b3f))


### BREAKING CHANGES

* **MediaReveal:** getAvatarUtilityClass no longer exists







**Note:** Version bump only for package @noaignite/oui
