![alt text](overview_cover.png)

Move-X is a division of [Move Solutions](https://www.movesolutions.it/), dedicated to the design of IoT devices. 

We create innovative technology with one aim: encouraging companies to leverage the opportunities that come with Digital Transformation. We help our clients optimize production processes, supply chains, services and infrastructures; we support them in designing intelligent environmental monitoring systems, in detecting air and water quality, in implementing smart agriculture technology, and much more. 

Many applications, one result: helping businesses use their resources more efficiently.

[Move-X MAMWLE](https://www.move-x.it/mamwle-module/) is our ultra low-power radio module for high-performance IoT devices. It embeds a powerful Cortex-M4 core for LoRaWAN stack and application code, a Sub-GHz radio and rich set of peripherals into a small footprint. The MAMWLE is also the core of [Move-X Cicerone](https://www.move-x.it/cicerone-board/), where LoRaWAN meets best in class low-power GNSS technology.

Visit [Move-X's website](https://www.move-x.it/) for more info and documentation regarding our offer.

# Contents

This GitHub profile provides resources for firmware developers using our technology.

* [__MAMWLE LoRaWAN end node__](https://github.com/Move-X/end_node_mamwle) example  for STM32Cube toolchain targeted to the MAMWLE

  * Ready to use ioc project file for STM32CubeMX code generator
  
  * Source code available with example implementation
  
  * Also [available with support for FreeRTOS](https://github.com/Move-X/end_node_freertos_mamwle)

* [__LoRaWAN AT slave__](https://github.com/Move-X/LoRaWAN_AT_Slave) ready to use firmware for adding LoRaWAN connectivity to your solution using the MAMWLE as transceiver

* [__Move-Xduino__](https://github.com/Move-X/Move-Xduino): Arduino support package for Move-X's MAMWLE module and Cicerone board
  
  * Quick start developing IoT devices within the popular Arduino IDE
  
  * Included examples for LoRAWAN end node and GNSS solutions for IoT such as u-blox ClouLocate
  
  * Access lots of libraries available from the Arduino community