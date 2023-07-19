P1 and Water meter reader:
====================

This script uses ESPHome to configure an ESP32-POE-ISO dongle from Olimex to read the P1 port of a smart meter and uses an inductive sensor to measure the water usage.

It is used with the Kaifa MA105C smart meter, which does not expose some of the interesting measurement values (e.g. voltage level).

Installation:
-------------

The ESPHome tool can be used to upload this script to the ESP32 device by running:

```
esphome run p1-water-reader.yaml
```

