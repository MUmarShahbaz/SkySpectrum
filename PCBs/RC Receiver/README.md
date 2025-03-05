---
name: "Muhammad Umar Shahbaz"
slack_handle: "@King Howler"
github_handle: "@MUmarShahbaz"
---

![3D Model](images/RC%20Receiver%203D.png)

# RC Transmitter

The Board is a customized Receiver that uses nRF24l01 to control any Project such as a Car, Plane, SpiderBot e.t.c. The only condition is that the Transmitting device must use a Programmable MCU and a nRF24l01 (Master Mode). For this, I have already designed a custom PCB for a Transmitter.

### **Specs**

| **Pin Type** | **Pin Count**| **Description**                                                                                  |
|:------------:|:------------:|:-------------------------------------------------------------------------------------------------|
| PWM          | 2            | Standard PWM pins                                                                                |
| DEMUX PWM    | 8            | A single PWM pin expanded to 8 using a makeshift Demultiplexer - Needs Testing                   |
| Ain + Dout   | 6            | Pins that are Capable of Digital Read/Write as well as Analog Read (Using Arduino's Builtin ADC) |
| I2C          | 5            | 5 I2C Ports (HardWired together)                                                                 |



![Front](images/RC%20Receiver%202DF.png)
![Back](images/RC%20Receiver%202DB.png)

## Directory

| File/Folder    | Description                                                    |
|:--------------:|:---------------------------------------------------------------|
| 3D Model       | Contains a `.obj` file for the PCB. Exported from EasyEDA Pro. |
| images         | Images to show what the PCB should look like.                  |
| src            | `.epro` file for EasyEDA pro. Contains Schematics and PCB.     |
| BOM.csv        | BOM exported from EasyEDA Pro.                                 |
| gerber.zip     | PCB gerber file.                                               |
| schematic.pdf  | PCB schematic.                                                 |
| cart.png       | Subtotal of the order.                                         |
| cart_30pcs.png | Subtotal for order if 30 pcs ordered instead of 5.             |
| pcb_config.png | The settings chosen whilst ordering the PCB.                   |