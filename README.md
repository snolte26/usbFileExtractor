# usbFileExtractor
A file extractor to mimic a Bash Bunny payload

## Basics: 

In the most basic sense, this script "steals" files from a computer. The purpose is to highlight and educate on the importance of locking down your computer before you leave your computer or workstation. Leaving your computer unattended leaves you vulnerable to attacks that compromises your files

Placing the .exe in a flash drive allows someone to run the attack on any windows machine. When ran, the script creates a "loot" directory with subdirectories for the desktop, documents, and pictures loot. The script then copies all the files and folders from the desktop, documents, and pictures and puts them in the corresponding loot folders

## Inspiration:

Inspiraction for this project comes from a video from The Modern Rogue, where they discuss Bash Bunnies and use a similar payload as this script:

https://www.youtube.com/watch?v=HHL92rSE6hk

## Original Bash Bunny Payload:

The Bash Bunny payload was originally developed by hak5

https://shop.hak5.org/products/bash-bunny?variant=31566299145

https://github.com/hak5/bashbunny-payloads/tree/master/payloads/library/exfiltration/simple-usb-extractor

## DISCLAIMER:

I DO NOT condone the use of this tool for illegal or nefarious uses. This tool is for educational purposes only. By using this tool, you assume all legal resopnsibility for the consequences of using this tool
