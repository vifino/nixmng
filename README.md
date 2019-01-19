# nixmng

Bare-bones UNIX-style server management.

## Utilities
### `mng`
Server group management.

Allows you to run commands over groups of hosts. For example `ssh` commands.

See the usage.

Requirements:
- A POSIX Shell (dash, for example)
- `ping` for `ping` commands.
- `OpenSSH` for `ssh` commands.
- `ipmitool` for `ipmi` commands.

## License
ISC.
