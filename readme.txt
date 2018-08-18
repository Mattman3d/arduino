THIS IF FOR LINUX.

Make a new folder for every project and copy a Makefile into every folder

CHANGE Permission
/dev/ttyACM0		might be /dev/ttyACM*	(*means other)
using: sudo chown <username> /dev/ttyACM0
or
USED: sudo chmod 666 /dev/ttyACM0		(probally better)

sudo apt install arduino-mk	for tool *Requires make file!!!
sudo apt install screen

Makefile
make
make upload
make monitor			activates screen
make clean
make upload monitor clean	does it all at once

SCREEN COMMANDS
screen -list		for avaiables outputs
screen -r		For return access to output(to default)
screen -X quit		quits

inside SCREEN
ctrl-a ctrl-d		Leaves screen

while screen is running no uploads can be made