# CANivore CAN FD Bus Expansion

CANivore provides a CAN FD network, which is faster than the CAN 2.0 provided by [roboRIO 2.0](../CPUs/RoboRIO.md)

<img src="./Canivore.png" width="300" height="300" alt="CANivore FD">

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
| CAN      | Solid <span style="color:red">Red</span> | Voltage too low for CAN        |
| CAN      | <span style="color:red">Red</span> double-blink | No CAN communication |

## Elecrical Specs

## Reference Docs

- <img src="../../assets/icons/book-open-text.svg" width="18" height="18" alt="User Guide"> [User's Guide](https://ctre.download/files/user-manual/CANivore%20User's%20Guide.pdf)
- <img src="../../assets/icons/shopping-cart.svg" width="18" height="18" alt="Shop"> [Product Page](https://store.ctr-electronics.com/products/canivore)
