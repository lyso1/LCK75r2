
# LCK75r2

The 2nd revision of the LCK75, this is updated to supported more layouts options such as ISO and split backspace. 

You can find the BOM for the mainboard here - https://octopart.com/bom-tool/ZgQKLyxD

![LCK75-Mainboard](https://cdn.discordapp.com/attachments/362014190984101899/941489778023628861/d5785ce7c6750694bd8e476ec2901076.png "1")

![LCK75-Mainboard2](https://cdn.discordapp.com/attachments/362014190984101899/941489779403550750/bf7b0f2e6338409b384ffbbd42bb0aa3.png "2")

![LCK75-Plate](https://cdn.discordapp.com/attachments/362014190984101899/941489779072176148/9bdf50bbd58ba28e368ccc6ca0779843.png "3")

![LCK75-Plate2](https://cdn.discordapp.com/attachments/362014190984101899/941489778560466975/e0f38fb05c1ef4937056d44388c4da53.png "4")

![LCK75-Bottom](https://cdn.discordapp.com/attachments/362014190984101899/941489778803761202/e5abce592489952574219ae9630de2b9.png "5")

![LCK75-Bottom2](https://cdn.discordapp.com/attachments/362014190984101899/941489780003332096/c150f6a2bf9414626f1b7359fe170753.png "6")

This is under the MIT liscense, due to this, i will not be held responsible for your endeavors with private runs of this board. 

if you have questions reach out to me on discord @Lysol#5640
_______________________________________________________________________________
# Here is a build guide/Solering guide for this project.
## Diodes
With your main board in fornt of you, we shall first tackle the biggest job, the switch diodes. these diodes are directional and for this, youll need to allign the black stripe on the diodes tro the bottom square hole of each diode location. (these diodes are not marked unlike the two zener diodes marked with a Z in the kit

![Imgur](https://imgur.com/K4UzXyE.png "top")
![Imgur](https://imgur.com/OZejtVx.png "2")
![Imgur](https://imgur.com/D1THLr8.png "4")

From there you'll need to solder the leads from the rear of the board(clip excess wire as you go or wait till the end).

Use tape, preferebly Kapton tape, to keep the diodes in place as you flip the board over to solder but you may be fine with just bending the dioe leads outwards on the back side of the board.



Repeat untill you fill nearly all switch diode locations aside from layout option diodes like Split-BackSpace or ISO unless you want those layouts

![Imgur](https://imgur.com/je845uA.png "3")

## Voltage controlling components
Now to the components that control the board's voltage. Here we are going to be soldering C1 & C2 the 22pF capacitors, C4 & C5 the 0.1uF Capacitors, and Y1 the 16mhz crystal(this allows the mcu to properly communicate to the device you are plugging the keyboard into. 

NOTE: As you insert these components bend the leads on the back side of the board to prevent them from falling out.

![Imgur](https://imgur.com/W6Fijdj.png "5")

## MCU
Here we are going to install the 40pin IC holder for the ATMEGA32a MCU that powers this board. 
We will be saving socketing the mcu in until all required soldering is completed to test the board

![Imgur](https://imgur.com/xZcQtYe.png "5")

## Top compeonents
All resistors in the kit are lebeled in the kit but if you feel like you need to double check you can use an online resistor calulator 
as for the zener diodes, they are directional and look similar to the normal switch diodes BUT their operational voltage is way higher at 3.6v. 

DO NOT MIX THEM UP!
![Imgur](https://imgur.com/5AgdAVf.png "5")

## Top compeonents cont.
now onto the 4.7uF Capacitor, BOOT & RESET push buttons, the 6 pin ISP header, and Fuse. as you insert these components bend the leads on the back side of the board to prevent them from falling out.

![Imgur](https://imgur.com/5AgdAVf.png "5")

## OLED
Now onto the OLED header, for this we are going to use the foam backing that came with the mcu and use it to support the oled module as we fipe the board over to solder it in.

![Imgur](https://imgur.com/5AgdAVf.png "5")

## Rotary Encoder
finally the EC-11 encoder, youll need to make sure you solder this in first before putting the switch plate over and start soldering switches as the leads going to to the encoder are slightly wider then the plate cutout. youll need to 


![Imgur](https://imgur.com/D1THLr8.png "4")

![Imgur](https://imgur.com/5AgdAVf.png "5")
