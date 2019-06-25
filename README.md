# DE0-Nano adapter board for PiDP-11

This is an adapter board to connect the
[DE0-Nano  FPGA Development board](http://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&No=593)
to the [PiDP-11, PDP-11/70 front panel replica](https://obsolescence.wixsite.com/obsolescence/pidp-11).
It is intended to be used with [PDP2011, an FPGA implementation of PDP-11](http://pdp2011.sytse.net/wordpress/).

In addition to routing the necessary pins to the panel, the board also
includes some components for use with the PDP2011:
* Micro-SDCard connector
* USB-UART bridge using the [CP2102](https://www.silabs.com/products/interface/usb-bridges/classic-usb-bridges/device.cp2102)
* Additional pin headers for a secondary UART connection
* Pin headers for connecting to [PMODNIC100](https://store.digilentinc.com/pmod-nic100-network-interface-controller/)

The pinout is a direct implementation of those
[described Sytse in his blog](http://pdp2011.sytse.net/wordpress/wiring/).

The components used are basically what I had lying around.
If you wish to make this board yourself, consider changing the design to
match the components most optimal for you.
