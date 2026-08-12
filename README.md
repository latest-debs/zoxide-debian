# zoxide for Debian

[zoxide](https://github.com/ajeetdsouza/zoxide) — A smarter cd command for your terminal — packaged for
Debian as part of [latest-debs](https://github.com/latest-debs).

## Install

Via the latest-debs apt repository:

```sh
sudo extrepo enable latest-debs
sudo apt update
sudo apt install zoxide
```

Or download a `.deb` from the [Releases](https://github.com/latest-debs/zoxide-debian/releases) page:

```sh
sudo dpkg -i zoxide_*.deb
```

## Supported distributions & architectures

- Debian Bookworm (12), Trixie (13), Forky (14/testing), Sid (unstable)
- amd64, arm64, armhf, i386 (bookworm/trixie) — actual per-release availability depends on what upstream publishes

## Building

Run the [Build zoxide for Debian](../../actions) workflow on GitHub with the
desired upstream version. Packaging is driven by
[debian-multiarch-builder](https://github.com/ranjithrajv/debian-multiarch-builder).

## Disclaimer

Unofficial packaging only. For issues with zoxide itself, see
[ajeetdsouza/zoxide](https://github.com/ajeetdsouza/zoxide).
