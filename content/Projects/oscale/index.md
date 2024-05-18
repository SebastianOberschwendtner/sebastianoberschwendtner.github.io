---
title: oScale
draft: false
summary: A weighing scale with built-in timer for brewing perfect espresso.
featured_image: img/oscale_banner.jpg
omit_header_text: true
keywords: "weighing scale, espresso, timer, avr, atmel, atmega,"
---

![oScale Logo Header](img/oscale_header.png)

## Overview

---

<table class="left w-100">
    <tr>
        <td class="pr0 tl"><i class="da fa-microchip"></i></td>
        <td><b>Controller:</b></td>
        <td class="tr">Atmel ATmega328P</td>
    </tr>
    <tr>
        <td class="pr0 tl"><i class="da fa-map-o"></i></td>
        <td><b>Schematics:</b></td>
        <td class="tr">
            <i class="fa fa-check green"></i>
            Available
            <a href="https://github.com/SebastianOberschwendtner/OTP22_oScale/blob/main/02_Schematic/OTP-22_oScale_Schematics_REVA.PDF" target="_blank">
                here
                <i class="fa fa-external-link"></i>
            </a>
        </td>
    </tr>
    <tr>
        <td class="pr0 tl"><i class="da fa-code"></i></td>
        <td><b>Firmware:</b></td>
        <td class="tr">
            <i class="fa fa-check green"></i>
                Available
            <a href="https://github.com/SebastianOberschwendtner/OTP22_oScale/tree/main/01_Code" target="_blank">
                here
                <i class="fa fa-external-link"></i>
            </a>
        </td>
    </tr>
    <tr>
        <td class="pr0 tl"><i class="da fa-flag-o"></i></td>
        <td><b>Languages:</b></td>
        <td class="tr"><i>C++, Python</i></td>
    </tr>
    <tr>
        <td class="pr0 tl"><i class="da fa-key"></i></td>
        <td><b>License:</b></td>
        <td class="tr"><i>GPL v3</i></td>
    </tr>
    <tr>
        <td class="pr0 tl"><i class="da fa-github"></i></td>
        <td><b>Repository:</b></td>
        <td class="tr">
        <a href="https://www.github.com/SebastianOberschwendtner/otp22_oscale" target="_blank">OTP22 oScale <i class="fa fa-external-link"></i></a>
        </td>
    </tr>
</table>

---

![tag](https://img.shields.io/github/v/tag/SebastianOberschwendtner/OTP22_oScale?color=green)
![release](https://img.shields.io/github/v/release/SebastianOberschwendtner/OTP22_oScale?color=green)
![issues](https://img.shields.io/github/issues-raw/SebastianOberschwendtner/OTP22_oScale)
![bugs](https://img.shields.io/github/issues/SebastianOberschwendtner/OTP22_oScale/bug?color=red)
![status](https://img.shields.io/badge/status-Developing-yellowgreen)

>The **schematic** and **PCB** are designed with *CircuitMaker*. The project can be found [here <i class="fa fa-external-link"></i>](https://circuitmaker.com/Projects/Details/SebastianOberschwendtner/OTP-22oScale).

## Description
{{< figure src="img/oscale.jpg" class="fl mt1 ml0 mb0" width=300 >}}

The *oScale* is a weighing scale with an integrated kitchen timer.
It is intended for brewing espresso, where the weight of the coffee grounds and the brewing time are crucial for a perfect espresso.
The weight is measured by a sensitive load cell with a maximum capacity of *500 g*.
The voltage of the load cell is amplified by an analog circuit before it is digitized by an external ADC with a resolution of *12 bit*.
The digitized signal is then filtered and processed by the ATmega328P microcontroller.
The large LCD display shows the weight in *0.1 g* increments and the current brew time.
The timer has to be started manually by pressing a button.
The case and weighing platform are designed to fit underneath an espresso machine, which has a limited distance between the drip tray and the portafilter.