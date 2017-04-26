# English (UK) + Catalan XKB distribution
Custom X KeyBoard layout for English (UK) + Catalan, which gives easy access to:
 - `ccedilla` (ç) via <kbd>AltGr</kbd>+<kbd>c</kbd>.
 - `ntilde` (ñ) via <kbd>AltGr</kbd>+<kbd>n</kbd>.

Of course, the <kbd>Shift</kbd> modifier will allow typping capital Ç and Ñ.

## Installation

Simple, you just run the script from the root of the source folder:
```bash
./INSTALL
```

Apparently, in Debian/Ubuntu systems, you also need to run the following after the installation:
```bash
sudo dpkg-reconfigure xkb-data
```
