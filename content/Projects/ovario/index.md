---
title: JoVario
draft: false
summary: Vario for paragliding with GPS and power bank capability.
featured_image: img/ovario_banner.jpg
omit_header_text: true
keywords: "paragliding, vario, diy, barometer, gps, stm32,"
author: ["Sebastian Oberschwendtner", "Jakob Karpfinger"]
---

![joVario Header](img/ovario_header.png) 

## Overview

---

<table class="left w-100">
    <tr>
        <td class="pr0 tl"><i class="da fa-microchip"></i></td>
        <td><b>Controller:</b></td>
        <td class="tr">STM32F427</td>
    </tr>
    <tr>
        <td class="pr0 tl"><i class="da fa-map-o"></i></td>
        <td><b>Schematics:</b></td>
        <td class="tr">
            <i class="fa fa-times dark-red"></i>
                Not Available
        </td>
    </tr>
    <tr>
        <td class="pr0 tl"><i class="da fa-code"></i></td>
        <td><b>Firmware:</b></td>
        <td class="tr">
            <i class="fa fa-check green"></i>
            Available
            <a href="https://github.com/SebastianOberschwendtner/OTP15_oVario" target="_blank">
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
        <td class="tr"><i>GPL v3</i></td>
    </tr>
    <tr>
        <td class="pr0 tl"><i class="da fa-github"></i></td>
        <td><b>Repository:</b></td>
        <td class="tr">
        <a href="https://github.com/SebastianOberschwendtner/OTP15_oVario" target="_blank">OTP15 joVario <i class="fa fa-external-link"></i></a>
        </td>
    </tr>
</table>

---

![tag](https://img.shields.io/github/v/tag/SebastianOberschwendtner/OTP15_oVario?color=green)
![release](https://img.shields.io/github/v/release/SebastianOberschwendtner/OTP15_oVario?color=green)
![issues](https://img.shields.io/github/issues-raw/SebastianOberschwendtner/OTP15_oVario)
![bugs](https://img.shields.io/github/issues/SebastianOberschwendtner/OTP15_oVario/bug?color=red)
![status](https://img.shields.io/badge/status-Released-lightgray)

## Description
{{< figure src="img/ovario2.jpg" class="fl mt1 ml0 mb0" width=300 >}}

The JoVario is a vario intended for paragliding.
It is based on the STM32F427 and features a barometer, GPS, and a power bank capability.
The large LCD screen gives information about current altitude, climb rate, and GPS position.
It shows a trend graph of the climb rate and has a configurable audio signal for the climb rate.
The GPS track is logged onto a MicroSD card.
The log automatically starts when a valid GPS fix is available.
Early version of the vario were powered using a LiIon 18650 battery.
The current version uses a pouch cell LiPo battery to achieve a more compact design.
The new case design can be found [here <i class="fa fa-external-link"></i>](https://github.com/SebastianOberschwendtner/OTP15_joVario2.0).
The battery can be charged via a Micro USB port.
The vario has a USB-A port to charge external devices like a smartphone.