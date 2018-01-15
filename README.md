toggle-grayscale
================

A simple script to toggle the OSX system pref to set the display to grayscale/color.

If you've been following the [latest trend](https://www.nytimes.com/2018/01/12/technology/grayscale-phone.html) to set your phone to grayscale to [attempt to make it less addictive](https://www.theglobeandmail.com/technology/your-smartphone-is-making-you-stupid/article37511900/), you may have noticed that although OSX has the ability to set the display to grayscale as well, there isn't an easy way to toggle back and forth. That's what this little script solves.

Installation instructions:
------------------------

* Download the [latest release .zip](https://github.com/vthunder/toggle-grayscale/releases) file and unzip
* Open System Preferences > Security & Privacy > Privacy tab
* Unlock (bottom-left icon) if necessary, and add the unzipped file to the list

That's it—you can now double-click the script to toggle into/out of grayscale mode.

Notes & Tips:
-------------

The app is a simple script created with the "Script Editor" app. You can easily open the .scpt file in this repository if you want to read it/make any changes, open the File menu and select Export to make a new app bundle.

You can place the script on your desktop, which works well if you also set a Hot Corner to show the desktop: Open System Preferences > Mission Control > Hot Corners... (bottom-left button). I use lower-right to show the desktop.

If you have a launcher app like [Alfred](https://www.alfredapp.com/), you can also copy and paste the AppleScript directly into a workflow action and quickly run it via the keyboard.

Let me know how it works out for you, or if you have any trouble using it! Pull requests for improvements are most welcome.
