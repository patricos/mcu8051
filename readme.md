## Software used

Some of the software used is:
* text editor (with asm syntax highlighting),
* 8051 compiler (to intel-hex or bin),
* hex2bin and bin2hex (optional translators),
* programmer software (for now: bascom),
* mcu8051 ide (integrated dev env, with simulator included),
* git for version control.

Ubuntu is a primary OS of choice, but some software packages that I use require Windows.  Works are undertaken to eradicate Windows, and stray towards FOSS only.

## Project goal
The goal of this project is to create programs utilising 8051 in various contexts.  The current list of ideas entails:

### RS232 communication
Using rs232 for transmitting bytes from a PC to the MCU, and bytes transferred to be outputed on P1. 

### Real-time clock
Parametrising MCU's timers such that they can count seconds, minutes, hours.  And there is a representation of hours, minutes and seconds in some memory cells.
Feature request: set and read the clock with with rs232.

### Programmer
Hardware programmer for 89c2051 that would obtain program via its serial port from a PC.  (Since serial port termial shall suffice [with possibly some syntax in place] for program-transfer, the programmer should be platform-agnostic.  I'd love to replace my 20 year old setup with that.)

### To Be Continued
I had a few issues re-starting my 89cX051 programmer after 2-3 years idle in the lowest drawer of the farthest locker on the bottom of a damp cellar.  But finally, the programmer works!  Moreover, one 20 year old PC works too:  on it a bunch of useful ancient software packages.  I love it when the plan comes together.
:-)
