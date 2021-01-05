# orchid

A lightweight text editor written in Lua
𝕎𝕖𝕝𝕔𝕠𝕞𝕖 𝕥𝕠 𝕥𝕙𝕖 𝕘𝕒𝕣𝕕𝕖𝕟.

* **[Get orchid](https://github.com/Dream-Imperium/orchid/releases/latest)** - Download
  for Windows and Linux
* **[Get started](doc/usage.md)** - A quick overview on orchid and how to get started
* **Get plugins** - Coming soon; add additional functionality
* **Get color themes** - Coming soon; add additional color themes

## Overview
orchid is a lightweight text editor written mostly in Lua. It aims to provide
something practical, pretty, and small. Like an orchid. All these features
are to be implemented as simply as possible; easy to modify and extend,
or to use without doing either.

## Customization
Additional functionality can be added through plugins which will be
available from two repositories, one for plugins and the other for
color themes. The editor can be customized by making changes to the
[user module](data/user/init.lua).

## Building
You can build the project yourself on Linux using the `build.sh`
script or on Windows using the `build.bat` script *([MinGW](https://nuwen.net/mingw.html) is required)*.
Note that the project does not need to be rebuilt if you are
only making changes to the Lua portion of the code.

## License
This project is in the public domain. See [LICENSE](LICENSE) for details.