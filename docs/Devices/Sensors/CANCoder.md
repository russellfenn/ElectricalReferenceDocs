---
icon: lucide/magnet
---
# CANCoder

![CANCoder](https://store.ctr-electronics.com/cdn/shop/files/CANCoder-wired-rotary-magnetic-encoder-robotics-automation-product.png?v=1756386105){ width=128 align=right }

The [CTR CANCoder](https://store.ctr-electronics.com/products/cancoder) is a magnetic rotoary motion encoder that reports rotation data over the CAN bus.

## LED Status

### Normal Operation

| LED Color    | LED Brightness | CAN Bus detection | Magnet Field Strength | Description                          |
| ------------ | -------------- | ----------------- | --------------------- | ------------------------------------ |
| Rapid <span style="color:green">Green</span> Blink | Bright | CAN bus present | Magnet in range. | |
| Rapid <span style="color:yellow">Yellow</span> Blink | Bright | CAN bus present | Magnet in range with reduced accuracy. | || Rapid <span style="color:red">Red</span> Blink | Bright | CAN bus present | Magnet is out of range. | |

### Error States

| LED Color    | LED Brightness | CAN Bus detection | Magnet Field Strength | Description                          |
| ------------ | -------------- | ----------------- | --------------------- | ------------------------------------ |
| Slow <span style="color:red">Red</span> Blink | Bright | CAN bus has been lost. | --- | Check CAN Bus health and connection to the CANCoder. |
| Rapid <span style="color:red">Red</span> Blink | Dim | CAN bus never detected since boot | Magnet is out of range. | |
| Rapid <span style="color:yellow">Yellow</span> Blink | Dim | CAN bus never detected since boot | Magnet in range with reduced accuracy. | |
| Rapid <span style="color:green">Green</span> Blink | Dim | CAN bus never detected since boot | Magnet in range. | |
| Off          | ---            | ---               | ---                   | CANCoder is not powered/ plugged in. <br/> Check power cabling to the CANCoder. |
| <span style="color:yellow">Yellow</span>/<span style="color:green">Green</span> | Bright         | ---               | ---                  | Device is in boot-loader             |
| <span style="color:red">Red</span>/<span style="color:green">Green</span>    | Bright         | ---               | ---                  | Device has Phoenix Pro firmware and is unlicensed. |

## Electrical Specs

## Magnet Specs

| Parameter | Condition | Value  | Unit |
| --------- | --------- | ------ | ---- |
| Length    | ±0.004    | .500   | INCH |
| Diameter  | ±0.004    | .250   | INCH |
| Material  | Grade N42 | NdFeB  |      |
| Plating   |           | Nickel |      |
| Magnetization Direction | | Diametrical | |

## Reference Docs

- :lucide-book-open-text: [User's Guide](https://ctre.download/files/user-manual/CANCoder%20User's%20Guide.pdf)
- :lucide-shopping-cart: [Product Page](https://store.ctr-electronics.com/products/cancoder)