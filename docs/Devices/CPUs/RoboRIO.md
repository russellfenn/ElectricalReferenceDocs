---
icon: lucide/cpu
---
# roboRIO 2.0

## LED States

### Normal Operations

| LED Name | Color / State | Description  |
| -------- | ------------- | -------------|
| Power    | <span style="color:green">Green</span> Solid   | Normal, no faults. |
| Status   | Off           | Normal Operation |
|          | Flash 3x      | Safe Mode        |

:lucide-power: The roboRIO 2.0 performs a power-on self test (POST). During the POST, the Power and Status LEDs turn on. When the Status LED turns off, the POST is complete.

### Error States

| LED Name | Color / State | Description  |
| -------- | ------------- | -------------|
| Power    | Off           | No power, or power outside normal range. |
|          | <span style="color:red">Red</span> Solid     | Brownout  |
| Staus    | Flash 2x      | Software Error. Reinstall software.      |
|          | Flash 4x      | Crashed 2x, usually means out of memory. |

## Electrical Specs

:lucide-triangle-alert: roboRIO must be on a dedicated circuit with a 10A fuse.

### CAN

We prefer to use the [CANivore](../Network/CANivore.md) CAN FD interface over the roboRIO 2.0 CAN.

- roboRIO 2.0 uses the older and slower CAN 2.0 Bus spec.
- :lucide-pencil: The roboRIO 2.0 contains an internal 120 Ω termination resistor between L (GRN) and H (YEL).

## Reference Docs

- :lucide-book-open-text: [User's Guide](https://www.ni.com/docs/en-US/bundle/roborio-20-umanual/page/user-manual-welcome.html)
- :lucide-siren: [LED Indications](https://www.ni.com/docs/en-US/bundle/roborio-20-umanual/page/ledindications.html)
- :lucide-shopping-cart: _The roboRIO 2.0 is no longer available._
