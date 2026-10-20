# CANCoder

<img src="./CANCoder.png" width="200" height="200" alt="CANCoder" />

The CTR CANCoder is a magnetic rotoary motion encoder that reports rotation data over the CAN bus.

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
| Off          | ---            | ---               | ---                   | CANCoder is not powered/ plugged in. <br/>Check power cabling to the CANCoder. |
| <span style="color:yellow">Yellow</span>/<span style="color:green">Green</span> | Bright         | ---               | ---                  | Device is in boot-loader             |
| <span style="color:red">Red</span>/<span style="color:green">Green</span>    | Bright         | ---               | ---                  | Device has Phoenix Pro firmware and is unlicensed. |

## Electrical Specs
| | |
| --| -- |
|Supply Voltage|6-16V|
|Current Draw|<50 mA nominal, 60 mA max|
|ESD Protection|30kV|
|Recommended Min Wire Gauge|22AWG|

|Cable Colors|Signal|AWG|Cable Length|Exposed End|
|---|---|---|---|---|
|Red|V+|22|12"|~3/8" Stripped & Tinned Lead|
|Black|Ground|22|12"|~3/8" Stripped & Tinned Lead|
|Yellow|CAN High|22|12"|0.1" spaced 3-pin connector (wires to outside, no middle pin)|
|Green|CAN Low|22|12"|0.1" spaced 3-pin connector (wires to outside, no middle pin)|

## Magnet Specs

| Parameter | Condition | Value  | Unit |
| --------- | --------- | ------ | ---- |
| Length    | ±0.004    | .500   | INCH |
| Diameter  | ±0.004    | .250   | INCH |
| Material  | Grade N42 | NdFeB  |      |
| Plating   |           | Nickel |      |
| Magnetization Direction | | Diametrical | |

## Reference Docs

- <img src="../../assets/icons/book-open-text.svg" width="18" height="18" alt="User Guide"> [User's Guide](https://ctre.download/files/user-manual/CANCoder%20User's%20Guide.pdf)
- <img src="../../assets/icons/shopping-cart.svg" width="18" height="18" alt="Shop"> [Product Page](https://store.ctr-electronics.com/products/cancoder)
