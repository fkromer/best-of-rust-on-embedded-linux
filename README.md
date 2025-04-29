<!-- markdownlint-disable -->
<h1 align="center">
    best-of-embedded-rust
    <br>
</h1>

<p align="center">
    <strong>🏆&nbsp; A ranked list of awesome projects. Updated weekly.</strong>
</p>

<p align="center">
    <a href="https://best-of.org" title="Best-of Badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-40-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/fkromer/best-of-embedded-rust/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/fkromer/best-of-embedded-rust?color=green&label=updated"></a>
</p>

This curated list contains 40 awesome open-source projects with a total of 55K stars grouped into 14 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/fkromer/best-of-embedded-rust/issues/new/choose), submit a [pull request](https://github.com/fkromer/best-of-embedded-rust/pulls), or directly edit the [projects.yaml](https://github.com/fkromer/best-of-embedded-rust/edit/main/projects.yaml). Contributions are very welcome!

> 🧙‍♂️  Discover other [best-of lists](https://best-of.org) or [create your own](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

## Contents

- [User Interfaces](#user-interfaces) _1 projects_
- [Home Automation Protocols](#home-automation-protocols) _3 projects_
- [Smart Grid Protocols](#smart-grid-protocols) _7 projects_
- [Robotics](#robotics) _3 projects_
- [Graphics](#graphics) _1 projects_
- [Inter Process Communication](#inter-process-communication) _6 projects_
- [Hardware Abstraction Layer (HAL)](#hardware-abstraction-layer-hal) _2 projects_
- [Character Device Drivers](#character-device-drivers) _3 projects_
- [Continous Integration](#continous-integration) _1 projects_
- [Yocto Layers](#yocto-layers) _4 projects_
- [Yocto](#yocto) _1 projects_
- [Cross Compilation](#cross-compilation) _1 projects_
- [Testing](#testing) _3 projects_
- [Tools](#tools) _4 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects

<br>

## User Interfaces

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/slint-ui/slint">slint</a></b> (🥇34 ·  ⭐ 19K) - Slint is an open-source declarative GUI toolkit to build native user.. <code>❗Unlicensed</code>
</details>
<br>

## Home Automation Protocols

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/project-chip/rs-matter">rs-matter</a></b> (🥇17 ·  ⭐ 380) - Rust implementation of the Matter protocol. Status: Experimental. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/project-chip/rs-matter) (👨‍💻 27 · 🔀 46 · 📦 6 · 📋 57 - 45% open · ⏱️ 22.04.2025):

	```
	git clone https://github.com/project-chip/rs-matter
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/knxkit/knxkit">knxkit</a></b> (🥉4 ·  ⭐ 3 · 🐣) -  <code><a href="http://bit.ly/2M0xmjV">EPL-2.0</a></code>
- <b><a href="https://github.com/memoos/knx-rust">knx-rust</a></b> (🥉3 ·  ⭐ 3 · 💤) - Library implementing the KNXNet/Ip protocol. <code>❗Unlicensed</code>
</details>
<br>

## Smart Grid Protocols

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/codelabsab/rust-ocpp">rust-ocpp</a></b> (🥇17 ·  ⭐ 87) - Libraries for ocpp 1.6 and 2.0.1. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/OpenLEADR/openleadr-rs">openleadr-rs</a></b> (🥈12 ·  ⭐ 32 · 🐣) - OpenADR 3.0 VTN and VEN implementation in Rust. <code>❗Unlicensed</code>
- <b><a href="https://github.com/PeterGrace/sunspec_rs">sunspec_rs</a></b> (🥈7) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/bikeshedder/sunspec">sunspec</a></b> (🥉6 ·  ⭐ 7) - Rust crate for accessing SunSpec compliant devices in a safe and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/lukaskirner/tokio-sunspec">tokio-sunspec</a></b> (🥉6 ·  ⭐ 5 · 💀) - A tokio-based SunSpec library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/DerAndereAndi/eebus-rust">eebus-rust</a></b> (🥉4 ·  ⭐ 3 · 💀) - Very basic EEBUS protocol implementation in Rust. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Lexicality/libmburs">libmburs</a></b> (🥉3 ·  ⭐ 1) - For when you want to talk to an m-bus device but dont want to use C. <code><a href="https://tldrlegal.com/search?q=EUPL-1.2">❗️EUPL-1.2</a></code>
</details>
<br>

## Robotics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/adnanademovic/rosrust">rosrust</a></b> (🥇20 ·  ⭐ 760) - Pure Rust implementation of a ROS client library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/adnanademovic/rosrust) (👨‍💻 19 · 🔀 75 · 📦 230 · 📋 110 - 36% open · ⏱️ 03.02.2025):

	```
	git clone https://github.com/adnanademovic/rosrust
	```
</details>
<details><summary><b><a href="https://github.com/ros2-rust/ros2_rust">ros2_rust</a></b> (🥉18 ·  ⭐ 1.1K) - Rust bindings for ROS 2. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ros2-rust/ros2_rust) (👨‍💻 47 · 🔀 150 · 📋 170 - 29% open · ⏱️ 13.03.2025):

	```
	git clone https://github.com/ros2-rust/ros2_rust
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/sequenceplanner/r2r">r2r</a></b> (🥉15 ·  ⭐ 360) - Minimal ROS 2 Rust bindings. <code>❗Unlicensed</code>
</details>
<br>

## Graphics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/rust-skia/rust-skia">rust-skia</a></b> (🥇22 ·  ⭐ 1.6K) - Rust Bindings for the Skia Graphics Library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rust-skia/rust-skia) (👨‍💻 56 · 🔀 140 · 📥 370 · 📦 9 · 📋 340 - 10% open · ⏱️ 11.04.2025):

	```
	git clone https://github.com/rust-skia/rust-skia
	```
</details>
<br>

## Inter Process Communication

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary>Show 6 hidden projects...</summary>

- <b><a href="https://github.com/dbus2/zbus">zbus</a></b> (🥇25 ·  ⭐ 480) - Rust D-Bus crate. <code>❗Unlicensed</code>
- <b><a href="https://github.com/diwic/dbus-rs">dbus-rs</a></b> (🥈15 ·  ⭐ 620) - D-Bus binding for the Rust language. <code>❗Unlicensed</code>
- <b><a href="https://github.com/KillingSpark/rustbus">rustbus</a></b> (🥈15 ·  ⭐ 59 · 💤) - Dbus transport in pure rust. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/srwalter/dbus-bytestream">dbus-bytestream</a></b> (🥉6 ·  ⭐ 6 · 💀) - Native D-Bus implementation for Rust. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code>
- <b><a href="https://github.com/Arnavion/dbus-pure">dbus-pure</a></b> (🥉5 ·  ⭐ 13) - Pure Rust implementation of a D-Bus client. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/cmaves/async-rustbus">async-rustbus</a></b> (🥉2 ·  ⭐ 2 · 💀) - An asynchronous implementation of the DBus protocol.. <code>❗Unlicensed</code>
</details>
<br>

## Hardware Abstraction Layer (HAL)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/rust-embedded/linux-embedded-hal">linux-embedded-hal</a></b> (🥇22 ·  ⭐ 260) - Implementation of the `embedded-hal` traits for Linux.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rust-embedded/linux-embedded-hal) (👨‍💻 29 · 🔀 45 · 📦 1.4K · 📋 41 - 48% open · ⏱️ 07.02.2025):

	```
	git clone https://github.com/rust-embedded/linux-embedded-hal
	```
</details>
<details><summary><b><a href="https://github.com/dbrgn/embedded-hal-mock">embedded-hal-mock</a></b> (🥉17 ·  ⭐ 130) - Mocks for testing embedded-hal based drivers without.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dbrgn/embedded-hal-mock) (👨‍💻 24 · 🔀 24 · 📦 920 · 📋 31 - 29% open · ⏱️ 26.04.2025):

	```
	git clone https://github.com/dbrgn/embedded-hal-mock
	```
</details>
<br>

## Character Device Drivers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/rust-embedded/rust-i2cdev">rust-i2cdev</a></b> (🥇21 ·  ⭐ 220) - Rust library for interfacing with i2c devices under Linux. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rust-embedded/rust-i2cdev) (👨‍💻 29 · 🔀 54 · 📦 1K · 📋 31 - 16% open · ⏱️ 04.03.2025):

	```
	git clone https://github.com/rust-embedded/rust-i2cdev
	```
</details>
<details><summary><b><a href="https://github.com/rust-embedded/rust-spidev">rust-spidev</a></b> (🥉18 ·  ⭐ 120) - Rust library providing access to spidev devices under Linux. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rust-embedded/rust-spidev) (👨‍💻 16 · 🔀 31 · 📦 810 · 📋 11 - 9% open · ⏱️ 04.03.2025):

	```
	git clone https://github.com/rust-embedded/rust-spidev
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/rust-embedded/gpio-cdev">gpio-cdev</a></b> (🥉18 ·  ⭐ 220 · 💀) - Rust interface to the Linux GPIO Character Device API.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Continous Integration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/houseabsolute/actions-rust-cross">actions-rust-cross</a></b> (🥇19 ·  ⭐ 160) - GitHub Action to compile Rust with cross. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/houseabsolute/actions-rust-cross) (👨‍💻 7 · 🔀 20 · 📦 1K · 📋 34 - 11% open · ⏱️ 12.04.2025):

	```
	git clone https://github.com/houseabsolute/actions-rust-cross
	```
</details>
<br>

## Yocto Layers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/meta-rust/meta-rust">meta-rust</a></b> (🥇15 ·  ⭐ 220) - OpenEmbedded/Yocto layer for Rust and Cargo. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/meta-rust/meta-rust) (👨‍💻 64 · 🔀 130 · 📋 160 - 38% open · ⏱️ 13.03.2025):

	```
	git clone https://github.com/meta-rust/meta-rust
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/rust-embedded/meta-rust-bin">meta-rust-bin</a></b> (🥈12 ·  ⭐ 120) - Yocto layer for installing Rust toolchain from pre-built.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/slint-ui/meta-slint">meta-slint</a></b> (🥉10 ·  ⭐ 15) - A Yocto layer with recipes for building Slint. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/silitics/meta-rugix">meta-rugix</a></b> (🥉5) - Yocto layers for Rugix. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Yocto

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/siemens/kas">kas</a></b> (🥇21 ·  ⭐ 450) - Setup tool for bitbake based projects. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/siemens/kas) (👨‍💻 78 · 🔀 170 · 📦 86 · 📋 110 - 14% open · ⏱️ 24.04.2025):

	```
	git clone https://github.com/siemens/kas
	```
</details>
<br>

## Cross Compilation

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/cross-rs/cross">cross</a></b> (🥇30 ·  ⭐ 7.3K) - Zero setup cross compilation and cross testing of Rust crates. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/cross-rs/cross) (👨‍💻 130 · 🔀 400 · 📥 2.2M · 📦 350 · 📋 800 - 23% open · ⏱️ 28.04.2025):

	```
	git clone https://github.com/cross-rs/cross
	```
</details>
<br>

## Testing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/mitsuhiko/insta">insta</a></b> (🥇30 ·  ⭐ 2.5K) - A snapshot testing library for rust. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mitsuhiko/insta) (👨‍💻 60 · 🔀 120 · 📥 130K · 📦 12K · 📋 300 - 15% open · ⏱️ 08.04.2025):

	```
	git clone https://github.com/mitsuhiko/insta
	```
</details>
<details><summary><b><a href="https://github.com/proptest-rs/proptest">proptest</a></b> (🥉26 ·  ⭐ 1.9K) - Hypothesis-like property testing for Rust. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/proptest-rs/proptest) (👨‍💻 77 · 🔀 180 · 📦 42K · 📋 270 - 41% open · ⏱️ 21.03.2025):

	```
	git clone https://github.com/proptest-rs/proptest
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/Diggsey/mockalloc">mockalloc</a></b> (🥉2 ·  ⭐ 13 · 💀) - Rust library for testing code relying on the global allocator. <code>❗Unlicensed</code>
</details>
<br>

## Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/rust-lang/miri">miri</a></b> (🥈25 ·  ⭐ 5.1K) - An interpreter for Rusts mid-level intermediate representation. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rust-lang/miri) (👨‍💻 310 · 🔀 370 · 📋 1.1K - 13% open · ⏱️ 29.04.2025):

	```
	git clone https://github.com/rust-lang/miri
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/rust-lang/rust-clippy">clippy</a></b> (🥇28 ·  ⭐ 12K) - A bunch of lints to catch common mistakes and improve your Rust.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/silitics/rugix">rugix</a></b> (🥉17 ·  ⭐ 73) - A suite of open-source tools to build and deploy reliable embedded Linux.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/awslabs/duvet">duvet</a></b> (🥉10 ·  ⭐ 72) - A requirements traceability tool. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>

---

## Related Resources

- [**Best-of lists**](https://best-of.org): Discover other best-of lists with awesome open-source projects on all kinds of topics.

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/fkromer/best-of-embedded-rust/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/fkromer/best-of-embedded-rust/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/fkromer/best-of-embedded-rust/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/fkromer/best-of-embedded-rust/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/fkromer/best-of-embedded-rust/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
