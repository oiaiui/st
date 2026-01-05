# st
[st](https://st.suckless.org/), or "simple terminal", is a fine piece of software by [suckless.org](https://suckless.org/), notable for making software that sucks less. Since it is pretty minimal out of the box, additional features are added by patching the source code. I'm sure you have read all of this before.

## "snazzy terminal"
"st" can also expand to "[snazzy terminal](https://github.com/siduck/st)", which is an apt (not the package manager) description of [siduck](https://github.com/siduck/)'s fork of suckless.org's st, modified to have some extra functionality patched in and also to look kind of neat. This repo is a fork of just that, with some extra patches and configurations set to my satisfaction.

## Additions
- The [Alpha Focus Highlight patch](https://st.suckless.org/patches/alpha_focus_highlight/);
- Variable `borderpx` is replaced with the pair `borderpx_x` and `borderpx_y` for finer control of padding. To be frank, I haven't tested this patch much and thus it is highly explosive material to be handled with care

## Dependencies
...are almost the same as siduck's st, which was already linked, so be sure to check it out. However, I did add an extra line to the Makefile script in order to include my [preferred colour header](https://github.com/oiaiui/eyesoreless), which I keep in `~/.local/include/` and which you will need unless you ditch and/or tamper with the supplied `config.h` header.

# Credits
- siduck
- suckless.org
- ...and also, of course, everything they give credit to.
