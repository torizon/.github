# Torizon #

[Torizon](https://www.torizon.io/) is an Easy-to-Use Industrial Linux Platform. It consists of:

- [Torizon OS](https://www.torizon.io/torizon-os): the base Embedded Linux distribution that actually runs on your preferred hardware.
- [Torizon Cloud](https://app.torizon.io/): a platform to manage services like remote access, updates, and monitoring via an API or a web GUI.
- [Debian Containers for Torizon](https://www.torizon.io/torizon-os#extensive-software): smooth integration of a robust, widely used Linux distro, on top of the Torizon OS.
- [VS Code IDE Extension](https://www.torizon.io/torizon-os#highly-productive-modern): the preferred application development workflow, with a ready-to-use SDK for various languages and frameworks, leveraging the Torizon OS and Debian Containers.
- [TorizonCore Builder](https://developer.toradex.com/torizon/os-customization/): a configuration tool so Torizon OS runs on your custom carrier board.

## Key Repositories ##

 Here's a list of important repos to get started with:

- [meta-toradex-torizon](https://github.com/torizon/meta-toradex-torizon): the Yocto layer that defines the Torizon OS distro. Start here if you want to port Torizon to a hardware platform.
- [torizon-containers](https://github.com/torizon/torizon-containers): the source code of the Debian Containers for Torizon. Start here if you want to understand how our containers are built on top of the official Debian ones.
- [vscode-torizon-templates](https://github.com/torizon/vscode-torizon-templates): the templates for the VS Code extension for Torizon. Start here if you want to support a new programming language or framework on Torizon.
- [torizoncore-builder](https://github.com/torizon/torizoncore-builder): the Torizon OS configuration tool. Start here if you want to learn how it works, request or add new features.

## Contributing ##

Contributions are welcome. They are processed on a per-project basis, therefore the best place to start is the repository of the project you want to contribute to.
