iso2usb - Make your life easy on Mac!
============

# Why?
I often wanted to burn iso files to usb but it seemed like a real hassle, I looked for a useful gui tool but couldnt find one, so I wrote this awesome bash script

# Installation
It's very easy, just run the following command to install into /usr/local/bin

`wget -q -O /usr/local/bin/iso2usb https://raw.githubusercontent.com/hongkongkiwi/iso2usb/master/iso2usb | chmod +x /usr/local/bin`

Once this is complete you can simply run it from the command line like any other command using `iso2usb`

# Usage
`iso2usb file.iso /dev/disk#` (where # is the disk number of the USB drive, you can find this using `diskutil list` from console)

# Help make it better
I have a few things on the todo list, mostly I would like to be able to detect all plugged in USB drives and give those as a selection to the user if they don't pass one

Pull requests are welcome!

