# Mission

See if I can make libZotero work.  If I can, see if that helps this lesson https://programminghistorian.org/en/lessons/retired/intro-to-the-zotero-api

# Steps / Work

I am folowing this lesson

https://programminghistorian.org/en/lessons/retired/intro-to-the-zotero-api

On my PC went into bash

In my pc this is the working directory
...hist3814\zotero

I went to https://github.com/fcheslack/libZotero
Downloaded the zip and extracted it to  ...hist3814\zotero

in ...hist3814\zotero
I did
pip install libZotero

Upgraded pip
python -m pip install --upgrade pip

In
...hist3814\zotero\libZotero-master\lib\py\libZotero
exceptions.py
added:

class Exceptions(Exception):
    """Base class for exceptions in this module."""
    pass

---
It seems I have to do a whole lot of updates to prepend "libZotero"  import libZotero.zotero

Also update for Python 3
