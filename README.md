[![ MCP3428](MCP3428_I2CADC.png)](https://store.ncd.io/product/mcp3428-4-channel-analog-to-digital-converter-16-bit-i2c-mini-module/).

#  MCP3428

The MCP3428 is a 4-Channel Analog to Digital Converter with 16-Bit resolution, ideally suited for low-speed high-resolution sensor monitoring. The MCP3428 is capable of reading analog voltages at 15 samples per second with 16-Bit resolution or 240 samples per second at 12-bit resolution.
This Device is available from www.ncd.io 

[SKU: MCP3428]

(https://store.ncd.io/product/mcp3428-4-channel-analog-to-digital-converter-16-bit-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface MCP3428 16Bit 4Channel ADC With Raspberry Pi :
1. <a href="https://store.ncd.io/product/mcp3428-4-channel-analog-to-digital-converter-16-bit-i2c-mini-module/">MCP3428 16Bit 4Channel ADC</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python MCP3428.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
