# IsadoraPatches

In this repository you will find a number of handy Isadora Patches used as reference or teaching material.

## material

In this folder you will find the material used in the Isadora Patches


## General Notes

If any of the Isadora patches opens with a dialog windod saying it could not find this and thsi media file just click "Skip All Files" and add your own sound/image/video media to use.


## makey_makey.izz

A demo Isadora file for the use of a MakeyMakey (https://makeymakey.com/) board. For Isadora an MakeyMakey is basically a keyboard and/or mouse so KeyboardWatchers play a central role in this file. With the Makey-Makey however it is important to use a bit of logic sometimes. For example if with a switch a key is kept pressed how do you handel the stream of incoming pulses? This file is here to help you with that.


## bareConductiveDemo.izz

A demo Isadora file for the use of the braeConductive board (https://www.bareconductive.com/ ).
In the second scen there are some examples that work with the bare conductive.
See also [this](https://github.com/hku-ect/BareConductive) repo for more information.


## LeapPlay.izz

A demo Isadora file for the use with the leapmotion (https://www.ultraleap.com/product/leap-motion-controller/). Fortunbaltely Isadora has it's own leap motion watcher, the file just show some examples of how to possible use it.

## LivePainting.izz

A demo Isadora file showing several possibilities of using the Live Drawing actor. See also for a tuorial here: https://support.troikatronix.com/support/solutions/articles/13000050887-how-to-use-the-live-drawing-actor-the-basics


## MPD2_Kinect.izz

A demo Isadora file shwocasing how to use the kinec tin Isadora. In order to use this file you need acces to a Kinect and you have to download the Openni tracker (https://troikatronix.com/plugin/openni-tracker/) see also the tutorial file: https://troikatronix.com/plugin/openni-tracker-tutorial/ and mor einformation here: https://support.troikatronix.com/support/solutions/articles/13000069937-skeleton-tracking-in-isadora-3-with-openni-tracker


## MOCAP_basis.izz

This Isadora file can be used as an example or starter file when playing around with a mocap system. This patch will assume you will recieve the MOCAP dat through OSC via de NATNET2OSCbridge (https://github.com/hku-ect/NatNet2OSCbridge). The core of this patch is the RadousCheck user actor which gives you informaton about if two points are near each other or not.


## MPD2_makeylivecam.izz

This Isdaora file was made of a demonstration of how you can make a simple installation where a video recording is triggerd by a keyboard press through a makeymakey (https://makeymakey.com/) board. The patch wil then fillm for three seconds and play all the recorded movies one after eachother.

## ENTTEC-DMX-USB_lightcontrol.izz

With this Isadora file you can control DMX lighting directly using an ENTECC DMX USB PRO.

## controlDMXLights_QLC.izz

With this Isadora file you can control DMX lighting in a decentralized way where there is one central computer wiht a USB-DMx interface running QLC+ (https://www.qlcplus.org/index.html) which listens to other computer via OSC.


## ControlPanelDemo.izz

Ths file show a very simple demo of the possibilitues of the in built control panel that Isadora features.

## IsadoraNetwork.izz & IsadoraNetworkListener.izz & OSCrecieve

These two Isadora patches and the Processing sketch show a very bare bones demo of the possibility so send data from one computer to another or between two Isadora patches or Isadora and Processing using OSC (https://en.wikipedia.org/wiki/Open_Sound_Control) or NDI (https://en.wikipedia.org/wiki/Network_Device_Interface)

## MidiDemo.izz

This is a demo how you can use Midi (https://blog.landr.com/what-is-midi/) Devices in Isadora the demo is built to use with a Akai LPD8 but cna be altered to use any midi device.


