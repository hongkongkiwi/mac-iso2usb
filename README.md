iso2usb - Make your life easy on Mac!
============

# Why?
I often wanted to burn iso files to usb but it seemed like a real hassle, I looked for a useful gui tool but couldnt find one, so I wrote this awesome bash script

# Installation
It's very easy, just run the following command to install into /usr/local/bin

`wget -q -O /usr/local/bin/iso2usb https://raw.githubusercontent.com/hongkongkiwi/iso2usb/master/iso2usb | chmod +x /usr/local/bin`

Once this is complete you can simply run it from the command line like any other command using `iso2usb`

# Usage

If you want to pass the device directly (get the device from `diskutil list`)

`iso2usb file.iso /dev/disk#` (# is a disk number)

If you want to bring up a selection of USB devices and select from the menu (potentially more dangerous)

`iso2usb file.iso`

# Help make it better

Pull requests are welcome!

