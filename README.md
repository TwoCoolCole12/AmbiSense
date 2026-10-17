# AmbiScout
A portable environment sensor to sense ambient temperature, humidity, light, movement speed, and more!

Inspired by features on the Starbie, but extended for functionality and development time. 

Living in a place where the climate constantly fluctuates, it can be handy to glance at a small device that's 
not a phone to see what's happening in the air around oneself.

<img width="1732" height="992" alt="Screenshot 2026-10-10 183336" src="https://github.com/user-attachments/assets/c6258785-c66a-47f5-b19d-a225aa41e19d" />

Here's some of the planned features:

- [x] Temperature Sensor
- [x] Humidity Sensor
- [x] Battery Powered or Rechargeability
- [x] OLED Display
- [x] Navigation Buttons
- [x] Power/Charging Indicator
- [x] Ambient Light Level Monitor
- [x] Audio Sensor

Checks does not mean it's programmed, just accounted for and wired.

With enough work, it might be reasonable to add in these features too, but they are lower priority:

- [x] Wi-Fi Connection
- [x] Bluetooth Compatiblitiy
- [x] Access to Weather Forcasts
- [x] Push Notifications when Major Changes Occue
- [x] Charging & Battery Info
- [ ] CO2 Sensor
- [x] Barometric Pressure Sensor
- [ ] Built in Clock
- [ ] Movement Sensor

<img width="1540" height="792" alt="image" src="https://github.com/user-attachments/assets/6696779c-9822-4993-9d67-4103371ddfd6" />

**Hardware Specifications** WIP

* Espressif ESP32-S3-MINI-1-N8 Microcontroller
  * Pin Reference: https://documentation.espressif.com/esp32-s3-mini-1_mini-1u_datasheet_en.html
* PDV-8103 Light Dependent Resistor
  * Pin Reference: https://www.advancedphotonix.com/wp-content/uploads/2015/07/DS-PDV-P8103.pdf
* I2C SHT31-DIS Temperature & Humidity Sensor
  * Pin Reference: https://sensirion.com/media/documents/213E6A3B/63A5A569/Datasheet_SHT3x_DIS.pdf
* SPH0655LM4H-1-8 Sound Sensor
  * Pin Reference: https://mm.digikey.com/Volume0/opasdata/d220001/medias/docus/6634/SPH0655LM4H-1-8.pdf
* WEA012864DBPP3N00003 OLED Screen
  * Pin Reference: https://mm.digikey.com/Volume0/opasdata/d220001/medias/docus/5485/WEA012864DBPP3N00003.pdf
* TPS63802 2-A Buck Boost Converter
  * Pin Reference: https://www.ti.com/lit/ds/symlink/tps63802.pdf
* BQ2407x Standalone Linear Battery Charger
  * Pin Reference: https://www.ti.com/lit/ds/symlink/bq24074.pdf?HQS=dis-dk-null-digikeymode-dsf-pf-null-wwe&ts=1791636441127&ref_url=https%253A%252F%252Fwww.ti.com%252Fgeneral%252Fdocs%252Fsuppproductinfo.tsp%253FdistId%253D10%2526gotoUrl%253Dhttps%253A%252F%252Fwww.ti.com%252Flit%252Fgpn%252Fbq24074
* Push-Button Switch
  * Pin Reference: https://www.te.com/commerce/DocumentDelivery/DDEController?Action=srchrtrv&DocNm=8-1773450-9_SECTION_C_TACTILE_SWITCHES&DocType=Data%20Sheet&DocLang=English&DocFormat=pdf&PartCntxt=1825910-6
* BMP384 Pressure Sensor
  * Pin Reference: https://mm.digikey.com/Volume0/opasdata/d220001/medias/docus/3999/bst-bmp384-ds003.pdf
* USB4105 USB-C Receptacle
  * Pin Reference: https://gct.co/files/specs/usb4105-spec.pdf
