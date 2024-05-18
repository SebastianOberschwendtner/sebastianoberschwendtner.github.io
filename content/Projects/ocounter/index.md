---
title: oCounter
draft: false
summary: A frequency counter which uses the 74-series logic.
featured_image: img/ocounter_banner.jpg
omit_header_text: true
keywords: "74 logic, frequency counter, etched pcb,"
---

## Overview

---

<table class="left w-100">
    <tr>
        <td class="pr0 tl"><i class="da fa-microchip"></i></td>
        <td><b>Processor:</b></td>
        <td class="tr">74-Series Logic</td>
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
            <i class="fa fa-times dark-red"></i>
                Not Available
        </td>
    </tr>
    <tr>
        <td class="pr0 tl"><i class="da fa-flag-o"></i></td>
        <td><b>Languages:</b></td>
        <td class="tr"><i>-</i></td>
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
        -
        </td>
    </tr>
</table>

---

## Description
{{< figure src="img/ocounter2.jpg" class="fl mt1 ml0 mb0" width=300 >}}

This project is a frequency counter.
It is based completely on analog hardware and 74-series logic ICs.
The counter counts how many signal transitions happen in the input signal over a predefined time window.
This gate time sets the precision and frequency range of the counter.
Several gate times are available, resulting in a frequency resolution from *10 mHz* to *10 Hz*.
The counting accuracy of all frequency ranges is based on the internal *10 MHz* reference clock.
An external reference can be used as well.
The display of the measured frequency is done via 7-segment displays, which are driven with 74-Series logic.
The PCB is edged by myself.
It is my first PCB where I applied an additional solder mask.