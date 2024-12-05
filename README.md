# some help with this

In order to use this, you must put the "ancient_hebrew" file into /usr/share/X11/xkb/symbols  

The way I put the language in the settings options is I went to /usr/share/X11/xkb/rules/evdev.xml and searched for the custom layout thing, I changed the <name> to "ancient_hebrew" and it recognized my file, gave some descriptions and put the <iso639Id> thing to "und" so it works properly.. it didn't work before when I put "he" there (hebrew).
I'm talking about this in first person because I'm a noobie and it's the way I did it in Linux Mint, I'm not sure if it will work on other distributions or desktops.
It will definetely not work unless you use X11.
