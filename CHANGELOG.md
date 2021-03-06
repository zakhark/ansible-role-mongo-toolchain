# [1.6.0](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/compare/v1.5.0...v1.6.0) (2020-02-27)


### Bug Fixes

* Add private key setup ([b5dfd58](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/b5dfd5821fee4566073f9a7a5de1a6fbd9fd9488))


### Features

* Add rhel7 support ([f0bf919](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/f0bf919150dbf483917b09c96035fe5012928467))
* Upgrade to molecule 3 ([28b7f0e](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/28b7f0e9ed295e67eb478664fc3527d9e08d9444))

# [1.5.0](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/compare/v1.4.0...v1.5.0) (2020-02-07)


### Features

* Pass delete first var to parent tc role ([cd041e8](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/cd041e8545f86302d13a4366659c70dbc26bba88))

# [1.4.0](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/compare/v1.3.1...v1.4.0) (2020-01-30)


### Features

* Added RHEL6 support ([e0b8a08](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/e0b8a084f74e850a057e48d092cfb4fd52878416))

## [1.3.1](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/compare/v1.3.0...v1.3.1) (2019-12-17)


### Bug Fixes

* Removed unused architecture variable ([62d7a18](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/62d7a18f2d00116977860cdf370e92dee7a96ad8))

# [1.3.0](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/compare/v1.2.4...v1.3.0) (2019-11-14)


### Bug Fixes

* Changed variable for final destination ([b7b312a](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/b7b312aaeeb73da9f961af2948374c89db5d6165))
* Changed variables to correct name and values ([3831e99](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/3831e996f640e64c66bafaf794547d79feec7852))
* Renamed variables to be passed in meta ([b23e1b8](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/b23e1b87258504b1c2bebe8f4f6b7249f483f27b))


### Features

* Create version file for mongo toolchain ([200f286](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/200f2866df91d5a8e279549336704665a373e258))

## [1.2.4](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/compare/v1.2.3...v1.2.4) (2019-11-05)


### Bug Fixes

* Fixed the "creates" directory for ins script ([ec7cae4](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/ec7cae4b36f3566b57e66a51e7c8354cf3a766f0))

## [1.2.3](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/compare/v1.2.2...v1.2.3) (2019-11-05)


### Bug Fixes

* Added become permissions to install script ([bc4db17](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/bc4db17f03cb3846477c3378543e4eb1326ba416))

## [1.2.2](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/compare/v1.2.1...v1.2.2) (2019-10-24)


### Bug Fixes

* Adding missing toolchain install script ([734964f](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/734964fd4a5ded6a7075229974fd6bd6d540a06f))

## [1.2.1](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/compare/v1.2.0...v1.2.1) (2019-10-24)


### Bug Fixes

* Create and use the revisions directory ([302b45d](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/302b45d7f07cc9cc4145c2aad9b89ec3bfbfb820))
* Vars were not being passed properly in meta ([6f0b027](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/6f0b0275f183b6c2848ad12968e7bee29886a2e3))

# [1.2.0](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/compare/v1.1.1...v1.2.0) (2019-10-18)


### Features

* added RHEL8 support ([1f89203](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/1f892039df134ce1a9013f8573665d1c2a6b3c1c))

## [1.1.1](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/compare/v1.1.0...v1.1.1) (2019-10-14)


### Bug Fixes

* some distros need sudo to rename toolchain ([dab5de7](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/dab5de79af8367938ecc9281c1bf5417e4e20e07))

# [1.1.0](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/compare/v1.0.0...v1.1.0) (2019-10-09)


### Bug Fixes

* added creates param for idempotency ([687cce2](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/687cce24febcc76cd00c1d10bb1337889ebb0d03))
* added creates param for idempotency test ([5bcf731](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/5bcf7318e210ff4c668e0461635cfced5a009805))
* moved creates parameter to correct level ([6feb2ed](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/6feb2ed5fbc6be07bd75b112e2f055f8bf75a087))
* rename toolchain directory to correct name ([61f4cbd](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/61f4cbd313550dd41f4cd3b1c915bfeb4d580e7b))
* show the directory name from toolchain role ([0aff602](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/0aff6028bd3133a7d478e6cbd1174c85f1128f4c))
* skip move step if toolchain isn't downloaded ([99b159b](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/99b159b9116fd91f52dd1a311a79ac03245795ae))


### Features

* added Darwin support ([4f26a9d](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/4f26a9d7c0d312cb15a43ab566de92370acb578e))

# 1.0.0 (2019-09-03)


### Bug Fixes

* added missing toolchain role ([7a7bad6](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/7a7bad6))


### Features

* new mongo toolchain role ([497ac8f](https://github.com/mongodb-ansible-roles/ansible-role-mongo-toolchain/commit/497ac8f))
