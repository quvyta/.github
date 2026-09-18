## Quvyta

A family of cross-platform terminal applications, written in Rust and built on one framework, so they look and behave alike: the same themes, icons, languages, keys and mouse behaviour. Shape comes from colour, never from bracket or box-drawing characters.

Everything here is open source under the MIT licence and in beta.

### Install

```sh
curl -fsSL https://raw.githubusercontent.com/quvyta/quvyta/main/install.sh | sh
```

The script (Linux) lets you pick what to install, installs Rust if it is missing, and adds `~/.cargo/bin` to your `PATH` with your consent. On any system, every application can also be installed on its own with `cargo install`.

### The family

| | Command | What it does |
|---|---|---|
| [code](https://github.com/quvyta/code) | `qcode` | Runs coding agent harnesses inside Podman or Docker containers and moves between them like tabs. |
| [focus](https://github.com/quvyta/focus) | `qfocus` | Tracks what you focus on, with timers, records and charts. |
| [packages](https://github.com/quvyta/packages) | `qpac` | One simple package manager for pacman, the AUR, Flatpak and Snap. Arch Linux for now; other distributions are planned. |
| [tools](https://github.com/quvyta/tools) | `qtools` | Applies the settings Arch Linux users usually set up by hand, and undoes them. Arch Linux for now. |
| [quvyta](https://github.com/quvyta/quvyta) | `quvyta` | The family's launcher: installs, opens and updates the others. |
| [framework](https://github.com/quvyta/framework) | `qframe` | The Rust framework they are all built on, with a showcase of every component. |

### Build with it

```sh
cargo add quvyta-framework
cargo install quvyta-framework-showcase && qframe
```
