# Possibly the most best Verilog-Based DPI and MIPI-DSI FPGA Examples

## If this project is constructive, welcome to donate a drink to PayPal.

<img src="images/qrcode.png" style="height:20%; width:20%">

or 

paypal.me/briansune

### This proejct targeted most commonly used camera module or sensor

### The sensors example

|Idx|Display|Status|I/F|Driver IC|Lane #|Mode|Project Link|FPGA|IDE|FPS|W,H,Bpp|
|:-:|:-:    |:-:   |:-:      |:-:   |:-:         |:-: |:-:|:-:|:-:    |
|  1 | Circle    | 🟢 DONE    | MIPI | ST7797       | 1 | V   | [DT160BQ-C12-01](https://github.com/briansune/Kintex-7-MIPI-DSI-1.6-inch-LCD) | XC7,ZU | Vivado 2020.2 | 60 |   400,400,[16,24] |
|  2 | Rectangle | 🟢 DONE    | MIPI | ST7701S      | 2 | V   | [CY300H4003](https://github.com/briansune/Kintex-7-MIPI-DSI-2.95-inch-LCD)    | XC7,ZU | Vivado 2020.2 | 60 |   360,640,[16,24] |
|  3 | Rectangle | 🟢 DONE    | MIPI | ST7701S      | 2 | V   | [T397B5-C24-02](https://github.com/briansune/Kintex-7-MIPI-DSI-3.97-inch-LCD) | XC7,ZU | Vivado 2020.2 | 60 |   480,800,[16,24] |
|  4 | Rectangle | 🟢 DONE    | MIPI | NT35516      | 2 | V/C | [INX4.5](https://github.com/briansune/Kintex-7-MIPI-DSI-4.5-inch-LCD)         | XC7,ZU | Vivado 2020.2 | 60 |   540,960,[16,24] |
|  5 | Rectangle | 🟢 DONE    | MIPI | HX8399C      | 4 | V   | [AML055T012A](https://github.com/briansune/Kintex-7-MIPI-DSI-5.5-inch-LCD)    | XC7,ZU | Vivado 2020.2 | 60 | 1080,1920,[16,24] |
|  6 | Rectangle | 🔜 PENDING | MIPI | ST7701S      | 2 | V   | [HXR397HS25PIN]()                                                             | XC7,ZU | Vivado 2020.2 | 60 |   480,800,[16,24] |
|  7 | Rectangle | 🔜 PENDING | MIPI | R61322       | 4 | V   | [DXQ5D0039]()                                                                 | XC7,ZU | Vivado 2020.2 | 60 | 1080,1920,[16,24] |
|  8 | Circle    | 🔜 PENDING | MIPI | JD9365DA-H3  | 3 | V   | [HD34003C39]()                                                                | XC7,ZU | Vivado 2020.2 | 60 |   800,800,[16,24] |
|  9 | Rectangle | 🔜 PENDING | MIPI | ST7701S      | 2 | V   | [HXR030HSD40PIN]()                                                            | XC7,ZU | Vivado 2020.2 | 60 |   360,640,[16,24] |
| 10 | Rectangle | 🟢 DONE    | DPI  | AT070N92/94  | x | V   | [AT070N92/94](https://github.com/briansune/max-II-cpld-sdram-tft-driver)      | MAX II | Quartus       | 60 |   800,480,24      |
| 10 | Rectangle | 🟢 DONE    | DPI  | AT070N92/94  | x | V   | [AT070N92/94](https://github.com/briansune/Spartan_3_sdram_ftf_driver)        | XC3    | ISE 14.7      | 60 |   800,480,24      |