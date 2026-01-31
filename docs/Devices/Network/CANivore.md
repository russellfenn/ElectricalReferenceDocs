---
icon: lucide/network
---
# CANivore CAN FD Bus Expansion

CANivore provides a CAN FD network, which is faster than the CAN 2.0 provided by [roboRIO 2.0](../CPUs/RoboRIO.md)

![CANivore CAN FD](https://store.ctr-electronics.com/cdn/shop/files/CANivore_robotics-USB-to-CAN-FD-hub-robot-automation-robotics-device-top.png){ align=right width=128}

## LED Status

Note: Our 3D Printed enclosure for the CANivore, Pigeon and roboRIO covers the BT (Bluetooth) and WiFi status LEDs.

### Normal Operation

| LED Name | Color / State                                        | Description           |
| -------- | ---------------------------------------------------- | --------------------- |
| Stat     | <span style="color:green">Green</span> Fast Strobe   | Good USB, CAN Enabled |
| CAN      | <span style="color:green">Green</span>               | CAN FD active         |

### Error States

| LED Name | Color / State                                        | Description             |
| -------- | ---------------------------------------------------- | ----------------------- |
| CAN      | <span style="color:red">Red</span> double blink      | Voltage too low for CAN |
| CAN      | Solid <span style="color:red">Red</span>             | No CAN communication    |

## Elecrical Specs

## Reference Docs

- :lucide-book-open-text: [User's Guide](https://ctre.download/files/user-manual/CANivore%20User's%20Guide.pdf)
- :lucide-shopping-cart: [Product Page](https://store.ctr-electronics.com/products/canivore)