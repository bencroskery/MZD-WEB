# MZD-WEB

## What is this?
This repo contains modifications to Mazda Connect JCI files to be able to view and test the interface from a desktop web browser.

**Opera 12.1x is required to access complete functionality**, other browsers can preview the main menu and highlight 1 of the 5 options (alright for previewing a simple theme).

> Note: You should have made tweaks to your car using something like [MZD-AIO-TI (Tweaks Installer)](https://mazdatweaks.com/) before getting into this, you will at least need to have gotten a copy of your JCI files unless you have procured them from elsewhere.

## How do I use it?

### 1. Get a JCI-Backup
You must first have a JCI backup from your car to apply these files on top of, if you've ever installed tweaks before hopefully you've got this already.

Use MZD-AIO-TI and compile a tweak with the "Backup JCI Folder" option. Apply the tweak with a USB stick, then plug the stick back into your computer and copy the *JCI-Backup* folder somewhere safe (not a bad idea to keep a couple copies of this around just in case).

### 2. Replace Files and Open It Up!
Take a clean copy of the *JCI-Backup/jci* folder, and paste the *jci* folder from the repository on top of it.

Now with your modified JCI in hand, open the *jci/gui/index.html* folder in your browser. The interface should appear and allow you to interact with it using your mouse (click and scroll wheel) and keyboard (arrow keys and enter).

### 3. Add Tweaks and Test
Now you can make tweaks to the png/css/js files and test them with the interface to make sure they function correctly.

There are a couple themes built into MZD-AIO-TI you can test out, any themes I've put together can be [found here](https://github.com/bencroskery/MZD-THEMES) and used as a resource to create your own!

## How do I apply the tweaks to my car?
I don't know of an especially straight forward way using MZD-AIO-TI to apply jci modifications to your car, but here's what I do :)

1. Build a hierarchy of just the modified files starting from the root *jci* folder (since we only want to replace the files we have to)
1. Apply the mod to a clean *jci* folder to check everything works as expected
1. In MZD-AIO-TI:
   1. Use the "Custom Infotainment Colors" option
   1. Choose "Custom Theme"
   1. Pick your *jci* folder mod
   1. Compile the tweak
1. Paste your *jci* folder mod on top of the *_copy_to_usb/config/color-schemes/theme/jci* created by MZD-AIO-TI to copy remaining files which the tweak installer did not add (ex. css files)
1. Put the contents of the *_copy_to_usb* folder onto your USB stick and go install the tweak as your normally would.