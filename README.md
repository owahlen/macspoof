# macspoof

Change the [MAC address](https://en.wikipedia.org/wiki/MAC_address) of your Apple MacBook to a random number.

## Purpose
This small script allows to give your WiFi network device another Media-Access-Control-Address.

## Installation
Download and copy the script to a location in your PATH and make it executable.
To do so open a terminal an type the following commands:
```
$ wget https://raw.githubusercontent.com/owahlen/macspoof/master/macspoof
$ chmod +x macspoof
$ sudo cp macspoof /usr/local/bin
```

## Execution
Open a terminal and type the following command
```
$ macspoof
```
Afterwards you should be able to reconnect to the WiFi with a different MAC-Address.
