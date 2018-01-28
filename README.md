# arch-chromebook
Random Stuff to Make Arch work properly on my samsung chromebook 2 -- also works on my sons acer cb3-111 ... may work on others.

Use caution ... may cause your computer to self destruct.  Not looking to support this but if it helps then by all means use it.  I stole most of this from duffydack, just re-enabled the touchpad drivers in the kernel.  
Original Here --> https://github.com/duffydack/linux-max98090

Install: 
Add the following to /etc/pacman.conf

[thescruggs]
SigLevel = Optional TrustAll
Server=https://github.com/thescruggs/arch-chromebook/raw/master

pacman -Sy linux-thescruggs linux-thescruggs-headers

Modify your bootloader of choice to see the images.

Items:
thescruggs-linux -- Fixed Baytrail Audio and working Touchpad
thescruggs-linux-headers
