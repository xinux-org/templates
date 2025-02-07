<p align="center">
    <img src=".github/assets/header.png" alt="Xinux'es {Templates}">
</p>

<p align="center">
    <h3 align="center">Various project templates for faster bootstrapping with Nix.</h3>
</p>

<p align="center">
    <img align="center" src="https://img.shields.io/github/languages/top/xinux-org/templates?style=flat&logo=nixos&logoColor=5277C3&labelColor=ffffff&color=ffffff" alt="Top Used Language">
    <a href="https://t.me/xinux"><img align="center" src="https://img.shields.io/badge/Chat-grey?style=flat&logo=telegram&logoColor=5277C3&labelColor=ffffff&color=ffffff" alt="Telegram Community"></a>
</p>

## About

This is a collection of Xinux'es Nix bootstrapped templates which can be used to bootstrap your own project for certain technology. The templates
have everything set up ready for you, so you can focus on developing the application instead of playing around configuring everything to get it
working.

> Every repository has its own detailed readme.md for more information to get started once you're done bootstrapping.

## Projects

- Rust (via #rust)
- Rust Nightly (via #rust-nightly)
- Rust C static/shared library (via #rust-shared)
- Rust Telegram Bot (via #rust-telegram)
- Rust Actix (via #rust-actix)
- WIP: Rust Embedded (via #rust-embedded)

## Bootstrapping

In order to bootstrap your own project using our tempaltes, you need to `cd` somewhere and on terminal:

```shell
# Replace `example` with any supported template above in projects section
nix flake init --template github:xinux-org/templates#example
```

the command above bootstrap project in current directory, or you can indicate location where it should be boostrapped:

```shell
# instead of examples, any chosen project's via #...
nix flake new --template github:xinux-org/templates#example ./my-cool-project
```

## Thanks

- [Official Nix Temapltes](https://github.com/NixOS/templates) - For showing how to create personal template collections.
- [Personal Hatsune Miku Playlist](https://www.youtube.com/watch?v=UavAXELySiY&list=PL8ICxEebtazfwaK8jTnyyXqVqfT5vWsj0&pp=gAQB) - For cheering me up while I was writing all these.

## License

This project is licensed under the MIT License - see the [LICENSE](license) file for details.

<p align="center">
    <img src=".github/assets/footer.png" alt="Xinux'es {Templates}">
</p>
