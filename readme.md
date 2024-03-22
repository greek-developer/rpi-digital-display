# Raspberry PI Digital-Display

## Introduction

This repo holds information on how to use a Raspberry PI to convert a TV or Monitor to a simple digital display using Magic-Mirror and on how to use it.

## Setup

## Usage

### Initial Configuration

When connecting the RPI-DD to a new environment for the first time follow the following steps

* Connect the RPI-DD to the TV/Monitor using a micro-HMDI to HDMI cable.
* Connect a keyboard to the RPI-DD using a micro-USB OTG cable
* Power the RPI-DD using a micro-USB cable and a phone charger or any other suitable source.
* Wait for the device to boot
* Setup the WIFI 
    * Press the "windows" key to activate the start menu and start "Terminal" (under accessories) 
    * Run `sudo raspi-config` to open the configuration utility
    * Go to `System Options` -> `Wireless LAN`
    * Enter SSID & WIFI Password
    * RPI-DD will try to connect to the WIFI network
    * Use "tab" key to navigate to "<Finish>"

### Network access

From a PC on the same network, open file explorer and navigate to `\\rpi-dd1` use the provided credentials to connect.

* `dd-config` share contains the configuration file for the "MagicMirror"
* `dd-gallery\live` share contains the images that will be displayed on the monitor
* `dd-gallery` can be used as temp storage to move images that are not used at the moment