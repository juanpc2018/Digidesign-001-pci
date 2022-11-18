### Digidesign-001-pci aka Digi001

Its an old audio interface, standard Rack Mount Configuration,
2-Mic pres with Hi-Z input, 8 channel i/o 1/4" TRS, ADAT, S/pdif.

does Not have Alsa drivers,
but works on Windows7x32, and has decent sound.

oldschooldaw.com forum web site is 404, had very important links.

the Only way to install Digi001 in Windows7x32 or XPsp3 32-Bit:

Download ProTools 6.4 LE installer,

Digi001 has ASIO drivers v6.1.1, v6.4 and v6.7 maybe 6,9

Only v6.4 work,
needs to install with Compatibility mode: WinXPsp3,

Only works in Windows 32-Bit,
havent Tested ReactOS, but should work ok. https://reactos.org/

Only intel 975x boards work, i tested X58, tweaked almost everything, 
problem is related to ACPI, AHCI / MPS Tables v1.4 v1.1
There was a strange change between 975x and X58 boards.

Q6600 CPU works ok, 2.8Ghz x9

the idea of installing Windows7 is to use: Vienna Ensemble Pro 5 or 6 
FXMax Teleport works in Xp, but Not Newer Nuendo 5 / Cubase 4/6.
havent Tested Reapoer, VSTHost, or any other.
http://fx-max.com/purchase.html
http://fx-max.com/fxt/

Recommended GPU: AMD HD6590 PCIe
drivers 14.4 for Xp 32-Bits on Windows7x32,
drivers 14.4 for W7 32-Bits, HDMI Audio does Not work.
No W7 driver has HDMI audio, v15 v16 

XP works Ok with 4K UHD TVs,
W7x32 dissabled that feature, Only works FullHD,

Vienna Ensemble Pro 5 allows to use newer plugins in other faster machines,
2 machine setup works ok with direct 1Gbe FullDuplex, fixed IPv4. 

3 or more machines require a powerful & fast Switch / Router, like MikroTik csr109 or better. 
Bridge lowers CPU performance too much.

Digi001 Windows Audio WDM drivers v6.4 Do Not Work.
Avid / Digidesign drivers 7.0 does Not work on Windows, OSX seem to still support Digi001, unknown / untested.

