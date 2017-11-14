= MIDI Stomper O'Doom User Manual

Congratulations on purchasing your MIDI Stomper of Doom. You can now keep your hands on your instrument while controlling your computer. The MIDI Stomper of Doom is a MIDI controller small enough to fit on a guitarist pedalboard, or tough enough to be thrown into a backpack.

== Plugging it in

Use a micro USB cable to attach the controller to your computer with the "hooks down". You can use a USB extension cable if your computer is sitting up high. The maximum length of cable cannot exceed 16 feet (without special cables). The controller is bus powered, so there are no batteries to die or corrode.

Be careful not to torque the USB jack in any manner, you could break it. Unplug it when not in use or it's being transported.

== Using it

Press the buttons. Stomp lightly if you like, just not too hard.

== Default notes

By default, the controller plays C3, C#3, and D3 from left to right via MIDI channel 10.

== Reprogramming the controller

First, you will need to have a piece of software that can send MIDI notes to a MIDI port. Nearly every DAW or software synth has this capability. If you don't have a piece of software that can do this, one option is the free "MIDI Tools" application from https://mountainutilities.eu/miditools (no affiliation).

Connect your controller and setup your software so it will send MIDI output to _O'DooM Fx - MIDI Stomper o'doom_.

Next, hold down all buttons on your controller for at least 2 seconds. The controller will initially play the notes, but after 2 seconds will stop them from playing.

The controller is now waiting for you to send MIDI notes to it. The controller will wait up to 30s for notes to arrive. You must send at least as many notes as there are buttons.

After the controller receives enough notes, it will play them back. The controller will remember both the pitch and the channel of each note.

The controller will remember these notes even if the controller is unplugged from USB.

== Reseting to defaults

You can reset the controller to send the default pitches. To do this, unplug the controller from the computer. Next, hold down all buttons while simultaneously plugging the controller back in. Lift up on the buttons. The controller is now reset to its default settings.

== Problems

Well shoot, sorry you're having issues! Open a bug on https://www.github.com/odoom/midi-stomper and describe
* What's happening
* What is supposed to happen
* Steps to reproduce

The source code is also available under the terms in that repository.

== Warranty
The device is will be warranted against physical and software defects for a period of one year from the original purchase date. This does not cover user damage or abuse. This warranty is void if other firmware is flashed to the device. This warranty is transferable if the controller device is sold. If accepted, shipping is paid for one-way. Contact Jonathan via GitHub if you ever need to initiate a warranty claim.

== Rocking out

You must rock out hard while using the controller for optimal awesomeness. Good luck, thank you, and God bless.

cheers,
 -Jonathan

== Info
© 2017 Jonathan S. Fisher - All Rights Reserved
* https://odoom.engineering
* https://www.github.com/odoom/midi-stomper
