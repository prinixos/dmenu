# dmenu-prinix1014


# What is dmenu?
dmenu is a dynamic menu for X, originally designed for dwm. It manages large numbers of user-defined menu items efficiently.  It is a very powerful tool that allows you to pipe information into it.  This makes dmenu a perfect utility to incorporate into your scripting.

# What is dmenu-distrotube
dmenu-distroube is my personal build of dmenu that is very heavily patched to add more functionality and more customization options.  The patches that I used in this build include:
+ dmenu-caseinsensitive -- case insesitive search
+ dmenu-lineheight -- adds a flag (-h) to set the minimum height of dmenu lines
+ dmenu-morecolor -- creates a color option for use the entries adjacent to the selection
+ dmenu-numbers -- shows the number of result / total number
* Mouse functionality

# Available flags
+ [-l lines]
+ [-p prompt]
+ [-fn font]
+ [-m monitor]
+ [-h height]
+ [-nb color]
+ [-nf color]
+ [-sb color]
+ [-sf color]
+ [-nhb color]
+ [-nhf color]
+ [-shb color]
+ [-shf color]
+ [-w windowid]

An example: dmenu_run

This launches dmenu_run will automatically run with all my configuration No need to add any flags.

# How to install dmenu-prinix1014
To install dmenu-prinix1014 on most Linux systems, simply clone this repository, then cd into the cloned directory, and finally run a: sudo make install
