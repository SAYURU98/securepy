# DreamTech SecurePy

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/dreamtech.securepy.svg?label=Visual%20Studio%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=dreamtech.securepy)
[![GitHub Release](https://img.shields.io/github/release/dreamtech/securepy.svg?logo=github)](https://github.com/dreamtech/securepy/releases)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/dreamtech/securepy/blob/master/LICENSE)

DreamTech SecurePy is a Visual Studio Code extension for securely running Python code. It provides a sandbox environment for running untrusted code, and ensures that the code is executed safely without accessing or modifying sensitive data on your system.

## Features

- Run Python code in a secure sandbox environment
- Restrict access to sensitive data and system resources
- Prevent malicious code from modifying your system
- Customizable security settings for different use cases

![SecurePy in Action](images/securepy.png)

## Requirements

SecurePy requires Python 3.6 or higher to be installed on your system.

## Extension Settings

This extension contributes the following settings:

* `securepy.timeout`: Set the timeout period (in seconds) for executing Python code in the sandbox. Default is 5 seconds.
* `securepy.maxMemoryMB`: Set the maximum memory limit (in megabytes) for executing Python code in the sandbox. Default is 256 MB.
* `securepy.tmpdir`: Set the temporary directory to use for storing files created during execution. Default is the system's temporary directory.

## Known Issues

There are currently no known issues with this extension.

## Release Notes

### 1.0.0

Initial release of DreamTech SecurePy.

### 1.1.0

Added support for customizing security settings.

## Contributions

Contributions are always welcome! If you have any suggestions, issues, or feature requests, please create an issue on the [GitHub repository](https://github.com/dreamtech/securepy) or submit a pull request.

## License

This extension is licensed under the [MIT License](LICENSE).
