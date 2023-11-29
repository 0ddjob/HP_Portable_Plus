HP Portable Plus (Model 45711)
------------------------------

The Portable Plus was a "simple" MS-DOS compatible machine running on an 80C86.  By simple I mean there is no in-built floppy drive and various ports ... there's just a DE9 RS232 serial port and a HP-IL interface (Hewlett Packard Interface Loop) for connecting peripherals.  Oh, you could also get an internal modem.  Nice and simple.

My example is the 45711B ... the "B" indicates 128KB RAM and no modem:
- 45711A ... 128KB, modem
- 45711B ... 128KB, no modem
- 45711C ... 256KB, modem
- 45711D ... 256KB, no modem
- 45711E ... 512KB, modem
- 45711F ... 512KB, no modem

An additional letter indicates the language/keyboard, for example 45711FF indicates French.  No additional letter means the US version.  More information from the documentation here:
http://www.hpmuseum.net/exhibit.php?hwdoc=49

{The service manual is pretty good}

There are some expansion options - I have an additional 128KB of RAM in a "memory drawer":
- 82981A ... 128KB expansion RAM
- 82992A ... 1MB expansion RAM
- 82982A ... Software Drawer for ROMs
- 82984A ... some sort of expansion with 128KB ... not sure
- 82985A ... video interface

The machine comes with 192KB of ROM.

It uses an obsolete Panasonic LCR-226P but there are equivalents available. Some minor modifications need to be made to convert a new battery for use in the 45711.

It requires a 10-13VAC transformer for recharging the battery via a custom socket/plug.  Of course, a standard socket could be installed to bypass this if you don't have the plug.

I also need to finish building the USB-to-HPIL interface I have so I can transfer software:
http://www.jeffcalc.hp41.eu/hpil/
