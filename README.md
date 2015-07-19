# Touchegg Mac-like Configuration File for Elementary OS Freya

This repository contains a Touchegg config file for Elementary OS Freya which tries to emulate the same gestures as in OS X.

The config file contains gestures for:
  - *Exposing all windows*: 3-finger swipe down
  - *Show all workspaces*: 3-finger swipe up
  - *Switching workspaces*: 3-finger swipe (left or right)
  - *Maximizing / Minimizing window*: 4-finger swipe (up or down)
  - *Tiling windows left or right*: 4-finger swipe (left or right)
  - There is also support for OS X-like "natural scrolling" and basic pinch-to-zoom.

## Installing Touchegg
1. Download the touchégg [source code](https://code.google.com/p/touchegg/downloads/detail?name=touchegg-1.1.1.tar.gz&can=2&q=) and unpack it;
2. Download and install dependencies with this handy command: `` sudo apt-get build-dep touchegg ``. This will pull and install necessary dependencies.
3. ``cd`` to the source directory and run these commands:

``$ qmake``

``$ make``

``$ sudo make install``

## Using the configuration file

Once you have touchegg installed, installing this configuration is easy.

1. Download the ``touchegg.conf`` file and save it under ``~/.config/touchegg/touchegg.conf`` (If the directory doesn't exist, create it.)
2. Run the command ``$ touchegg`` and try the gestures.
3. If you want it to run on startup simply add touchegg to your startup applications list.
