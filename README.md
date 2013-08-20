# LIL SCRIPTS

These are just a couple little scripts that I use to do some things that you may
or may not need to do.

## todo

_From: [this guy](https://twitter.com/holman/status/364509812962242560)_

Shell script to add a todo to my Desktop.

### Usage:

    $ todo a thing

## sass-heading

_From: me_

Ruby script to output a heading like this:

    /*------------------------------------*\
       $SASS HEADING
    \*------------------------------------*/

For use in Sass, maybe other things.

### Usage

    $ sass-heading the heading follows

Bonus points for using in Vim like:

    :r!sass-heading the heading follows

## lipsum

Output a paragraph of lorem ipsum from [lipsum.com](http://www.lipsum.com).

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed feugiat et erat
nec facilisis. Donec condimentum ante vel arcu auctor, accumsan bibendum odio
elementum. Aliquam iaculis auctor nisi luctus mattis. Nam quis bibendum leo,
vitae varius ligula. Proin tristique ullamcorper mauris, ut pharetra quam
posuere quis.

### Usage

    $ lipsum

Again, bonus points if used inside Vim:

    :r!lipsum

## note

_From: me_

Shell script to add a note to the file ~/notes/TODAYSDATE.txt

### Usage

    $ note started a project
