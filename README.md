# led-controller-ethernet

led-controller-ethernet is the hardware to the [avr-ethernet-licht firmware](https://github.com/marenz2569/avr-ethernet-licht).

Its purpurse is to control ws2812 protocol compatible leds via a [udp protocol](https://chch.it/Fensterbogenbeleuchtung).

In addition to the pcb the hardware uses an arduino pro mini and an enc28j60 breakout board.

## flexibilty

- V\_in ranging from 12 to 36 Volts or 5 Volts (bridge JP1 and JP2, note that switch mode regulator must not be populated).
- V\_out switchable between 5 Volts (bridge JP2) and V\_in (bridge JP1).

## todo
- test if regulator may be populated when inserting 5 Volts to V\_in and bridging JP1 and JP2
- add option for rgb leds with 3 mosfets.

## license
see lgplv2.1 in LICENSE file.
