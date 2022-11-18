### Digidesign-001-pci aka Digi001

Its an old pci audio interface, standard 18-channel Rack Mount Configuration, </br>
2-Mic pres with Hi-Z input +Phantom Power, 8 channel line i/o 1/4" TRS, ADAT, S/pdif. </p>

does Not have Alsa drivers, </br>
but works ok on Windows7x32, and has decent sound. </p>

oldschooldaw.com forum web site is 404, had very important links. </p>

the Only way to install Digi001 in Windows7x32 or XPsp3 32-Bit: </br>
Download ProTools 6.4 LE installer, </p>

Digi001 has ASIO drivers v6.1.1, v6.4 and v6.7 maybe 6,9 </p>

Only v6.4 work, </br>
W7x32 needs to install with Compatibility mode: WinXPsp3, </p>

Only works in Windows 32-Bit, No 64-Bit. </br>
havent Tested ReactOS, but should work ok. https://reactos.org/ </p>

Only intel 975x boards work, i tested X58, tweaked almost everything, </br>
problem is related to ACPI, AHCI / MPS Tables v1.4 v1.1 </br>
There was a strange change between 975x and X58 boards, XP and W7. </br>
for example: </br>
Lynx AES16 pci install ok in W7x64 driver 19g, </br>
but driver 20 does Not install on W8.1x64 IF board does Not have True / Complete MPS Tables 1.4 in the Bios </br>
Only msi and ASRock has, Asus does Not, and Gigabyte is unknown. </br>
because of that Maybe X58 Asus Rampage 3 Extreme could work with Digi001 + W7x32, Maybe. </br>
but Asus Rampage 2 has better chance of success. </p>

Q6600 CPU works ok, 2.8Ghz x9 https://www.cpu-world.com/benchmarks/Intel/Core_2_Quad_Q6600.html </p>

the idea of installing Windows7 is to use: ViennaEnsemblePro 5 or 6 </br>
FXMax Teleport works ok in Xp, but Not Newer Nuendo 5 / Cubase 4/6 Nor Newer VST plugins. </br>
havent Tested Reapoer, VSTHost, or any other. </br>
http://fx-max.com/purchase.html </br>
http://fx-max.com/fxt/ </br>

Recommended GPU: AMD HD6590 PCIe </br>
drivers 14.4 for Xp 32-Bits on Windows7x32, </br>
drivers 14.4 for W7 32-Bits, HDMI Audio does Not work. </br>
No W7 driver has HDMI audio, v15 v16 </br>
Vista driver does Not work. </p>

XP works Ok with 4K UHD TVs, 
W7x32 dissabled that feature, Only works FullHD. </br>
problem is related to ACPI, AHCI / MPS Tables v1.4 v1.1 </br>
tested same XP with same HD6590 pcie on X58 board and did Not worked 4k. </br>
Older was better designed, dont know why they changed/damaged that, </br>
probably wanted more profits "damage to sell again." </p>

Vienna Ensemble Pro 5 allows to use newer plugins in other faster machines, </br>
2 machine setup works ok direct 1Gbe FullDuplex, fixed IPv4. </br>
3 or more machines require a powerful & fast Switch / Router, like MikroTik csr109 or better, No Wireess. <br>
Bridge lowers CPU performance too much. </p>

Digi001 Windows Audio WDM drivers v6.4 Do Not Work. </br>
Avid / Digidesign drivers 7.0 does Not work on Windows, OSX seem to still support Digi001, unknown / untested. </p>

P.D. System Clock Needs to be between 2010 & 2016 or wont work. 
