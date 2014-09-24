AUTHOR: David Brown
VERSION: 1.5
------------------------------
REQUIREMENTS/DEPENDENCIES

tintin++ debian bases) sudo apt-get install tintin++
sox (debian bases) sudo apt-get install sox
mplayer (debian bases) sudo apt-get install mplayer

------------------------------
DESCRIPTION:
This sound pack has been created for the game Miriani. It's origins are in the VIPMUD sound pack for Windows based operating systems. I have attempted to duplicate as much of the VIPMUD sound pack onto the Linux operating system. I plan to sometime in the future test it on Mac OS.X and make sure it works there as well.

------------------------------
KNOWN ISSUES
------------------------------
SUPPORT, FEATURE REQUESTS, and BUGS

please read the following section carefully before submitting any emails.

the address is tmirsp@gmail.com

Please use the following formats in the subject line
	SUPPORT: "Your question here"
For bugs or issues
	BUG/ISSUE: "Your problem here"
For feature requests
	FEATURE REQUEST: "Your request here"
For general feedback
	FEEDBACK: "The subject of feedback"
------------------------------
NOTES

the variable "os" stands for "output silencer"

the variable "vol" stands for "volume"

on ubuntu mplayer might be already installed you may have to uninstall it and reinstall it for it to work properly
uninstall: sudo apt-get purge mplayer
reinstall: sudo apt-get install mplayer
------------------------------
OTHER CONTRIBUTIONS BY:
Malik Wilson <wilsonmalik12@gmail.com>
Justin Heard <braillemasterjustin@gmail.com>

------------------------------
CHANGELOG

09/28/13
	Added activate and deactivate sounds for devices such as flight control scanners and metafrequency communicators.
09/30/13
	added trigger to make communicators play the activate and deactivate sounds.
10/02/13
	fixed an error where the sound pack was not being registered with the game.
	modified some socials to work with the sound pack messages from the MUD.
	added sound for "this ship transmits" line during general sector communication conversations.
	added substitute for using point units to make the message shorter and have the same invaluable information.
10/03/13
	shortened all planetary mining drone messages to be less verbose but still get across the point.
	added support for whistling sound.
10/09/13
	implemented some variables to check the last received message for "private", "short range", "frequency", and "P.A" (in progress)
10/14/13
	began implementing multiple sounds for triggers. Example: random laughs are now possible (unfinished)
	added another variable to check the last flight control message.
10/16/13
	continued work on implementing multiple sounds including lots of socials and levers.
10/28/13
	got galactic coordinate calculator (gcc) working.
	added the "spreload" command for your soundpack reloading convenience.
10/30/13
	setup variables and got an after mission report working. (calculates total hits, direct hits, and partial hits)
11/1/13
	added accelerate sound for entering jumpgates and added decelerate sound for exiting jumpgates.
	added cover and uncover sounds.
11/4/13
	changed sounds for accelerate, decelerate, and atmo salvaging.
	added fuzzy sounds (let me know if they are still broken for any reason).
11/6/13
	changed the $DIR variable to .
11/17/13
	added disarm, disrupt, interrupt, and immobilize pulse sounds.
11/26/13
	Made a lag calculator. (it will never say 0 because it times from when you send a command until you get the responce)
12/11/13
	made ambiances work... (FINALLY)
08/31/14
	fixed launch sound file issue
09/12/14
	enabled log functionality. these can be found in ./logs/ directory.
	enabled volume changes for ambiance as well as standard sounds
09/13/14
	Added radio streaming functionality
09/24/14
	Added sound for lore file import
