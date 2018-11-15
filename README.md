# macspoof

Change the [MAC address](https://de.wikipedia.org/wiki/MAC-Adresse) of your Apple MacBook to a random number.

## Purpose
This small script allow to give your WiFi network device another Media-Access-Control-Address.

## Installation
Download and copy the script to a location in your PATH and make it executable.
To do so open a terminal an type the following commands:
```
$ cp macspoof /usr/local/bin
$ chmod +x /usr/local/bin/macspoof
```

## Execution
Open a terminal and type the following command
```
$ macspoof
```
Afterwards you should be able to reconnect to the WiFi with a different MAC-Address.
