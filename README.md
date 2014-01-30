NBus1553
========

NBus1553 is an open source library wiritten in C# used to communicate with the military serial data bus called 1553.
Basically this data bus is used by military aircrafts to control the data communication flow between all the digital equipments like MDP, Radar, EFI, etc
If you have never heard about it, please take a look at the http://en.wikipedia.org/wiki/MIL-STD-1553

NBus1553 was developed to make the use of the 1553 easier to any .net developer, since it provides an abstraction between the low level manufacturer layer 

This kind of library is tightly tied to the hardware you are using, so NBus1553 is not different. It was tested only against the Excalibur 1553 PCMCIA Card and there is no guarantee it will work against any other manufacturer.

NBus1553 supports the following transactions:

** RT to Controller Transfer
** RT to RT Transfers.
** Mode Command With Data Word (Transmit)
** Mode Command With Data Word (Receive)

There is no tested support to used these library as a Bus Controller.


