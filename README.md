# socket-credential-cache

## Installation

Install using [μpkg](https://github.com/orbit-online/upkg) and then symlink the
systemd unit from your user systemd dir:

```
upkg install orbit-online/socket-credential-cache@<VERSION>
ln -s ../../../.local/lib/upkg/orbit-online/socket-credential-cache/socket-credential-cache@.service $HOME/.config/systemd/user/socket-credential-cache@.service
systemctl --user daemon-reload
```
