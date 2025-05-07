# THIS IS A WORK IN PROGRESS

I'm designing a 40% keyboard just for the fun of it and to learn how to make everything from scratch.  

There should be every required file in Git Repository for you to build your own, I'll also include the bill of materials for both KiCad/JLCPCB and also DigiKey if you wish to solder it all by hand.  

Here a few of the features of the board:

> - USB-C Support (USB2.0 for easy compatibility)
> - ATMEGA32U4 Microcontroller (Easily available and ready firmware support through QMK)
> - Live keymapping through QMK/VIAL
> - Gasket Mounting (Gummy O-Ring)
> - MOSTLY screwless Design (Excluding the four to mount the daughterboard)    
I'll think of more later    

What does the board conceptually look like?  

![3D model/render of the keyboard](/40percent.png)
![Keyboard Layout](/40percentlayout.png)
PgDn and PgUp will be Layer Keys  
Cool!  

> #### Bill of Materials:  
>
> ##### Main Keyboard
>
> - 1 ATMEGA32U4-AUR [DigiKey](https://www.digikey.com.au/en/products/detail/microchip-technology/ATMEGA32U4-AUR/2238241)
> - 1 FA238 16.0000MB-C3 [DigiKey](https://www.digikey.com.au/en/products/detail/epson/FA-238-16-0000MB-C3/2403378)
> - 2 22pf Ceramic Capacitor 50v (0805) [DigiKey](https://www.digikey.com.au/en/products/detail/kemet/C0805C220J5GACTU/411112)
> - 1 1uf Ceramic Capacitor 16v (0805) [DigiKey](https://www.digikey.com.au/en/products/detail/yageo/CC0805KKX7R7BB105/2103103)
> - 1 4.7uf Ceramic Capacitor 25v (0805) [DigiKey](https://www.digikey.com.au/en/products/detail/murata-electronics/GRM219R61E475KA73D/4905426)
> - 2 10K Resistor 5% 1/8W(0805) [DigiKey](https://www.digikey.com.au/en/products/detail/stackpole-electronics-inc/RMCF0805JT10K0/1757762)
> - 1 TL3342F160QG/TR Switch [DigiKey](https://www.digikey.com.au/en/products/detail/e-switch/TL3342F160QG-TR/379003)    
> - 2 SM04B-SRSS-TB JST SH1.0 4Pin Connector [DigiKey](https://www.digikey.com.au/en/products/detail/jst-sales-america-inc/SM04B-SRSS-TB/926710)
> - 1 JST SH1.0 Male/Male Cable (Size not known just yet, also to connect both PCBs)
> - 40 1N4148W/SOD-123 Diodes (0603) [DigiKey](https://www.digikey.com.au/en/products/detail/smc-diode-solutions/1N4148W/6022450)
> - 1 Printed 40percent Case
> - 40 Gateron Hotswap Sockets (Can't find on Digikey, AliExpress?) 
> - 40 MX Compatible Switches (Outemu might not work in the sockets)
> - 1 Suitable Keycap Set
> - This MIGHT be a working O-Ring size? I'll have to find out when I make this. [oリング](https://xn--o-7eu7hjb.com/?pid=81334721)
> ##### USB-C Daughter Board
> - 1 USB4105-GF-A-060 USB-C 16pin [DigiKey](https://www.digikey.com.au/en/products/detail/gct/USB4105-GF-A-060/14559036)
> - 2 5.1k Resistor 5% 1/8W (0805) [DigiKey](https://www.digikey.com.au/en/products/detail/yageo/RC0805JR-075K1L/728338)
> - 4 M2 4mm Bolts (Screw straight into posts, if you for some reason chose to mill the case, tap it out... it's at 1.6mm ID)
> - One of the JST connectors from above
> - 1 USB-C to USB-C\A cable
> ### I'd recommend ordering a few more than you need at minimum, just incase you fuck it up. Better safe than sorry. Also, cut down on shipping cost :)

# That's pretty much it so far!
