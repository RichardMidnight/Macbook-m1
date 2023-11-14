# Macbook-m1
Adventures with a Macbook m1

Virtual machines on an M1 Macbook.

Virtualization software

      Virtualbox does not currently run on an M1 Mac.
      UTM does and seems pretty good.   (This is what I am using)
      Paralells and _____ also exist.

To install UTM

      Go to the Mac App Store and search for "UTM Virtual Machines" and install it.

To run Debian on M1 Mac with UTM

    Download Debian from here:  https://www.debian.org/distrib/netinst 
    Save the Small CD / ARM64 file to Downloads folder: https://deb.debian.org/debian/dists/bookworm/main/installer-arm64/current/images/ 
    
    Start UTM, New, Virtulaize, Linux, Boot ISO Image, Browse, point to your debian download image.
    The defaults are pretty good, but you can adjust as desired.

    Start up the UTM virtual machine.  It should boot the the downloaded CD image.  Select Grapical install.
    The defaults are pretty good.  Probably limit the cores to 2-4.  Can reduce the HDD to 32GB.
    Recomend the KDE Plasma Desktop Environment, but you can play with the others.
    When it is complete and asking to reboot, FIRST select the "Drive Image Options" in the upper right corner, and Eject the Debian image so it boots from HDD.
    Then Continue to reboot.

    Once it boots up:
    Terminal, SU, password, sudo adduser USER sudo,  then reboot

    For a more Windows-like experience, run "global theme", Get new Global Themes, Search for Windows ....
    

    
To run Windows on M1 Mac with UTM

      Install Crystalfetch from App store

      Run Crystalfetch and Download Windows 11 for Apple Silicon to your Downloads Folder.  Win 10 may not work.

      Start UTM, New, Virtulize, Windows, ...
      You neet to select EUFI and TPM-2

      You will need to buy and apply a Windows license.
      
      

