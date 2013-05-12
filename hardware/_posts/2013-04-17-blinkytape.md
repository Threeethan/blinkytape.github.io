---
layout: project
permalink: /blinkytape/index.html 
category: hardware
type: "Interactive Lighting Controller" 
img: blinkytape
title: Blinkytape
technologies: [C++, C, Processing, Python] 
when: 8/2012 - 10/2012
collaborators:
task: 
desc:
images:
sourcecode: [
	[BlinkyTape, https://github.com/blinkiverse/blinkyboard]	
]
context: 
---

We've had a lot of fun [working](/domestar) with [LEDs](/daftpunk), but we've often been frustrated by how difficult they can be to program, power, mount, and enclose.

That's why we invented the BlinkyTape!

![Meet BlinkyTape](/images/{{page.img}}/big/bt.jpg)

BlinkyTape is a one meter long, full-color light tape with 60 independent RGB LEDs controlled by our custom light processor. Power and communications are provided by a built-in micro-USB connector. An on-board button allows for simple interactions such as choosing between effects.

BlinkyTape is flexible, so you can easily integrate it into any shape your project needs. BlinkyTape also comes enclosed in weatherproof silicone, so it's suitable for outdoor use!

# Portable Power

![Portable Power](/images/{{page.img}}/big/power.png)

Patterns can be stored directly on the BlinkyTape, so there's no need for a dedicated computer. Taking designs on the go is as simple as plugging the BlinkyTape into a USB battery pack!

# Software

The BinkyTape comes with bright, colorful built-in patterns, but of course you will want to make your own!

## Pattern Editor

![Pattern Editor](/images/{{page.img}}/big/pattern.png)

The BlinkyTape comes with a rich set of companion software that run cross-platform on Mac OS X, Windows, and Linux. Creating custom animations is as easy as plugging the BlinkyTape into your computer and starting our pattern editor. Patterns can be edited in real-time, or saved to the strip for playback away from the computer.

## Music Reactive Mode

Need some sweet lighting for your next party? No problem, hook a couple of BlinkyTapes up to your USB port, fire up the beat analyzer, and you'll have flashing colors and bright lights in no time.

## Hacking

![Processing](/images/{{page.img}}/big/processing.png)

Our favorite thing about the BlinkyTape is how easy it is to program to meet your own needs.

The BlinkyTape understands a simple serial protocol over USB, and we have plenty of example code for controlling the BlinkyTape using free programming environments such as Processing and Python.

![Arduino](/images/{{page.img}}/big/arduino.png)

Of course, it's possible to go even lower level. The BlinkyTape uses the same ATMEGA32u4 processor that you will find in the Arduino Leonardo, and can be programmed using the same easy-to-learn Arduino programming environment. We provide plenty of examples to get your project started!

# We &lt;3 Open Source Hardware

![We &lt; Open Source](/images/{{page.img}}/big/opensource.jpg)

We strongly believe in open source, and the BlinkyTape is no exception. All of the design files, PCB layouts, and source code are available now on Github.

Got a cool extension or some neat patterns? Please share them! Operators are standing by to review your pull requests.

# Speed Projects

Every one of the projects in our Kickstarter video is what we like to call a Speed Project.  Speed Projects are typically done in one sitting and we think that these really show off how powerful the BlinkyTape can be!

## Blinky Hat - 30 minutes

![Blinky Hat](/images/{{page.img}}/big/hat.png)

The Blinky Hat started its life as a $7 hat found on the streets of Shenzhen, China.  With the help of some double-sided tape, we wrapped a BlinkyTape around the hat brim and plugged it into our computer.

We used the live preview feature of PatternPaint to map out which LEDs were part of the front-left, front-right, and rear parts of the hat.  From there it was a simple matter of making some sweet animations and saving them to the BlinkyTape.  The last step was to simply unplug from the computer and plug into a portable USB charger!

## Movie FX - 1 Hour

![Movie SFX](/images/{{page.img}}/big/sfx.jpg)

Inspired by the computer-screens-projected-on-faces effects in a popular sci-fi film, this project required only a BlinkyTape, some double-sided sticky tape, and a 4-sided box.

With the BlinkyTape attached to the front of the box we loaded up PatternPaint to make some cool looking animations that would light up our victi-, er, actor's face.  After saving the pattern to the BlinkyTape, we just needed to find a dark, quiet place to film!

## DJ Booth - 10 Minutes

![DJ Booth](/images/{{page.img}}/big/dj.jpg)

Armed with 3 BlinkyTapes mounted in our aluminum diffuser tubes, a USB hub for power, and a MacBook Pro for the tunes, this project was a breeze to set up.

Using the awesome SoundFlower from Cycling '74, we looped the laptop's outgoing audio back in to the system input.  This gives a clean audio signal to our DiscoParty app, which runs in Processing and makes use of the built-in beat detection analysis that Processing provides.

Warning: This project is super quick to set up, but we had so much fun tweaking the various visual effects that we spent hours playing with it afterwards.

## Light Painting - 10 Minutes

![Nyan](/images/{{page.img}}/big/nyan.jpg)

This project used a BlinkyTape mounted in an aluminum diffuser tube, a camera with a long exposure setting, and a dark place to shoot pictures.

PatternPaint makes light painting super simple with its image import functionality.  Since the BlinkyTape has 60 RGB LEDs, we can load in almost any image that is 60 pixels tall.  By saving the pattern to the BlinkyTape and powering it with a portable USB charger, we can make ridiculously awesome light paintings anywhere and everywhere (that it is dark enough to do so).

# Tech Specs

The BlinkyTape is a one meter strip of flexible PCB material containing 60 RGB LEDs.  At one end is our custom light processor, the BlinkyBoard.  The BlinkyTape come enclosed in a weatherproof silicone tubing.

## BlinkyBoard Specs

* 8-bit ATMEGA32u4 operating at 16MHz
* 32KB Flash memory
* 2.5KB RAM
* 1KB EEPROM
* Micro USB connector for power and data
* On-board micro switch for interactive applications