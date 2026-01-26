![Cover](/profile/overview_cover.png?raw=true)

Move Silicon is a division of Move S.p.A. focused on accelerating chip design with AI-driven solutions. We enable companies to optimize workflows, enhance innovation, and reduce time-to-market for analog and mixed-signal circuits. Our core offerings include [Spaceman](https://movesilicon.com/spaceman/spaceman-overview), an AI tool that automates analog block sizing within existing EDA flows, and [Custom Silicon Services](https://movesilicon.com/asic-design/custom-asic), covering end-to-end ASIC design and IP creation.
Many applications, one result: helping businesses bring complex silicon projects to life efficiently and reliably.

Move Silicon also develops IoT solutions. **MAMWLE** is our ultra low-power radio module for high-performance IoT devices, embedding a Cortex-M4 core for LoRaWAN stack and application code, a Sub-GHz radio, and a rich set of peripherals. It also powers **Cicerone**, where LoRaWAN meets best-in-class low-power GNSS technology.

Discover more about our AI tools and IoT solutions on [Move Silicon's website](https://www.movesilicon.com/).

# Contents

This GitHub profile provides resources for firmware developers using our technology.

* [__MAMWLE LoRaWAN end node__](https://github.com/Move-X/end_node_mamwle) example  for STM32Cube toolchain targeted to the MAMWLE

  * Ready to use ioc project file for STM32CubeMX code generator
  
  * Source code available with example implementation
  
  * Also [available with support for FreeRTOS](https://github.com/Move-X/end_node_freertos_mamwle)

* [__LoRaWAN AT slave__](https://github.com/Move-X/LoRaWAN_AT_Slave) ready to use firmware for adding LoRaWAN connectivity to your solution using the MAMWLE as transceiver

* [__Move-Xduino__](https://github.com/Move-X/Move-Xduino): Arduino support package for MAMWLE module and Cicerone board
  
  * Quick start developing IoT devices within the popular Arduino IDE
  
  * Included examples for LoRAWAN end node and GNSS solutions for IoT such as u-blox CloudLocate
  
  * Access lots of libraries available from the Arduino community
