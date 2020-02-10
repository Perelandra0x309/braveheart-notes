# braveheart-notes

These are some notes as I test the [PinePhone](https://wiki.pine64.org/index.php/PinePhone) BraveHeart edition.  Updates will be amde as I am able to test these systems.

## KDE Neon
- Installation

Download [latest image](https://images.plasma-mobile.org/pinephone/)
Write image to SD card using Etcher

- Notes

Lock PIN is 1234
 
- Good

Nice looking UI, better than other Plasma implimentations
Can install apps
Has a dark mode for Plasma
Wifi connects (until phone locks, see below)
Scrolling in web browser is fairly smooth

- Bad

The wireless chip goes to sleep when the phone locks.  I have not figured out how to wake it up again.

## Plasma Manjaro
- Installation

Download [latest image](https://osdn.net/projects/manjaro-arm/storage/pinephone/plasma-mobile/alpha3/)
Write image to SD card with Etcher

- Good

WiFi connectes
Web browser works

- Bad

Scrolling in browser is jerky
Can't install apps yet?

## PostmarketOS Phosh
- Installation

Download [latest image](http://images.postmarketos.org/pinephone/)
Write to SD card with Etcher

> Note trying to build from source on Manjaro failed for me, I got errors about missing kernel modules.

- Good

Very nice UI

- Bad

Can't connect to wifi, selecting the wireless network does not bring up any dialog to enter a password

## PostarketOS Plasma
- Installation

Download [latest image](http://images.postmarketos.org/pinephone/)
Write to SD card with Etcher

- Good

Wifi connects

- Bad

Can't install any apps yet?
Web browser only shows a white screen

## Sailfish
- Installation

Follow [these instructions](https://wiki.pine64.org/index.php/PinePhone_Software_Release#SailfishOS) to use the flashing script.

- Notes

When first booting up the screen may look black but it is actually just very very dim.  The OS is using automatic brightness adjustment but it causes the screen to be too dark in normal light.  You will need to shine a flashlight into the sensor near the top of the screen for the brightness to increase enough to see the screen.  Once you have booted into the OS adjest the Display settings to turn off atumoatic screen adjustment.

- Good

UI looks great
Has an app store, but selection is limited

- Bad

Browser doesn't work
Are apps being updated?  The ones fro mJolla look like they were last updated in 2017.

## Debian Phosh
- Installation

Download the [image file](https://people.collabora.com/~aferraris/pinephone/debian-pinephone.img.gz)
Write it to SD card with Etcher

- Good

WiFi connects

- Bad

Web browser only shows a white screen
