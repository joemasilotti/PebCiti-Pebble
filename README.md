# PebCiti for Pebble

PebCiti is a simple Pebble app to show the nearest available bike hire dock or bike on your watch (works both in NYC and London).

# Installation

PebCiti now requires Pebble SDK 3.0 to build.

1. `brew install pebble/pebble-sdk/pebble-sdk`

If you are working in OS X, you can also use Xcode as your IDE.

2. `gem install bundler`
3. `bundle`
4. `open PebCiti.xcodeproj`

## Credit

PebCiti is composed of two parts — the Pebble app was created by [Joe Masilotti](http://masilotti.com/) and the javascript code (which runs in the official Pebble app) has been developed by [Tomas Vitek](http://tomasvitek.com/).

## What does it do?

The app will show you the nearest available bike for hire or the nearest available docking space.

Since it does not require a special companion app, it runs both on iOS and Android, all you need is the official Pebble app paired with a Pebble.

## PebCiti ❤️ New York City & London 

PebCiti works with **CitiBike** in NYC and with **Barclays Cycle Hire** in London. If you want to add more cities, add an issue on Github or submit a pull request.

## Download

You can download the latest build of PebCiti from [/build/PebCiti](https://raw.github.com/tomasvitek/PebBike/pebciti/build/PebCiti.pbw).

## Screenshots

<img src="https://raw.github.com/tomasvitek/PebBike/pebciti/screenshots/iOS.png" style="width:403px;height:706px">
<img src="https://raw.githubusercontent.com/tomasvitek/PebBike/pebciti/screenshots/Pebble.png" style="width:181px;height:290px">
