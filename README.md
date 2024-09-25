# Nacosvel Contracts

[![GitHub Tag](https://img.shields.io/github/v/tag/nacosvel/contracts)](https://github.com/nacosvel/contracts/tags)
[![Total Downloads](https://img.shields.io/packagist/dt/nacosvel/contracts?style=flat-square)](https://packagist.org/packages/nacosvel/contracts)
[![Packagist Version](https://img.shields.io/packagist/v/nacosvel/contracts)](https://packagist.org/packages/nacosvel/contracts)
[![Packagist PHP Version Support](https://img.shields.io/packagist/php-v/nacosvel/contracts)](https://github.com/nacosvel/contracts)
[![Packagist License](https://img.shields.io/github/license/nacosvel/contracts)](https://github.com/nacosvel/contracts)

## Installation

You can install the package via [Composer](https://getcomposer.org/):

```bash
composer require nacosvel/contracts
```

## Design Principles

- contracts are split by domain, each into their own sub-namespaces;
- contracts are small and consistent sets of PHP interfaces, traits, normative doc-blocks and reference test suites when applicable;
- all contracts must have a proven implementation to enter this repository;

Packages that implement specific contracts should list them in the "provide" section of their "composer.json" file, using the _Nacosvel/*-implementation_ convention (e.g. `"provide": { "Nacosvel/cache-implementation": "1.0" }`).

## License

Nacosvel Contracts is made available under the MIT License (MIT). Please see [License File](LICENSE) for more information.
