# Xcode Plugin Template
(This origin project is deprecated in favor of [Editor Extensions](https://developer.apple.com/videos/play/wwdc2016/414/) support in Xcode 8+.)

This fork add supports for **Xcode8, Xcode9**, and future versions.

## Installation

- Install using [Alcatraz](http://alcatraz.io/)

## Usage

The default plugin file links against `AppKit` and `Foundation`, and, when built (and Xcode is restarted), creates a menu item labeled "Do Action" in the Edit menu. Pressing the menu item should open an alert. Customize at will!

**Note:** Compiling the template with Swift requires Xcode 6.1 or greater.


## Notes

- Add the build UUIDs for the versions of Xcode you wish to support to `DVTPlugInCompatibilityUUIDs` in `Info.plist`. This can be found by running:

  <pre>defaults read /Applications/Xcode.app/Contents/Info DVTPlugInCompatibilityUUID</pre>
