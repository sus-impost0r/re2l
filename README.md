# re2l
A launcher script for Red Eclipse 2.

## Use case
Compiling, running, and updating Red Eclipse without hassle, in a
fashion that is compatible with existing source trees..

## Install
- Set RE2L_DATAPATH to the directory where the data is at. For most
cases, this is the root directory of the cloned git repo,
- Set RE2L_BINPATH to the path of the binary to execute. This binary
should reside inside the source tree of Red Eclipse 2.
- That's it! You may want to symlink re2l into some directory in your
`$PATH` -- probably `/usr/local/bin`.

## Launch
- Invoking `re2l` will launch the game
- `re2l update` to update and launch.
- `re2l clean` to recompile and launch.
- Append an ` x` if you do not wish to run the game (e.g. `re2l update
 x` to only update).

## Features
- [x] `compile`
- [x] `pull`
- [x] `update`
- [x] `clean`
- [x] `gitclean`
- [x] fancy banner
- [ ] `clone`
- [ ] `deps`

