# Herdr configuration

Personal Herdr preferences backed up from `~/.config/herdr/config.toml`.

## Restore

```sh
git clone git@github.com:dincorvaia-nc/herdr.git /tmp/herdr-config
mkdir -p ~/.config/herdr
cp /tmp/herdr-config/config.toml ~/.config/herdr/config.toml
```

Restart Herdr after restoring the file. Runtime sockets, logs, plugin locks,
release metadata, and session/workspace state are intentionally not backed up.
Herdr recreates them locally.
