# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [6.0.6](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/compare/@gamio-technology/loopback-connector-mongodb@6.0.5...@gamio-technology/loopback-connector-mongodb@6.0.6) (2021-04-15)

### [6.0.5](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/compare/@gamio-technology/loopback-connector-mongodb@6.0.4...@gamio-technology/loopback-connector-mongodb@6.0.5) (2021-04-15)

### [6.0.4](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/compare/@gamio-technology/loopback-connector-mongodb@6.0.3...@gamio-technology/loopback-connector-mongodb@6.0.4) (2021-04-15)

### [6.0.3](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/compare/@gamio-technology/loopback-connector-mongodb@6.0.3...@gamio-technology/loopback-connector-mongodb@6.0.3) (2021-04-15)

### [6.0.2](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/compare/@gamio-technology/loopback-connector-mongodb@6.0.3...@gamio-technology/loopback-connector-mongodb@6.0.2) (2021-04-15)

### [6.0.1](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/compare/@gamio-technology/loopback-connector-mongodb@6.0.3...@gamio-technology/loopback-connector-mongodb@6.0.1) (2021-04-15)

### [6.0.3](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/compare/@gamio-technology/loopback-connector-mongodb@6.0.2...@gamio-technology/loopback-connector-mongodb@6.0.3) (2021-04-15)

### [6.0.2](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/compare/@gamio-technology/loopback-connector-mongodb@6.0.1...@gamio-technology/loopback-connector-mongodb@6.0.2) (2021-04-15)

### [6.0.1](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/compare/@gamio-technology/loopback-connector-mongodb@6.1.1...@gamio-technology/loopback-connector-mongodb@6.0.1) (2021-04-15)

### [6.1.1](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/compare/@gamio-technology/loopback-connector-mongodb@6.1.0...@gamio-technology/loopback-connector-mongodb@6.1.1) (2021-04-15)

## 6.1.0 (2021-04-15)


### Features

* add mongodb.dataType to property definition ([8d86bdc](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/8d86bdca9e919a0056ba06e0ebd90d0204acd5a6))
* allow methods to pass strictObjectIDCoercion ([b30a28e](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/b30a28e7a13e9547ea0435bc5e388c55c761d26b))
* update dependenies ([b77dc55](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/b77dc556abe1b42514881bcba76027b892e00e74))
* upgrade to eslint v6 ([b982ce6](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/b982ce6bea64e56ede81e9ae769e8b2509efc686))


### Bug Fixes

* allow arrays to be stored in type ObjecId ([f2cef0f](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/f2cef0f0b5a5b3c17bc485651c7b15b39069d77c))
* allow db name to be parsed from url ([4e489c2](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/4e489c2436a4a661bdd7175cd5089d17fc1b528a))
* allow to include options to mongodb connector ([d3f6ed3](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/d3f6ed375024394258ec89b123b5976fd102929e))
* allows fields filter with custom field name ([8bdadd1](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/8bdadd1f7ed67d6ae4654d91ca2a8db3b44f8634))
* call toDatabase update and upsert ([ce6145c](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/ce6145c7f9d8b8daefdda98174ebb3c47e73fe8a))
* coerce deep nested decimal properties ([fb41e40](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/fb41e40777c7eb11a9de15878bf3ad09eac943bc))
* edge cases to coerce nested decimal props ([25122e0](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/25122e02a59dea75148d1670ed49ce9294a8b548))
* fix ([78e7970](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/78e797091cb0c7e2e4763a50ef97a41a6e27f87d))
* fix sections order ([822ffc7](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/822ffc797439a3417ceb6d0b73ba568f7b276a9a))
* map new names to old for connector hooks ([1782868](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/1782868c2fe7d6f6f9261142684a0e9b47c0267d))
* ObjectID data type preservation ([32bb8fd](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/32bb8fd37d4b331bba1dcd9eec281e6eca4b2998))
* preserve id on update ([c5200e2](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/c5200e26498ffcd2b560e3a3cf8ba2795bbf603f))
* sanitize extra dollar signs for operators ([c839406](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/c8394066e4066e400df62dbe8688865956408606))
* sanitize query by default ([ee24cd0](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/ee24cd08b8ccc32711264831c71b1da628df357b))
* throws when the custom id field name is set ([3c40c14](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/3c40c14c9b355267df89847c3b3e8e59cb735671))
* update the error message and name ([#561](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/issues/561)) ([8aa3127](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/8aa3127f847aea4fc401626bc98561bb129ffd94))


### Reverts

* Revert "Add a workaround for auth with multiple mongos servers" ([35c537d](https://github.com/Gamio-technology/loopback-connector-transactions-mongodb/commit/35c537d4b36096a0076d065757c4aa09edc88388))
