# Curb Wheel BLE

The repository holds the source code for the Raspberry Pi Zero image for running the Curbwheel. The source code for the Android/iOS CurbWheel app is available at [https://github.com/sharedstreets/curb-wheel](https://github.com/sharedstreets/curb-wheel).

## Installation

1. Download the [Etcher software](https://www.balena.io/etcher/) app for your computer and install it. You will use this to set up the microSD card. Select the appropriate download for your computer (Windows vs Mac OS).

2. Download the [zip file](https://curblr-www.s3.amazonaws.com/wheel/images/curbwheel_image_bleno_r1.img.gz) to install on your microSD. Unzip the file if it does not automatically unzip once downloaded. 

3. Insert your microSD into your card reader and open Etcher. Select the unzipped file as the image. Select your microSD card as the target. It is important to point this at the microSD card as this could rewrite your hard drive if the wrong location is selected. 

3. (cont’d) Once this is set up properly, write the file to the microSD by selecting 'Flash!'. This step may prompt you to enter a password, this is your computer account password.

4. Eject and remove the microSD card. Insert your microSD card into the reader on your Raspberry Pi.

5. Plug your Pi into a power source (such as a power bank that you would use to recharge your phone, or a charging cable plugged into the wall) using the microUSB port labelled "PWR in". If you're using a power bank, make sure it's turned on. You should then see a green blinking light on your Pi with a heart beat pattern which indicates the image is running properly.


## Releases

* R1 [downlaod](https://curblr-www.s3.amazonaws.com/wheel/images/curbwheel_image_bleno_r1.img.gz) 
