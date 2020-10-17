# Gseu - Search and delete Ruby gems on your terminal.

This was a "CLI" that I'd to cover my needs to eliminate
all the gems of a group at the same time without placing
one by one (for example those of sinatra) and I decided
to make it public as it could serve someone else.

The name means "**G**em **Se**arch & **U**ninstall".

---

## Installation
Since it's just a BASH script, you just need
to place it inside your bin folder to use it.

## Usage
This is a usage example, for more information, use
the help command or run the script without any arguments.

### Linux / MacOS
```sh
# If you have sinatra installed as root
gseu -r -u sinatra

# If you have sinatra installed in your home directory (user installation)
gseu -u sinatra

# Example output
=== gseu [2020-10-17 / 11:59:27] [LOG]: Uninstalling sinatra ...
=== gseu [2020-10-17 / 11:59:28] Successfully uninstalled sinatra-2.1.0
=== gseu [2020-10-17 / 11:59:28] [LOG]: Uninstalling sinatra-activerecord ...
=== gseu [2020-10-17 / 11:59:29] Successfully uninstalled sinatra-activerecord-2.0.19
=== gseu [2020-10-17 / 11:59:29] [LOG]: Uninstalling sinatra-cross_origin ...
=== gseu [2020-10-17 / 11:59:31] Successfully uninstalled sinatra-cross_origin-0.4.0
```

> **Note**: If you use Termux (Android), you shouldn't use the `-r` flag as you cannot use sudo.

---

# License
Gseu is distributed under [MIT](./LICENSE) License.
