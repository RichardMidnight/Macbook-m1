# Macbook-m1
Adventures with a Macbook m1


Virtual machines on an M1 Macbook.

Virtualbox does not currently run on an M1 Mac.
UTM does and seems pretty good.   (This is what I am using)
Paralells and _____ also exist.

To install UTM

      Go to the Mac App Store and search for "UTM Virtual Machines" and install it.

To run Debian on UTM

    Download Debian from here:  https://www.debian.org/distrib/netinst 
    Save the Small CD / ARM64 file to Downloads folder: https://deb.debian.org/debian/dists/bookworm/main/installer-arm64/current/images/ 
    
    Start UTM, New, Virtulaize, Linux, Boot ISO Image, Browse, point to your download.
    The defaults are pretty good, but you can adjust as desired.

    Start it up, and it should boot the the downloaded CD image.  Select Grapical install.
    The defaults are pretty good.
    Recomend the KDE Plasma Desktop Environment, but you can play with the others.
    
