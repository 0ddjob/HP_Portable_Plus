Configuration EPROM (U30)
-------------------------
Taken from a 45711B (128KB base RAM) with serial number 2549A07023

The configuration EPROM (erasable/programmable read-only memory, designated U30
on the memory PCA) can be configured as an 8K-byte device (standard) or as a
16K-byte device.
A 32K-byte device can be used, but only the upper 16K bytes are addressable,
since PGM (pin 27) is connected to VccS. The EPROM is connected to the I/O
address and data buses.
Typically, a configuration EPROM contains the computer's unique serial number
and information about keyboard mapping, display fonts, and hardware
configuration, including the amount of built-in RAM.
The CPU uses this information to determine system operation.
The configuration EPROM is programmed differently for each language, but all
versions use the same unprogrammed EPROM as a replacement.

System ROM (U16/17/18/27/28/29)
-------------------------------
These are Toshiba TC53257P 256Kbit/32Kbyte masked ROMs, pin equivalent to
Toshiba TC57256D 256Kbit EPROMs (same pinout as 27256).

U16 = 1818-3668
U17 = 1818-3669
U18 = 1818-3670
U27 = 1818-3671
U28 = 1818-3672
U29 = 1818-3673

The service manual instead mentions only two 128Kbyte ROMs: U16 & U27
So it's possible that later revisions replaced the six 32KByte EPROMs (192Kbyte
of System ROM) with only two 128Kbyte ROMs.

![Memory PCA](HP_45711_Memory_PCA.jpg)
