---
icon: lucide/compass
---
# Pigeon IMU

![Pigeon 2.0 IMU](https://store.ctr-electronics.com/cdn/shop/files/Pigeon-2.0-CTRE-easy-IMU-robot_tech.png){ width=128 align=right}

The Pigeon 2.0 is an inertial measurement unit (IMU) that can sense acceleration, angular velocity, and magnetic fields

## LED Status

### Normal Operation

| LED Color | Blink Pattern | Description |
| --------- | ------------- | ----------- |
| <span style="color:green">Green</span> | Blink | CAN bus detected. Robot is enabled. |
| <span style="color:yellow">Yellow</span> | Simultaneous Blinking | CAN bus detected. Robot is disabled. |

### Error States

| LED Color | Blink Pattern | Description |
| --------- | ------------- | ----------- |
| <span style="color:red">Red</span> | Blink | Check CAN Bus health and connection to the Pigeon 2.0 |
| <span style="color:yellow">Yellow</span> | Alternate Blinking | CAN bus detected. Robot controller is not present on CAN bus, or Pigeon2 software object not created in user application. |

| <span style="color:red">Red</span> | Error | Error |

## Electrical Specs

## Reference Docs

- :lucide-book-open-text: [User's Guide](https://ctre.download/files/user-manual/Pigeon2%20User's%20Guide.pdf)
- :lucide-shopping-cart: [Product Page](https://store.ctr-electronics.com/products/pigeon-2)

![Pigeon 2.0](Pigeon-2.0-CTRE-IMU.webp)