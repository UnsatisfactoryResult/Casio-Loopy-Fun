# Casio-Loopy-Fun

If you're looking for a compatible US power supply you'll need one with 24 volts, 1A, and a 2.1x5.5mm center positive barrel connector. Triad Magnetics WSU240-1000 or WSU240-1500 are two high quality options. These are 1 amp and 1.5 amp output respectively. If you plan to get a Magical Shop, flashcart, and USBRetro adapter then it may be worth the extra headroom of the 1.5 amp version.

Flashcart? Yep. PartlyHuman has made a flashcart for the Loopy called the Floopy Drive. It is open source, so you can make one yourself, or purchase one from his Tindie store. Check out his repo here: https://github.com/partlyhuman/loopycart

USBRetro? Yep, it's still in the prototype phase, but Robert Dale Smith's prototype is fully functional. This allows you to use USB controller and mice with the Loopy. The controller connector is proprietary, and replacements are being explored. I am creating a USB interface that mounts to the RGB/S Video/Composite mod I'm working on. This outputs video through a 10 pin minidin located where the video rca was. The USB port occupies one of the audio rca ports. Check out Robert's repo here: https://github.com/RobertDaleSmith/USBRetro

Wait, RGB? Yes, I'm working on a video mod that will use Sega Saturn cables. I have a working prototype, but I'm chaising noise right now.

You'll find datasheets for the through hole capacitors used on the I/O board and power supply board.

The main board uses all smd capacitors that are only marked with capacitance and voltage.

C504 on the I/O board is installed backwards. Ignore the board markings, and confirm with a multi meter. (Thanks to Kasami for pointing this out.)

Keep in mind that my console is a very early production unit that uses a revision B main board
which was apparently not used for very long. Some info here may not apply to the later rev C boards.

I made a DigiKey list for replacement caps utilizing the following:

Nichicon UWD caps for the main board

Nichicon UCS and UPA for the power supply

Chemi-Con KMG for the I/O board

Rev B
https://www.digikey.com/en/mylists/list/SPZKPT0VS9

Rev C
Coming soon...
