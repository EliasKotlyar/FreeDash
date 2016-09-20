# FreeDash
Reprogramming Amazon Dash V2 (JK29LP)

## Usage

---not usable in the moment, for information only---

## Contribution

Any contribution to the development is highly welcome. The best possibility to provide any change is to open a pull request on GitHub.


## Hardware infos of Amazon Dash V2
Main Processor:
[Atmel SAMG55](http://www.atmel.com/Images/Atmel-11289-32-bit-Cortex-M4-Microcontroller-SAM-G55_Summary-Datasheet.pdf)

Wifi:
[ Atmel ATWINC1500B ](http://www.atmel.com/Images/Atmel-42487-ATWINC1500B-MU_Datasheet.pdf)

Bluetooth:
[Cypress CYBL10563-68FNXI  ](http://download.opendatasheets.com/pdfs/2014/11/11/22/53/36/106/cyp_/manual/procble.pdf)

SPI Flash:
[Micron N25Q032 ](https://www.micron.com/~/media/documents/products/data-sheet/nor-flash/serial-nor/n25q/n25q_32mb_3v_65nm.pdf)

Headers:[AXE510127 ](http://www.mouser.com/ds/2/316/con_eng_a4s-974509.pdf)


## Testpoints on Board:

TX18 – SWDIO

TX19 – SWCLK

TX21 – 3.3V

TX20 – RESET

TX22 – GND

TX16 – UART TX

TX15 – UART RX

## Hardware required for debugging:
- JTAG Debugger -  Segger J-Link
- AXE510127/AXE610124 Headers
- Wires
- Debug Adapter[[Version aihei61r]](https://oshpark.com/shared_projects/aihei61r)
[[Version nqbit]](https://github.com/nqbit/kicad-boards/tree/master/dash_connector)






## List of sources:
[Amazon Dash Teardown](https://mpetroff.net/2015/05/amazon-dash-button-teardown)

[New Amazon Dash Teardown](https://mpetroff.net/2016/07/new-amazon-dash-button-teardown-jk29lp/)

[Amazon Dash: Does anyone hacked it?](https://community.particle.io/t/amazon-dash-anyone-hacked-it/14303/26)

[ReDash](https://github.com/gtalusan/redash)

[Amazon Dash Version 2](http://key-basher.blogspot.de/2016/09/amazon-dash-button-version-2.html)