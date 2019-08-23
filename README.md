# dmenu a bit modified

added `-bo` and `-c` in addition of the following patches :  

+ center (modified to add option)
+ border (modified to add option)
+ fuzzymatch
+ lineheight
+ xyz

`-bo` require a value that sets the border width, `-c` is a standalone arg that centers dmenu.  

borders are supported even in "docked" mode (the default positionning method)

## original README :

```
dmenu - dynamic menu
====================
dmenu is an efficient dynamic menu for X.


Requirements
------------
In order to build dmenu you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install


Running dmenu
-------------
See the man page for details.
```
