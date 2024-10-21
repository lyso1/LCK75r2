
# LCK75 - R2 & R3

The nearly final iteration of the LCK75, the main changes are the increased trace width, bigger soldering pads, and another overhual for the trace routing. 

You can find the BOM for the mainboard here - https://octopart.com/bom-tool/ZgQKLyxD

![Imgur](https://imgur.com/YtXoAaF.png "1")

![Imgur](https://imgur.com/nzXxHEl.png "2")

![Imgur](https://imgur.com/zLgx0jd.png "3")

![Imgur](https://imgur.com/6JiJl66.png "4")

![Imgur](https://imgur.com/bwwttXl.png "5")

![Imgur](https://imgur.com/avkIRg0.png "6")

This is under the MIT liscense, due to this, i will not be held responsible for your endeavors with private runs of this board. however i will provide a build guide and solder guide.

if you have questions reach out to me on discord @Lysol#5640
_______________________________________________________________________________
# Here is a build guide/Solering guide for this project.
![Imgur](https://imgur.com/K4UzXyE.png "top")
## Diodes
With your main board in fornt of you, we shall first tackle the biggest job, the switch diodes. these diodes are directional and for this, youll need to allign the black stripe on the diodes tro the bottom square hole of each diode location. (these diodes are not marked unlike the two zener diodes marked with a Z in the kit)

DO NOT MIX THE DIODES UP. KEEP THE ZENER DIODES OFF TO THE SIDE!

![Imgur](https://imgur.com/OZejtVx.png "2")
![Imgur](https://imgur.com/D1THLr8.png "4")

From there you'll need to solder the leads from the rear of the board(clip excess wire as you go or wait till the end).

Use tape, preferebly Kapton tape, to keep the diodes in place as you flip the board over to solder but you may be fine with just bending the dioe leads outwards on the back side of the board.

Repeat untill you fill nearly all switch diode locations aside from layout option diodes like Split-BackSpace or ISO unless you want those layouts
![Imgur](https://imgur.com/je845uA.png "3")

## MCU IC HOLDER
Here we are going to install the 40pin IC holder for the ATMEGA32a MCU that powers this board. allign the notch of the holder with the silk screen of the board.

We will be saving socketing the mcu in until all required soldering is completed to test the board.

![Imgur](https://imgur.com/xZcQtYe.png "5")

## Top Components pt. 1
Now to the components that control the board's voltage. Here we are going to be soldering C1 & C2 the 22pF capacitors, C4 & C5 the 0.1uF Capacitors, and Y1 the 16mhz crystal(this allows the mcu to properly communicate to the device you are plugging the keyboard into. 

These components aren't directional so feel free solder them how ever you'd like similar to the diagram below.

NOTE: As you insert these componentsm, bend the leads on the back side of the board to prevent them from falling out as you fip the board to solder them in.

![Imgur](https://imgur.com/W6Fijdj.png "5")

## Top compeonents pt. 2
All resistors in the kit are lebeled in the kit but if you feel like you need to double check you can use an online resistor calulator like the one from Digikey.

![Imgur](https://imgur.com/BXbayoe.png "5")

## Top compeonents pt. 3
The 4.7uF Round Capacitor, BOOT & RESET Push Buttons, the 6 pin ISP Flashing Header, 3.6v Zener Diodes(the ones marked Z), and the Fuse.

As you insert these components bend the leads outwards on the back side of the board to prevent them from falling out.

NOTE: THE ROUND 4.7uF CAPACITOR & ZENER DIODES ARE DIRECTIONAL! MAKE SURE THEIR RESPECTIVE POLARITY IS FOLLOWED AS SEEN IN THE DIAGRAM BELOW.

![Imgur](https://imgur.com/L1iEmgu.png "5")

## OLED Module
For the OLED header, we are going to use the foam backing that came with the mcu and socket, and position it to support the underside of the oled module as we flip the board over to solder the pins in.

NOTE: LEAVE THE PROTECTIVE LAYER ON THE OLED UNTIL ALL SOLDERING IS COMPLETE

![Imgur](https://imgur.com/fnMXRKX.png "5")

## Rotary Encoder
finally the EC-11 encoder, youll need to make sure you solder this in first before putting the switch plate over and start soldering switches as the leads going to to the encoder are slightly wider then the plate cutout. 

For soldering youll need to get the positioning "latches" on the side of the encoder bent inwards after seating the encoder flat on the board to secure it to the board. 

From there its just making sure you have the orientation correct for the data pins on the north and south of the encoder. reference the diagram below. 

![Imgur](https://imgur.com/zAj7gUC.png "4")
![Imgur](https://imgur.com/iCFOCfg.png "4")

From here you trim any excess leads from any comonents sticking out on the other side, be careful not to trim too close to the actual board to avoid damaging any traces. 

You should be good to socket in the MCU in at this point and to ensure it sockets in smoothly,  you may need to bend the legs in-ward. 

As for testing software personally i use EK switch hitter but VIAL(firmware) can be used for testing as well.
![Imgur](https://imgur.com/p4ab9q0.png "5")
After all this you should have a fully functioning LCK75 Mainboard. once you solder in you switches and install your stabilisers, you are at the final set of steps.

## Stack Assembly 
From here youll need the bottom backplate and install the m2 screws and nylon standoffs with the screw heads visible from the logo side.
![Imgur](https://imgur.com/t2Nw9Rs.png "6")

From here place the foam piece included in the kit in between the standoffs. it will only go in one way.
![Imgur](https://imgur.com/Qb2qxlj.png "6")

Use 6 more screws and standoffs on the main board. the screw heads should be on the backside of the mainboard where you did the soldering.

(ignore the fact the diagram is missing switches and stabilizers) 
![Imgur](https://imgur.com/ttwY9YN.png "6")

From here after soldering all your switches and installing your stabilizers, place and align the switch plate holes with the to the nylon standoffs sticking through the back plate and foam layers.
![Imgur](https://imgur.com/xNfRsY1.png "6")

Place the included rubber angling feet from the kit on backplate.
![Imgur](https://imgur.com/xMvL4rU.png "6")

Finally use a set of keycaps of your choice and enjoy the keyboard.
![Imgur](https://imgur.com/dyo0pXA.png "6")
