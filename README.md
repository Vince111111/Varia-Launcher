<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="/program_info/org.varialauncher.VariaLauncher.logo-darkmode.svg">
    <source media="(prefers-color-scheme: light)" srcset="/program_info/org.varialauncher.VariaLauncher.logo.svg">
    <img alt="Varia Launcher" src="/program_info/org.varialauncher.VariaLauncher.logo.svg" width="40%">
  </picture>
</p>

<p align="center">
  Varia Launcher is a high-performance, feature-rich Minecraft launcher designed for power users and low-end hardware.<br />
  <br />This is a <b>fork</b> of the Prism Launcher and is <b>not</b> endorsed by or affiliated with the Prism Launcher project.
</p>

## About Varia

Varia Launcher extends the powerful foundation of Prism to provide more freedom and better performance. Whether you are playing on a high-end rig or an Intel HD 4600, Varia is built to be fast, customizable, and inclusive of all account types.

### Key Features
- **Account Freedom:** Native support for **Ely.by**, **Offline/Cracked** accounts, and Microsoft Auth.
- **Enhanced UI:** Modernized interface with deeper customization options.
- **Legacy Support:** Built-in compatibility for older modloaders like **Rift** and **Legacy Fabric**.
- **Performance First:** Optimized background processes and "debloated" code for smoother gameplay on low-end PCs.

## Installation

- Since this is a community fork, downloads are currently available through the [GitHub Releases](https://github.com/YOUR_USERNAME/VariaLauncher/releases) tab.
- Build status and automated testing can be found in the [Actions](https://github.com/YOUR_USERNAME/VariaLauncher/actions) tab.

### Development Builds
Development builds are experimental. They include the latest changes but may contain bugs. Use them at your own risk.

## Building

To build Varia Launcher yourself, you will need:
- **Qt 6.10+** (with Qt 5 Compatibility Module)
- **CMake** & **Ninja**
- **A C++17 Compiler** (MSVC 2022 recommended for Windows)

```bash
git clone [https://github.com/YOUR_USERNAME/VariaLauncher.git](https://github.com/YOUR_USERNAME/VariaLauncher.git)
cd VariaLauncher
git submodule update --init --recursive
cmake -S . -B build -G "Ninja"
cmake --build build
Forking & Redistributing Policy
This project is a fork. In accordance with the original Prism Launcher policy and the GPL license:

It is clearly stated that this is Varia Launcher, not Prism Launcher.

All official Prism Launcher API keys have been removed or set to empty strings ("") to ensure no unauthorized use of their services.

This fork is, and will remain, open source under the GPL-3.0 license.

Credits
Varia Launcher is made possible thanks to the hard work of the Prism Launcher team and the original MultiMC developers.

License 
All launcher code is available under the GPL-3.0-only license.
Assets and branding are subject to their respective licenses (CC BY-SA 4.0).
