
# LCK75 - R2 & R3

The nearly final iteration of the LCK75, the main changes are the increased trace width, bigger soldering pads, and another overhual for the trace routing. 

You can find the BOM for the mainboard here - https://octopart.com/bom-tool/ZgQKLyxD

![LCK75-Mainboard](https://cdn.discordapp.com/attachments/362014190984101899/941489778023628861/d5785ce7c6750694bd8e476ec2901076.png "1")

![LCK75-Mainboard2](https://cdn.discordapp.com/attachments/362014190984101899/941489779403550750/bf7b0f2e6338409b384ffbbd42bb0aa3.png "2")

![LCK75-Plate](https://cdn.discordapp.com/attachments/362014190984101899/941489779072176148/9bdf50bbd58ba28e368ccc6ca0779843.png "3")

![LCK75-Plate2](https://cdn.discordapp.com/attachments/362014190984101899/941489778560466975/e0f38fb05c1ef4937056d44388c4da53.png "4")

![LCK75-Bottom](https://cdn.discordapp.com/attachments/362014190984101899/941489778803761202/e5abce592489952574219ae9630de2b9.png "5")

![LCK75-Bottom2](https://cdn.discordapp.com/attachments/362014190984101899/941489780003332096/c150f6a2bf9414626f1b7359fe170753.png "6")

This is under the MIT liscense, due to this, i will not be held responsible for your endeavors with private runs of this board. however i will provide a build guide and solder guide.

if you have questions reach out to me on discord @Lysol#5640
_______________________________________________________________________________
# Here is a build guide/Solering guide for this project.
## Diodes
With your main board in fornt of you, we shall first tackle the biggest job, the switch diodes. these diodes are directional and for this, youll need to allign the black stripe on the diodes tro the bottom square hole of each diode location. (these diodes are not marked unlike the two zener diodes marked with a Z in the kit)

DO NOT MIX THE DIODES UP. KEEP THE ZENER DIODES OFF TO THE SIDE!

![Imgur](https://imgur.com/K4UzXyE.png "top")
![Imgur](https://imgur.com/OZejtVx.png "2")
![Imgur](https://imgur.com/D1THLr8.png "4")

From there you'll need to solder the leads from the rear of the board(clip excess wire as you go or wait till the end).

Use tape, preferebly Kapton tape, to keep the diodes in place as you flip the board over to solder but you may be fine with just bending the dioe leads outwards on the back side of the board.



Repeat untill you fill nearly all switch diode locations aside from layout option diodes like Split-BackSpace or ISO unless you want those layouts

![Imgur](https://imgur.com/je845uA.png "3")

## Voltage controlling components
Now to the components that control the board's voltage. Here we are going to be soldering C1 & C2 the 22pF capacitors, C4 & C5 the 0.1uF Capacitors, and Y1 the 16mhz crystal(this allows the mcu to properly communicate to the device you are plugging the keyboard into. these components arent directional so feel free solder them how ever you'd likesimilar to the diagram below.

NOTE: As you insert these components bend the leads on the back side of the board to prevent them from falling out.

![Imgur](https://imgur.com/W6Fijdj.png "5")

## MCU
Here we are going to install the 40pin IC holder for the ATMEGA32a MCU that powers this board. 
We will be saving socketing the mcu in until all required soldering is completed to test the board

![Imgur](https://imgur.com/xZcQtYe.png "5")

## Top compeonents
All resistors in the kit are lebeled in the kit but if you feel like you need to double check you can use an online resistor calulator like the one from Digikey.

![Imgur](https://imgur.com/BXbayoe.png "5")

## Top compeonents cont.
The 4.7uF Round Capacitor, BOOT & RESET Push Buttons, the 6 pin ISP Flashing Header, 3.6v Zener Diodes(the ones marked Z), and the Fuse. as you insert these components bend the leads outwards on the back side of the board to prevent them from falling out. the round 4.7uF capacitor & zener diodes are directional, make sure their respective polarity is followed as seen in the diagram below.

![Imgur](https://imgur.com/L1iEmgu.png "5")

## OLED
For the OLED header, we are going to use the foam backing that came with the mcu and socket, and position it to support the underside of the oled module as we flip the board over to solder the pins in.

NOTE: LEAVE THE PROTECTIVE LAYER ON THE OLED UNTIL ALL SOLDERING IS COMPLETE

![Imgur](https://imgur.com/fnMXRKX.png "5")

## Rotary Encoder
finally the EC-11 encoder, youll need to make sure you solder this in first before putting the switch plate over and start soldering switches as the leads going to to the encoder are slightly wider then the plate cutout. for soldering youll need to get the positioning "latches" on the side of the encoder bent inwards after seating the encoder flat on the board. from there its just making sure you have the orientation correct for the data pins on the north and south of the encoder. reference the diagram below. 

![Imgur](https://imgur.com/zAj7gUC.png "4")
![Imgur](https://imgur.com/iCFOCfg.png "4")

from here you trim any excess leads from any comonents sticking out on the other side, be careful not to trim too close to the actual board to avoid damaging any traces. you should be good to socket in the MCU in at this point and to ensure it sockets in smoothly,  you may need to bend the legs in-ward. as for testing software personally i use EK switch hitter but VIAL(firmware) can be used for testing as well.
![Imgur](https://imgur.com/p4ab9q0.png "5")

After all this you should have a fully functioning LCK75 Mainboard. once you solder in you switches and install your stabilisers, you are at the final set of steps.
## stack assembly 
from here youll need the bottom backplate and install the m2 screws and nylon standoffs with the screw hads visible from the logo side.
![Imgur](https://imgur.com/t2Nw9Rs.png "6")
from here place the foam piece included in the kit in between the standoffs. it will only go in one way
![Imgur](https://imgur.com/Qb2qxlj.png "6")
use 6 more screws and standoffs on the main board. the screw heads should be on the backside of the mainboard where you did the soldering.
![Imgur](https://imgur.com/ttwY9YN.png "6")
from here after soldering all your switches and installing your stabilizers, place the mainboard + plate assembly and align theholes with the top plate to the standoffs that you put on the bottom back plate.
![Imgur](https://imgur.com/xNfRsY1.png "6")
![Imgur](https://imgur.com/t2Nw9Rs.png "6")
![Imgur](https://imgur.com/t2Nw9Rs.png "6")
