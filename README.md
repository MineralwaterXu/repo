# Arch Linux MineralwaterXu Repository

Here are package sources, which I maintain, co-maintain or host.

## Package Repository

To use my package repository, add [my GPG key](https://keyserver.ubuntu.com/pks/lookup?op=get&search=0x0a979d95548d549c) to your pacman keyring:

```sh
pacman-key --recv-keys 0A979D95548D549C
pacman-key --lsign-key 0A979D95548D549C
```

Then add the repository configuration to your `pacman.conf` after the *[community]* repository.

```ini
[archlinuxmw]
Server = https://m1neralwater.com/repo
```