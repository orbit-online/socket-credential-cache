# bitwarden-tools

Work in progress

## Installation

Install using [μpkg](https://github.com/orbit-online/upkg) and then symlink the
systemd unit from your user systemd dir:

```
upkg install orbit-online/socket-credential-cache@v1.0.0
ln -s ../../../.local/lib/upkg/socket-credential-cache/socket-credential-cache@.service $HOME/.config/systemd/user/socket-credential-cache@.service
```