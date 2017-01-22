# Lab | Swift Package Manager | Executable

[![License](https://img.shields.io/github/license/odaceo/lab-swift-package-manager-executable.svg)](LICENSE)
[![Build Status](https://travis-ci.org/odaceo/lab-swift-package-manager-executable.svg)](https://travis-ci.org/odaceo/lab-swift-package-manager-executable)

## Description

A Swift Executable using a Swift Library.

## Prerequisites

[Vagrant](https://www.vagrantup.com/downloads.html) must be installed on your 
computer to mount the workbench for this project.

Open a Terminal and run the following commands:

```shell
vagrant up
vagrant ssh
cd /vagrant
```

## Creating an empty application

To create an empty application use the following command:

``` shell
swift package init --type executable
```

## Building the application

The build command produces the binary file:

``` shell
swift build --configuration release
```

## Testing the application

To launch the application use the following command:

``` shell
.build/release/UuidGenerator
```

## Reporting Issues

Issues can be reported at [https://github.com/odaceo/lab-swift-package-manager-executable/issues](https://github.com/odaceo/lab-swift-package-manager-executable/issues)

## Source code

The source code is available at [https://github.com/odaceo/lab-swift-package-manager-executable](https://github.com/odaceo/lab-swift-package-manager-executable)

## License

All the source code is distributed under [ASL 2.0](LICENSE).

## Copyright

© 2017 [Odaceo](http://odaceo.ch). All rights reserved.
