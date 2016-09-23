## What it is
A small command-line utility for linux to create bootable usb-s fast and easy - written in python.

## What it does
- Looks through your home directory and lists your ISO files (newest first) to choose one
- Lists your connected USB drives (by their brand and size for easy recognition) to choose one
- Unmount your selected USB if it's mounted
- Formats it as a FAT32 drive
- Puts your selected ISO on it (with the *dd* utility)

## What it needs
- Python 2 or 3
- A system that has the following utilities installed: *find*, *mount*, *mkdosfs* and *dd*

## Why would you need it
I'm the type of user how likes experimenting with different OS-s and distros and found it way too time consuming to manually create the bootable usb-s in the command line. I hope others find this useful as well. 

## How to install it
´´´
pip install bootable-usb
´´´
## How to use it
Just run the following command and after that everything should be self-explanatory
´´´
bootable-usb
´´´

## Other
License can be found in LICENSE.txt
If you encounter any bug pleas report it either here or write an e-mail to **balazs.saros@gmail.com**
Pull requests are very welcome! :)
