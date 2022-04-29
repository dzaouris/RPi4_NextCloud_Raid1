# RPi4_NextCloud_Raid1
Raspberry Pi 4 Nextcloud server with RAID 1 for redundancy

## Introduction
In this repo I will describe, step-by-step, how to setup a NextCloud server using a Rasberry Pi 4. The setup will also include two 2 TB hard drives arranged in a RAID 1 configuation for redundancy. The sections below include detailed instructions and photos for each step

## Hardware
In this section all the equipment used for this project is listed. Next to each component there is also a link for the purchase webpage.

* Raspberry Pi 4 Model B Starter Kit (It includes the Raspberry Pi board, a 5.1 V power supply, a HDMI to micro HDMI cable, a raspberry pi case and a 32 GB micro SD card) ([Link](https://thepihut.com/collections/raspberry-pi-kits-and-bundles/products/raspberry-pi-starter-kit))
* 4-Piece Raspberry Pi 4 Heatsink Set ([Link](https://thepihut.com/products/4-piece-raspberry-pi-4-heatsink-set))

## Procedure

### Installing Heatsinks
Installing the heatsinks is an optional step and it is pretty staightforward. Check the photo below (taken from the pihut website) to see which heatsink goes to each component. Then just remove the protective cover sheet and stick the heatsink on top of the component. After finishing that you can put the Raspberry Pi board in the case for protection.

<img src="https://user-images.githubusercontent.com/19223395/148088819-ab996d80-66f4-4a8c-98ba-2c5652550d6b.jpg" width="250" height="250">

### Flashing SD Card
I have used the official Raspberry Pi Imager in order to flash the SD card used in the Raspberry Pi. This will work with Windows, macOS and Ubuntu. You can download Rasberry Pi Imager from the Rarsberry Pi website ([Link](https://www.raspberrypi.com/software/)). Once you download and install the imager, go ahead and run it. You should see the following window appearing on your desktop.

<img src="https://www.raspberrypi.org/app/uploads/2020/03/RPI_intro-e1583228263677.png" width="250">

The next step is to choose an Operating system (press the button on the left of the Imager window). I have chosen the Lite version of Raspbian. Next make sure you have connected the SD card to your computer and by pressing the middle button on the Imager window choose the appropriate option (CAUTION: Make sure you choose the SD card and not any other hard drive!!!). The final step is to actually flash the card. You can achieve that by pressing the button on the righthand side of the Imager window. When the process finishes, a message will appear on your screen stating that Raspbian has been written to the Mass Storage Device. At this point you can remove the SD card from your computer and install it in the Raspberry Pi. 
