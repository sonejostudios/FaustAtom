# FaustAtom
Config files for Faust in the Atom Text Editor.

First, install language-faust in ~$ .atom/packages/
(it is in the source code of faust, https://sourceforge.net/p/faudiostream/code/ci/master/tree/syntax-highlighting/atom/)
This will enable syntax highlighting for faust and install a couple of basic snippets.

__Extended Snippets:__

1. Copy the language-faust-extended.cson in ~$ .atom/packages/language-faust/snippets

This will provide a much bigger list of handy snippets (osc, square, amp_follower, button radio, etc etc). Feel free to add yours and commit!
For an easy classification the names of the snippets are written like "object.variation", ie "slider.h" will give "hslider". So writing "slider" will open the drop down menu with all sliders possibilities.

![screenshot](https://raw.githubusercontent.com/sonejostudios/FaustAtom/master/snippets.png "Faust Extended Snippets")


__Process Palette:__

1. Install the module Process Palette in Atom

2. Copy process-palette.json in ~$ .atom
This will install the faust process palette as global palette. To install it in a project only please read the doc of process palette.

3. Create a "FaustAtom" directory in your home folder.
This will be the current directory for the bock diagrams and FaustLive.

The process palette will provide a couple a very handy commands for faust:

* faust2SVG (shortcut: shift-ctrl-s): this will save the .dsp file and export it as block diagram.
* faust2jaqt
* faust2lv2
* Faust gThumb (shortcut: shift-ctrl-v): open block diagram with gThumb (as soon as the block diagram is re-drawn (by faust2svg) gThumb will reload it automatically)
* Faust Lib Doc: open the Faust Libraries Documentation in Firefox
* FaustLive (shortcut: shift-ctrl-t): start project with FaustLive (be sure jackd is running)

![screenshot](https://raw.githubusercontent.com/sonejostudios/FaustAtom/master/processpalette.png "Faust Process Palette")
