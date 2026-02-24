---
icon: lucide/battery-charging
---
# MitoCANdria

The MitoCANdria provides reliable, clean power to the vision PC.

## Electrical Specs

- Input voltage range 3V – 24V
- Over 10A capability on 5V rail (block of 4, labeled "5A")
- Configurable boost rail (14.5V-24V) (block of 2, labeled "VA")
  
## LED States

| Color                                          | State                           |
| ---------------------------------------------- | ------------------------------- |
| <span style="color:green">Green</span> (solid) | Firmware ready, CAN initialised |
| <span style="color:green">Green</span> + <span style="color:purple">Purple</span> (flashing) | Firmware ready, CAN awaiting bitrate detection (CAN bus disconnected) |
| <span style="color:red">Red</span> (solid) |  In Bootloader |
| <span style="color:red">Red</span> + <span style="color:yellow">Yellow</span> (flashing) | Bootloader Initialised |
| <span style="color:red">Red</span> + <span style="color:purple">Purple</span> (flashing) | Detecting CAN bitrate |

## Reference Docs

- :lucide-book-open-text: [User's Guide](https://docs.thethriftybot.com/mitocandria/)
- :lucide-shopping-cart: [Product Page](https://www.thethriftybot.com/products/mitocandria)
