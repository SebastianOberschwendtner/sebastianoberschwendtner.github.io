---
title: oTimer
draft: false
summary: A simple countdown timer for the kitchen.
featured_image: img/otimer_banner.jpg
omit_header_text: true
keywords: "kitchen timer, avr, atmel, atmega"
---

## Overview

---

<table class="left w-100">
    <tr>
        <td class="pr0 tl"><i class="da fa-microchip"></i></td>
        <td><b>Controller:</b></td>
        <td class="tr">Atmel ATmega328</td>
    </tr>
    <tr>
        <td class="pr0 tl"><i class="da fa-map-o"></i></td>
        <td><b>Schematics:</b></td>
        <td class="tr">
            <i class="fa fa-times dark-red"></i>
                Hand Wired
        </td>
    </tr>
    <tr>
        <td class="pr0 tl"><i class="da fa-code"></i></td>
        <td><b>Firmware:</b></td>
        <td class="tr">
            <i class="fa fa-check green"></i>
            Available
            <a href="https://github.com/SebastianOberschwendtner/OTP18_oTimer" target="_blank">
                here
                <i class="fa fa-external-link"></i>
            </a>
        </td>
    </tr>
    <tr>
        <td class="pr0 tl"><i class="da fa-flag-o"></i></td>
        <td><b>Languages:</b></td>
        <td class="tr"><i>C</i></td>
    </tr>
    <tr>
        <td class="pr0 tl"><i class="da fa-key"></i></td>
        <td><b>License:</b></td>
        <td class="tr"><i>-</i></td>
    </tr>
    <tr>
        <td class="pr0 tl"><i class="da fa-github"></i></td>
        <td><b>Repository:</b></td>
        <td class="tr">
        <a href="https://github.com/SebastianOberschwendtner/OTP18_oTimer" target="_blank">OTP18 oTimer <i class="fa fa-external-link"></i></a>
        </td>
    </tr>
</table>

---

## Description
{{< figure src="img/otimer2.jpg" class="fl mt1 ml0 mb0" width=300 >}}

Kitchen timer made with parts I had lying around.
It uses three 7-segment displays with a dedicated driver IC.
The microcontroller multiplexes the segments, so that one driver IC is sufficient.
The timer is controlled via a single button, which starts and stops the counting.
Two potentiometer adjust the timer value in seconds and minutes respectively.
A 18650 LiIon battery powers the timer, with an auto power-off circuitry.
The PCB is prototyped using wires on a quick solder PCB.
The housing is 3D printed with a wooden front plate.