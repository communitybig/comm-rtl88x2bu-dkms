# `rtl88x2bu-dkms`

## Package Description

The `rtl88x2bu-dkms` package provides a kernel module for Realtek RTL88x2BU-based wireless network adapters. This package is built using DKMS (Dynamic Kernel Module Support), allowing it to compile and install the module automatically whenever a kernel update occurs.

This driver ensures compatibility and performance for devices using the Realtek RTL88x2BU chipset across various Linux distributions and kernel versions.

## Features

- **Dynamic Kernel Support (DKMS):** Automatically compiles and installs the driver during kernel updates.
- **Wide Compatibility:** Supports various architectures, including `x86_64`, `i686`, `arm`, and `aarch64`.
- **Conflict Handling:** Blacklists conflicting drivers to prevent module conflicts.
- **Documentation and License:** Includes the necessary license and documentation files.

## Source Repository

This package retrieves the driver source code from the following GitHub repository:

[RinCat/RTL88x2BU-Linux-Driver](https://github.com/RinCat/RTL88x2BU-Linux-Driver)

The repository contains the official Realtek RTL88x2BU driver for Linux, with ongoing community updates to ensure compatibility and stability.