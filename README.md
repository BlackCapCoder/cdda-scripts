# CDDA scripts

`./upd` download the most recent experimental build of CDDA from github

`./run` launch the game

The directories (mods, configs, templates ..) are symlinked to the correct
places by the `upd` script and persist between versions.

The `mods_` directory contains the actual mods and is not symlinked, and
the `mods` directory contains symlinks to individual mods in `mods_`.
This convention makes it easier to debug.

