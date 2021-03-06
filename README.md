# esp-water-temp
Log water temp to thingspeak using an esp-01 and a ds18B20 temp sensor

## Dependencies
- Requires the OneWire Library from here: https://github.com/PaulStoffregen/OneWire
- Requires the WifiManager Library from here: https://github.com/tzapu/WiFiManager
- Requires the DallasTemperature Library from here: https://github.com/milesburton/Arduino-Temperature-Control-Library
- Requires the DHT Library from here: https://github.com/adafruit/DHT-sensor-library

## Hardware
When purchased in bulk (10pcs), component costs come in at around £3 for a basic DS18B20 or DHT11 sensor, or about £5 for a higher resolution DHT22.

### Sensors
- DS18B20 £0.50 http://www.ebay.co.uk/itm/10Pcs-DALLAS-DS18B20-18B20-TO-92-Thermometer-Temperature-Sensor-MO-/152236378750?hash=item2371feca7e:g:ZcEAAOSwXeJYNBLN
- DHT11 £0.49 http://www.ebay.co.uk/itm/10pcs-DHT11-DHT-11-Digital-Temperature-and-Humidity-Sensor-for-Arduino-/192055645655?hash=item2cb76895d7:g:Rm0AAOSw8w1X79ND
- DHT22 £2.11 http://www.ebay.co.uk/itm/1-2-5-10PCS-DHT22-AM2302-Temperature-Humidity-Sensor-Replace-SHT11-SHT15-Module-/272484297869?var=&hash=item3f71546c8d:m:mGt9gF2SrPUPrgvcAIzpEHg

### Other Hardware
- Connector £0.10 http://www.ebay.co.uk/itm/10-x-MICRO-USB-to-DIP-Adapter-5pin-Female-Connector-B-Type-PCB-Converter-/122258312781?hash=item1c7729ce4d:g:B7AAAOSwB09YR-cJ
- Power Supply £0.10 http://www.ebay.co.uk/itm/10PCS-4-5V-7V-to-3-3V-AMS1117-3-3V-Power-Supply-Module-AMS1117-3-3-New-/142174787483?hash=item211a47179b:g:eUsAAOSwMVdYIvPA
- ESP-01 £1.50 http://www.ebay.co.uk/itm/152113749822
- Header socket £0.13 http://www.ebay.co.uk/itm/10pcs-2-54MM-40-Pin-Single-Row-Straight-Female-Pitch-Header-Socket-Connector-PCB-/301874080743?hash=item464918ebe7:g:TrkAAOSwG-1WwuMo
- Pull up resistor £0.01 http://www.ebay.co.uk/itm/100PCS-4-7K-4K7-Ohms-1-4W-0-25W-5-Carbon-Film-Resistors-Resistance-/172394294675?hash=item2823802d93:g:REYAAOSwImRYF-0T
- Strip board £0.40 http://www.ebay.co.uk/itm/5-x-New-Stripboard-Strip-Board-25mm-x-64mm-Vero-Style-/120540034387?hash=item1c10bef553:g:-cYAAOSwpzdWqJjv
- Push Button £0.04 http://m.ebay.co.uk/itm/50-Pcs-6x3-5x5mm-DIP-PCB-Momentary-Push-Button-Tact-Switch-/121800118624?hash=item1c5bda5160%3Ag%3AxSQAAOSwwbdWMRq4&_trkparms=pageci%253Ab0f24321-cd60-11e6-8d95-74dbd180e897%257Cparentrq%253A480ddc561590a60ca5335f26ffde3c19%257Ciid%253A3
- Smoothing Capacitor £0.03 http://www.ebay.co.uk/itm/40-Pcs-1000uF-6-3V-105-Radial-Electrolytic-Capacitors-Dark-green-8x12mm-BT-/282240517215?_trksid=p2349526.m2548.l4275

### For programming
- 3.3V FTDI module £1.42 http://www.ebay.co.uk/itm/262693491468
