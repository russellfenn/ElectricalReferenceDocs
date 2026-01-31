---
icon: lucide/disc-3
---
# Neo Vortex Motor / Spark Flex Controller

## LED States

### Normal Operations

| LED State                                        | Signal      | Mode       |
| ------------------------------------------------ | ----------- | ---------- |
| Blink <span style="color:cyan">Cyan</span>       | No Signal   | Brake mode |
| Solid <span style="color:cyan">Cyan</span>       | Good Signal | Brake mode |
| Blink <span style="color:magenta">Magenta</span> | No Signal   | Coast mode |
| Solid <span style="color:magenta">Magenta</span> | Good Signal | Coast mode |

:lucide-lightbulb: Note: These are for **brushless motors**. See the full list of [Blink Codes](https://docs.revrobotics.com/brushless/spark-flex/status-led).

:lucide-refresh-cw: Switch between Brake Mode (Cyan) and Coast Mode (Magenta) with the Mode button. Must be on main power (not just USB power).

### Error States

| LED State                                        | Fault                             |
| ------------------------------------------------ | --------------------------------- |
| <span style="color:orange">Orange</span> / <span style="color:blue">Blue</span> Slow Blink | 12V missing |
| <span style="color:orange">Orange</span> / <span style="color:yellow">Yellow</span> Slow Blink | CAN Fault |
| <span style="color:orange">Orange</span> / <span style="color:green">Green</span> Slow Blink | Temperature Cutoff |


## Electrical Specs

## Reference Docs

- :lucide-book-open-text: [User's Guide]()
