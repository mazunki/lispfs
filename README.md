
# lispfs

lets you compile a filesystem structure into valid lisp code. someone said everything was a file, so i considered this a bug in the lisp world

fixed

## how to use

run the following to see the output
`bin/lispfs examples/example1`

then looksie at the structure (perhaps with `tree`) to get an idea of the layout

symlinks are not meaningful, they are just a nice bonus. you can use `touch` instead of `ln` if you prefer to.

`[[:digit:]]\+-` prefixes are optional, but if you, for whatever unholy reason, need a symbol called `69-`, then just prefix `00-` to it. they are otherwise used to define the order of things (by your locale's order) , which you often want

##### btw

the code isn't really pretty

TODO: port to lisp

