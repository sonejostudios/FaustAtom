# FaustAtom
Config files for Faust in Atom

First, install language-faust in ~$ .atom/packages/
(in is in the source code of faust, https://sourceforge.net/p/faudiostream/code/ci/master/tree/syntax-highlighting/atom/)
This will enable syntax highlighting for faust and install a couple of basic snippets.

Extended Snippets:
1. Copy the language-faust-extended.cson in ~$ .atom/packages/language-faust/snippets

This will provide a much bigger list of handy snippets (osc, square, amp_follower, button radio, etc etc). Feel free to add yours and commit!
For an easy classification the names of the snippets are written like "object.variation", ie "slider.h" will give "hslider". So writing "slider" will open the drop down menu with all sliders possibilities.


Process Palette:
1. Install the module Process Palette in Atom
2. Copy process-palette.json in ~$ .atom
This will install the faust process palette as global palette. To install it in a project only please read the doc of process palette.

This will provide a couple a very handy commands for faust
- faust2svg (shortcut: ctrl-shift-s. This will save the .dsp file and export it as block diagram)
- faust2jaqt
- faust2lv2
- open block diagram with gThumb (as soon as the block diagram is re-drawn (by faust2svg) gThumb will reload it automatically)
- navigate block diagram with Firefox
- start project with FaustLive (be sure jackd is running)
