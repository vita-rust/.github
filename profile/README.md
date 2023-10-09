# Welcome to Vita-Rust! 🎮🛠️

Welcome to the GitHub organization Vita-Rust, dedicated to supporting [Rust programming language] on the PlayStation Vita platform. Our goal is to provide a seamless Rust development experience for PlayStation Vita enthusiasts and developers.

Please refer to our [Rust on Sony PlayStation Vita Book] to find out how to start developing applications in Rust for Vita. The wiki is a work in progress, and we would like to encourage you to contribute by adding any information necessary.

## Getting Started 🚀

To get started with Rust development on the PlayStation Vita, please note the following:

1. PlayStation Vita is now a **[Tier 3 target]** in Rust with standard library (`std`) support. This is possible by using [newlib] implementation from [Vita SDK].

2. Since this is a Tier 3 target, in order to use std you will have to build `std` yourself. This is possible with a [build-std] cargo build flag without the use of any external tools. This is an unstable feature of `cargo`, so in order to have `std` you must use the nightly compiler.

3. Currently, compilation and linking are only supported with the **[Vita SDK] toolchain**. Setting up the [Vita SDK] toolchain on your development environment is essential to build Rust applications for the PlayStation Vita.

4. While the std library is supported, there may still be some unsupported or non-functioning features.

5. Please note that not all Rust crates will work out-of-the-box on the PlayStation Vita. Crates that rely on platform-dependent code or have `libc` dependencies outside the std library may not be compatible. It is essential to consider the platform limitations when selecting crates for your PlayStation Vita projects.

## Contribution 🙌

We welcome and appreciate contributions and feedback from the Vita-Rust community. Whether you want to report an issue, suggest improvements, or contribute code, we encourage you to get involved and help us enhance the Rust ecosystem on the PlayStation Vita.

## Communication 🤙

If you have any questions, or suggestions or want to start some discussions, you can do so on [HENKaku] Discord server in [#rust] channel. When you join the server please read and follow the rules.

## Disclaimer ⚠️

Vita-Rust is an independent organization and is not affiliated with Sony or its proprietary SDK. We do not utilize Sony's proprietary SDK in our development efforts. Vita-Rust aims to provide an open-source platform for Rust developers interested in PlayStation Vita programming.


Thank you for joining Vita-Rust! We hope this organization serves as a valuable resource for your Rust development journey on the PlayStation Vita platform.

[Rust programming language]: https://www.rust-lang.org/
[Rust on Sony PlayStation Vita Book]: https://vita-rust.github.io/book/
[Tier 3 target]: https://doc.rust-lang.org/nightly/rustc/platform-support/armv7-sony-vita-newlibeabihf.html
[newlib]: https://github.com/vitasdk/newlib
[Vita SDK]: https://vitasdk.org/
[build-std]: https://doc.rust-lang.org/cargo/reference/unstable.html#build-std
[HENKaku]: https://discord.gg/m7MwpKA
[#rust]: https://discord.com/channels/439481392548675594/1148989867699744909
