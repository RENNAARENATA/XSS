# Vulnerability Dr1ll3r
![Banner](sample.png)

## Installation
For installation you'll need this modules:
>> Requests
>> Time
>> Argparse
>> bs4
>> random
>> urllib
>> pprint
>> colorama
>> asciistuff
>> user_agent
>> 
Yes, quite a lot of modules but...I DON'T CARE Xd

## Usage
` python VulnDriller.py --help `
With this command you can see all possible configurations and choose the best one for you!

## Options
There are 5 options:
1. "-c" or "--custom", use this option if you want to use a custom xss payload for the scan.
2. "-wl" or "--wordlist", use this option if you want to use a wordlist of xss payloads.
3. "-u" or "--site", you have to define this variable since is the actual target that the tool will scan.
4. "-m" or "--mode", you have to define also this variable because is the scanner mode (-m xss for xss scanner and -m lfi for lfi scanner)
5. "-ws" or "--swordlist", DON'T USE THIS OPTION, is still in development, is still in the code because I'm too lazy for delete this and all related things and...its also a leak for the coming versions!


## What I'm going to add...
I'm working for adding an option that allows you to select a list of sites to scan.
After that I'll implement also SQLi. Then some other exploits or other shit :)

Happy Scan!

~Rennaarenata
