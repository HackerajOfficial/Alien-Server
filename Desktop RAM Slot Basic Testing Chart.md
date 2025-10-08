# Desktop RAM Slot Basic Testing Chart

| SL No. | Voltage / Signal | DDR2 (240 Pins) | DDR3 (240 Pins) | DDR4 (288 Pins) | DDR5 (288 Pins) |
|:------:|:-----------------|:----------------|:----------------|:----------------|:----------------|
| 1 | **VPP** | ✗ | ✗ | 2.5V (Pin 143/145/267/271/273) | ✗ |
| 2 | **VDDQ** | 1.8V (Pin 51/54/67/75) | 1.5V (Pin 51/54/57/60) | 1.2V (Pin 114/133/134/153) | 5V (Pin 81/145/146) |
| 3 | **VTT** | 0.9V (On termination resistor) | 0.75V (Pin 120/240) | 0.6V (Pin 77/221) | ✗ |
| 4 | **VREF_DQ** | 0.9V (Pin 114) | 0.75V (Pin 114) | ✗ | ✗ |
| 5 | **VREF_CA** | ✗ | ✗ | 0.6V (Pin 164) | ✗ |
| 6 | **VDD_SPD** | 3.3V (Pin 236) | 3.3V (Pin 236) | 3.3V (Pin 224) | ✗ |
| 7 | **SDA** | 3.3V (Pin 238) | 3.3V (Pin 238) | 3.3V (Pin 285) | 3.3V (Pin 5) |
| 8 | **SCL** | 3.3V (Pin 240) | 3.3V (Pin 240) | 3.3V (Pin 241) | 3.3V (Pin 84) |
| 9 | **DRAM_RESET** | ✗ | 1.5V (Pin 166) | 1.2V (Pin 65) | 1.2V (Pin 95) |
| 10 | **DRAM_POWER_EN** | ✗ | ✗ | ✗ | 3.3V (Pin 151) |
| 11 | **DRAM_PWR_GOOD** | ✗ | ✗ | ✗ | 3.3V (Pin 147) |
