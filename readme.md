# Energenie Pi-mote Command Line Tool

A python script to allow you to control Energenie sockets using a Raspberry Pi with Energenie's Pi-mote attached.

## Usage

To use the script from the command line, enter commands in the format:

```sh
./energenie.py <socket num> <on/off>
```

Note: you will need root privileges to access the GPIO ports

So, to turn on socket one:

```sh
sudo ./energenie.py 1 on
```

To turn off all sockets:

```sh
sudo ./energenie.py 0 off
```

This script supports up to four sockets - the maximum allowed by the board.
## Other Resources

* [MiniGirlGeek's demo](https://github.com/MiniGirlGeek/energenie-demo)
* [Energenie's example script](https://energenie4u.co.uk/res/pdfs/ENER314%20UM.pdf)
