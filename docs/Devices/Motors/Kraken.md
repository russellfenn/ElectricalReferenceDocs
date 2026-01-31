---
icon: lucide/disc-3
---
# Kraken X60/X44 Powered by Talon FX

- The Kraken X60 is a high-performance brushless motor used for robot drive.
- The Kraken X44 is a smaller brushless motor used for steering.
- Talon FX is an integrated motor conroller for Kraken.

## LED Status

### Normal Operation

| LED State                                                      | Cause                        |
| -------------------------------------------------------------- | ---------------------------- |
| Blinking Simultaneous <span style="color:orange">Orange</span> | Robot Disabled.              |
| Both Solid <span style="color:orange">Orange</span>            | Enabled with neutral output. |
| Blinking Simultaneous <span style="color:red">Red</span>       | Driving in reverse.          |
| Blinking Simultaneous <span style="color:green">Green</span>   | Driving forward.             |

### Error States

| LED State                                                     | Cause                        |
| ------------------------------------------------------------- | ---------------------------- |
| Blinking Alternating <span style="color:red">Red</span>       | No CAN signal.               |
| Blinking Alternating <span style="color:orange">Orange</span> | Detects CAN but does not see Phoenix running on the robot controller. |
| Offset <span style="color:orange">Orange</span>/Off           | Talon FX in thermal cutoff.  |
| Alternate <span style="color:red">Red</span>/<span style="color:green">Green</span> | Talon FX unlicensed. |
| Alternate <span style="color:red">Red</span>/<span style="color:orange">Orange</span> | Damaged Hardware. |
| Single LED alternates <span style="color:green">Green</span>/<span style="color:orange">Orange</span> |Talon FX in bootloader. |

## Electrical Specs

Use a 40A fuse.

## Wiring

![Talon FX Connectors](./Kraken%20X44%20-%20Wiring%20&%20Modularity.svg){ width="300" }

| Location        | Screw Size   | Driver Size | Torque Value | Wire Size |
| --------------- | ------------ | ----------- | ------------ | --------- |
| Power Terminals | #6-32 x 1/4" | IP10 or T10 | 0.9 N*m      | 10 AWG    |
| CAN Terminals   | #4-40 x 1/4" | IP8 or T8   | 0.6 N*m      | 22 AWG    |

!!! warning

    DO NOT use longer screws in either location. Use of longer screws may damage the controller.

## Reference Docs

- :lucide-book-open-text: [Kraken X60 Docs](https://docs.wcproducts.com/welcome/electronics/kraken-x60) [Kraken X44 Docs](https://docs.wcproducts.com/welcome/electronics/kraken-x44)
- :lucide-siren: [Status Lights Reference](https://v6.docs.ctr-electronics.com/en/stable/docs/hardware-reference/talonfx/index.html#status-light-reference)
- :lucide-shopping-cart: [Kraken X60 Product Page](https://store.ctr-electronics.com/products/kraken-x60) [Kraken X44 Product Page](https://store.ctr-electronics.com/products/kraken-x44)