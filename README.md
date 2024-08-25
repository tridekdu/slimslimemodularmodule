# Slim and modular SlimeVR module
## Goals
* Easy wiring and provide supplementary components (caps, etc.)
* Support many readymade AliExpress-tier modules (they seem to have similar pinouts)
* Be compatible with SlimeVR
* Provide wide selection of power input methods

## Needed parts
### PCB
* SW1 = PCM12 slide switch
* R1, R2, R3 = 10K pull-up/down resistors for ESP
* R4 and R5 = Similar sized resistor ~100K (battery monitor voltage divider)
* 100n bypass caps
* Optional AMS1117-3.3V regulator
* Optional 1N5817 Diode

SMD components are 0805 sized

### External modules
* Accelerometer module (for example: MPU6XXX or BNO08X)
* Power management module (for example: TP4056)
* Lithium battery


![Schematic](https://github.com/tridekdu/slimslimemodularmodule/blob/main/images/schema.png)

## Design sketches
![Design Sketch 1.0](https://github.com/tridekdu/slimslimemodularmodule/blob/main/images/design1.png)

## Example 
![Example build 1.1](https://github.com/tridekdu/slimslimemodularmodule/blob/main/images/example1.png)
![Example build 1.2](https://github.com/tridekdu/slimslimemodularmodule/blob/main/images/example2.png)