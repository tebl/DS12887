# Simple DS12887
I'm not going to add a complete set of documentation for this, mostly as the chips will disappear before long. And honestly - the project is more of a reminder as to what goes where instead of something that you'd need a complete PCB for. It's great if you need it, or prefer the look of one as compared to some components soldered directly to the pins. I can't tell you which computers it would be compatible with as there are so many computers and so little time, but if you found a *Dallas DS12887* soldered to your "vintage IBM PC or compatible" mainboard - then this is an option as long as supplies last.

![Assembled unit](https://raw.githubusercontent.com/tebl/DS12887/main/gallery/2022-11-01%2023.23.30.jpg)

As for components you're going to need a *Dallas DS12885*, a 32.768Khz crystal (3x8mm, 6pf if you're lucky enough to find one with a datasheet) as well as a CR2032 battery holder. Assembly is easy - all you need is to put the PCB on top of your chip, then bend up and over any pins that have a corresponding solder pad on the top. Solder it in place, add crystal and wire the battery holder leads in the indicated places. The reason for the external battery holder is that on many of my motherboards, a board with a battery directly on it would mean that I couldn't use some of the slots - and I'm still not quite ready to give up on my ISA soundcards.

- Shared project on [PCBWay](https://www.pcbway.com/project/shareproject/Simple_DS12887_dbfa00e8.html)
