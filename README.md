# 24-bit Stereo Audio DAC for Raspberry Pi
![Platform](https://img.shields.io/badge/platform-MAX--II-red)
![GitHub](https://img.shields.io/github/license/dilshan/max2-audio-dac)

![MAX-II DAC Module](https://raw.githubusercontent.com/wiki/dilshan/max2-audio-dac/DSCN1155P-720p.JPG)

This is a 24-bit stereo DAC, which is specifically built for Raspberry Pi boards. This R-2R ladder DAC is developing around Intel / Altera *EPM240T100C5N* CPLD.

DAC which described in this repo can directly connect with the I2S interface of Raspberry Pi boards. The recommended supply voltage for this DAC is 5V to 8V.

The *MCP602* opamp of this module is capable to drive headphone directly. An external AF power amplifier must pair with this module to obtain a higher output power.

This repository contains all the files and binaries to build DAC, which including *Intel Quartus* Project files, Raspberry Pi Device Tree Overlays, etc.

This is certified open-source hardware project. All the content of this project are distributed under the terms of the following license:

-   Hardware License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
-   Software License: [MIT](https://github.com/dilshan/max2-audio-dac/blob/master/LICENSE)
-   [Documentation](https://github.com/dilshan/max2-audio-dac/wiki) License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

[![OSHW-LK000006](https://raw.githubusercontent.com/dilshan/max2-audio-dac/master/OSHW_LK000006.png)](https://certification.oshwa.org/lk000006.html)
