# DMI LightBox

<img src="images/Cube_BlueGreen.jpg" height=300><img src="images/Bela_PerfBoard.jpg" height=300>

## Contents
- [Preface](#preface)
- [Introduction](#introduction)
- [Code](#code)
- [Components List](#components-list)
    - [Electronics](#electronics)
    - [Housing](#housing)
- [Videos](#videos)

## Preface
This repo documents the progression of my final year project from my time studying Music Technology (BMus) at the University of Edinburgh (2017-2021). You can read the original dissertation from this project [here](Dissertation.pdf) and watch the presentation [here](https://youtu.be/LdHWVvEBqIA).

While the initial commit includes information, photos, and files as they were submitted as part of the original project submission (May 2021), subsequent commits will include work carried out to improve, upgrade, fix, or otherwise change the device.

The purpose of this repo is to demonstrate the development and evolution of my project beyond its initial submission. This repository also aims to illustrate how the progression of a project is inherently linked to the development of one's own skills and experience over time.

## Introduction
The aim for this project was to create an expressive and educational digital musical interface. Using research into other expressive digital instruments, a  device was created that combined the use of audio, visual and haptic elements to provide the user with an expressive musical instrument enabled with additional non-sonic feedback. As the project progressed, there were changes made to the initially proposed hardware and software, which changed the scope if the device. The resulting device is an adaptable digital musical instrument that can be programmed to behave in a variety of ways.

The device can be programmed to behave in one of three ways:

- "Drum" mode.
- "Bow" mode.
- "Strum" mode.

## Code
The initial iteration of this device was programmed using patches made in PureData. Unfortunately, the patches for the Bow and Drum mode have been lost, however, you can find the Strum mode patch [here](src/StrumMode.pd).

## Components List
### Electronics
- 1x [Bela Starter Kit](https://shop.bela.io/collections/bela-and-bela-mini/products/bela-starter-kit).
- 1x [3W Speaker](https://shop.pimoroni.com/products/mini-speaker-4-3w?variant=2976551927818).
- 4x [Trill Square](https://uk.shop.bela.io/collections/trill/products/trill-square) - Capacitive XY touch pad.
- 4x [Linear Resonant Actuator](https://catalogue.precisionmicrodrives.com/product/c10-100-10mm-linear-resonant-actuator-4mm-type) - vibration motor.
- 4x [Adafruit DRV2605L](https://learn.adafruit.com/adafruit-drv2605-haptic-controller-breakout/overview) - LRA driver.
- 1x [Adafruit I2C Multiplexer](https://learn.adafruit.com/adafruit-tca9548a-1-to-8-i2c-multiplexer-breakout/overview) - I2C multiplexer.
- 9x DIP LED - Red.
- 9x DIP LED - Green.
- 9x DIP LED - Blue.
- 9x DIP LED - Yellow.
- 27x Resistor - 220Ω.

### Housing
- 3mm Acrylic Sheet - Opaque White.
- PLA 3D Printer Filament.
- Perf board.
- M2 Screws.

## Construction
### Frame
The frame for the device was 3D printed using PLA filament. You can find the .stl files [here](STLs/).

<img src="images/Frame.jpg" height=300>

### Panels
Four panels housing the Trill sensors, LEDs, and LRAs were mounted on each side of the frame. 

<img src="images/Panels_Outer.jpg" height=300><img src="images/Panels_Inner.jpg" height=300>

A fifth panel that holds the speaker was mounted on top of the device.

<img src="images/Panels_Top.jpg" height=300>

### Circuit
The circuit was created on a piece of perforated board.

<img src="images/Bela_PerfBoard.jpg" height=300>

## Videos
- [Full Presentation](https://youtu.be/LdHWVvEBqIA).
- ["Drum" Example](https://youtu.be/Nnmb8wrtWPo)
- ["Bowed" Example](https://youtu.be/kS6pSZya3a8)
- ["Strummed" Example](https://youtu.be/ceU9Kx6uD7M)