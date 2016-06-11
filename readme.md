# Kickoff Snippets

> For Sublime Text, Atom

Use these snippets if you use the [Kickoff framework](https://github.com/trykickoff/kickoff/) & [Sublime Text](http://sublimetext.com) or [Atom](https://atom.io)

* [Kickoff demos](http://trykickoff.io/demos/)

## How to install

### Sublime

With [Package Control](http://packagecontrol.io):

1. Run `Package Control: Install Package` command, find and install **Kickoff Snippets** plugin.
2. Restart ST editor (if required)

### Atom
1. Go to `Atom > Preferences...` then search for **Kickoff Snippets** in Packages tab.
2. Restart Atom.

---

## Tab triggers

* **CSS**
 * animation: <kbd>animation</kbd> <kbd>TAB</kbd>
 * background-size: <kbd>background-size</kbd> <kbd>TAB</kbd>
 * background: <kbd>background</kbd> <kbd>TAB</kbd>
 * border-radius: <kbd>border-radius</kbd> <kbd>TAB</kbd>
 * box-shadow: <kbd>box-shadow</kbd> <kbd>TAB</kbd>
 * media-query: <kbd>media-query</kbd> <kbd>TAB</kbd>
 * transform: <kbd>transform</kbd> <kbd>TAB</kbd>
 * transition: <kbd>transition</kbd> <kbd>TAB</kbd>
 * translate3d: <kbd>translate3d</kbd> <kbd>TAB</kbd>
* **HTML**
 * 2 grid columns: <kbd>grid</kbd> <kbd>TAB</kbd>
 * grid row: <kbd>grid</kbd> <kbd>TAB</kbd>
 * grid column: <kbd>grid</kbd> <kbd>TAB</kbd>
 * media object: <kbd>media</kbd> <kbd>TAB</kbd>
 * button: <kbd>btn</kbd> <kbd>TAB</kbd>
 * fluid video: <kbd>video</kbd> <kbd>TAB</kbd>
 * checkbox: <kbd>checkbox</kbd> <kbd>TAB</kbd>
 * radio: <kbd>radio</kbd> <kbd>TAB</kbd>
 * select: <kbd>select</kbd> <kbd>TAB</kbd>
 * file: <kbd>file</kbd> <kbd>TAB</kbd>
 * form actions: <kbd>actions</kbd> <kbd>TAB</kbd>
 * input: <kbd>input</kbd> <kbd>TAB</kbd>
 * table: <kbd>table</kbd> <kbd>TAB</kbd>
* **Javascript**
 * es6 module: <kbd>es6</kbd> <kbd>TAB</kbd>
 * attach.js module: <kbd>attach</kbd> <kbd>TAB</kbd>
* **SCSS**
 * before: <kbd>before</kbd> <kbd>TAB</kbd>
 * after: <kbd>after</kbd> <kbd>TAB</kbd>
 * before&after: <kbd>beforeafter</kbd> <kbd>TAB</kbd>
 * font-size mixin: <kbd>font-size</kbd> <kbd>TAB</kbd>
 * hidpi mixin: <kbd>hidpi</kbd> <kbd>TAB</kbd>
 * respond-min mixin: <kbd>rmin</kbd> <kbd>TAB</kbd>
 * respond-max mixin: <kbd>rmax</kbd> <kbd>TAB</kbd>
 * respond-minmax mixin: <kbd>rminmax</kbd> <kbd>TAB</kbd>
 * rotate mixin: <kbd>rotate</kbd> <kbd>TAB</kbd>
 * size mixin: <kbd>size</kbd> <kbd>TAB</kbd>
 * square mixin: <kbd>square</kbd> <kbd>TAB</kbd>
 * modular-scale function: <kbd>modular-scale</kbd> <kbd>TAB</kbd>
 * colors variables: <kbd>color</kbd> <kbd>TAB</kbd>
 * default-transition variables: <kbd>default-transition</kbd> <kbd>TAB</kbd>
 * font-family variables: <kbd>font-family</kbd> <kbd>TAB</kbd>


### Sublime to Atom converter
./atomizr -i "~/htdocs/trykickoff/Kickoff-snippets/SASS/*.sublime-snippet" -o snippets.cson --split
