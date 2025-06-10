# IS4310 Modbus Actuator with Arduino

## Description:
This example demonstrates how to use the IS4310 Modbus RTU Slave chip with the Arduino platform.

The sketch creates a Modbus actuator using the IS4310. The Arduino reads Modbus Holding Registers 1, 2, and 3 and maps their values to an RGB LED—creating a simple pixel controlled over Modbus RTU.

You can write to the Holding Registers from your PC using a Modbus master client, such as [qModMaster](https://sourceforge.net/projects/qmodmaster/).

## Default Modbus Connection Parameters:
- **Slave Address**: 1
- **Baud Rate**: 19200 bps
- **Parity**: Even
- **Stop Bits**: 1

## If You're Using the Kappa4310Ard Evaluation Board:
- Set the "I2C Speed Selector" jumper to **100 kHz**.
- Set the "I2C Pull-up Voltage" according to your microcontroller's logic level. If unsure, use **3.3 V**.

Check the product page at [www.inacks.com/is4310](https://www.inacks.com/is4310).

ℹ️ For more information: [www.inacks.com](https://www.inacks.com)
