FluidTYPO3 Suite Tests
======================

[![Build Status](https://img.shields.io/travis/FluidTYPO3/fluidtypo3-testing.svg?style=flat-square)](https://jenkins.fluidtypo3.org/job/fluidtypo3-testing/) [![Coverage Status](https://img.shields.io/coveralls/FluidTYPO3/fluidtypo3-testing/master.svg?style=flat-square)](https://coveralls.io/r/FluidTYPO3/fluidtypo3-testing)

Small project to run all tests of all FluidTYPO3 extensions.

Comes without composer lock file in order to always use latest dev.

Usage
-----

```
composer install
# composer install --no-dev
./vendor/bin/runtests
```

