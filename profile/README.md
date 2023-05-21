# Welcome to Vita-Rust! 🎮🛠️

Welcome to the GitHub organization Vita-Rust, dedicated to supporting [Rust programming language](https://www.rust-lang.org/) on the PlayStation Vita platform. Our goal is to provide a seamless Rust development experience for PlayStation Vita enthusiasts and developers.

## Getting Started 🚀

To get started with Rust development on the PlayStation Vita, please note the following points:

1. PlayStation Vita is now a [**Tier 3 target**](https://doc.rust-lang.org/nightly/rustc/platform-support/armv7-sony-vita-newlibeabihf.html) in Rust with standard library (`std`) support. This is possible by using [newlib implementation from Vita SDK](https://github.com/vitasdk/newlib).

2. Currently, compilation and linking are only supported with the **Vita SDK toolchain**. It is essential to set up the Vita SDK toolchain on your development environment to build Rust applications for the PlayStation Vita. To learn more about the Vita SDK toolchain and installation instructions, visit [vitasdk.org](https://vitasdk.org/).

3. While the std library is supported, there may still be some unsupported or non-functioning features. Please refer to our [wiki](https://github.com/vita-rust/.github/wiki) for an overview of the current limitations and known issues. The wiki is a work in progress, and we encourage you to contribute by adding any information you discover.

4. Please note that not all Rust crates will work out-of-the-box on the PlayStation Vita. Crates that rely on platform-dependent code or have `libc` dependencies outside the std library may not be compatible. It is essential to consider the platform limitations when selecting crates for your PlayStation Vita projects.

## Contribution 🙌

We welcome and appreciate contributions and feedback from the Vita-Rust community. Whether you want to report an issue, suggest improvements, or contribute code, we encourage you to get involved and help us enhance the Rust ecosystem on the PlayStation Vita.

## Disclaimer ⚠️

Vita-Rust is an independent organization and is not affiliated with Sony or its proprietary SDK. We do not utilize Sony's proprietary SDK in our development efforts. Vita-Rust aims to provide an open-source platform for Rust developers interested in PlayStation Vita programming.


Thank you for joining Vita-Rust! We hope this organization serves as a valuable resource for your Rust development journey on the PlayStation Vita platform.