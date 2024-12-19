# CutieCat
Build your own Cat-Themed console for hacking & prototyping, based around the [Adafruit QT-PY]() microcontroller!
*Learn more at [DevKitty.io](https://devkitty.io)*

<!-- ![](assets/img/v1.0-CutieCat_F.png) -->

#### Resources:
- [Assembly Guide](https://hackster.io)
- [Product Docs](https://docs.devkitty.io/cutiecat)
- []()

## Version
**PCB Version**: `v1.0`  
   - Hackster Special Edition
   - Regular  

**Case Version**: `v1.0`
(Case version main numbers are updated with PCB main versions).

## Content
- **src**
   - **pcb**: KiCAD PCB design files
   - **cases**: FreeCAD enclosure design files
- **exports**: ready to order / print files
- **assets**: board outline, graphic art for design, renders

## Components
|Name|Details|Number|
|---|---|---|
|Screen|SH1106 1.3" I2C OLED|1|
|Microcontroller|QT Py / Seeed Xiao|1|
|Buttons||4|
|RGB LED|WS2181B "NeoPixel"|1|
|Expansion Header|6-Pin Female 2.54mm|1|

## Changelog 
#### v1.0 Changes:
- Remove crowded headers
- Move screen + buttons up (for case margin)

#### To-Do:
- [ ] `v1.1` **PCB**: move expansion header
- [ ] `v1.1` **Case**: stronger snap point
- [ ] `v1.1` **Case**: improve printability, SMA cutouts
- [ ] `v1.1` **Case**: header case design