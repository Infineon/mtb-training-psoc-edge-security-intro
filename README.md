# PSOC™ Edge E2 Training - Security introduction

This training provides an introduction to fundamental security concepts, including 
cryptography basics, IoT security, and security threats; and then it explores the
security features available in PSOC™ Edge, providing practical experience using
Edge Protect Tools, provisioning the device, and enabling secured boot.

## Device family
- [PSOC™ Edge](https://www.infineon.com/products/microcontroller/32-bit-psoc-arm-cortex/32-bit-psoc-edge-arm)

## How to use this training?
1. Download the training [content](#content).
2. Watch the video or review the presentation at your own pace.
3. Follow the step-by-step instructions in the training manual during the hands-on sections.
4. Use the provided source files if needed to verify the solution. 

## Training level
- E2: Intermediate

## Pre-requisites 
### Recommended trainings
- This training doesn't cover basic concepts of ModusToolbox™ and PSOC™ Edge. 
  - For an introduction to PSOC™ MCUs, including getting started guides to ModusToolbox™, go to the [PSOC™ Developer Journey](https://www.infineon.com/product-information/psocdeveloper).
  - For PSOC™ Edge trainings, from begginer tutorials to advanced trainings, please visit the [PSOC™ Edge E84 Training Collection](https://infineon-academy.csod.com/ui/lms-learner-playlist/PlaylistDetails?playlistId=8f04565f-88f4-4ca7-83b3-22e501656fbd).

### Tools (see [training manual](#content) for versions and installation instructions)
- [ModusToolbox™ with Eclipse IDE](https://softwaretools.infineon.com/tools/com.ifx.tb.tool.modustoolboxsetup)
- [Edge Protect Security Suite](https://softwaretools.infineon.com/tools/com.ifx.tb.tool.modustoolboxsetup)
- [ModusToolbox™ Programming tools](https://softwaretools.infineon.com/tools/com.ifx.tb.tool.modustoolboxsetup)
- Terminal emulator

## Hardware
- [KIT_PSE84_EVAL](https://www.infineon.com/evaluation-board/KIT-PSE84-EVAL)

## Duration
- 90min, including video and hands-on labs

## Agenda
1. Cryptography basics
2. Introduction to IoT security
3. PSOC™ Edge security architecture
    - Basic boot flow
    - Secure enclave
    - Extended boot
    - Secured boot
    - Device lifecycle
    - Transfer of ownership
    - Policy file
4. Introduction to Edge Protect Tools
5. Labs demonstrating transfer of ownership, enabling secured boot, and signing an application image

## Expected outcome
- Understand fundamental concepts of security.
- Get familiar with the PSOC™ Edge security architecture and features.
- Understand how to transfer the ownership of PSOC™ Edge and how to modify policy file for development.

## Content
- [Training video at Infineon Academy](https://infineon-academy.csod.com/samldefault.aspx?ouid=1&returnURL=%252fDeepLink%252fProcessRedirect.aspx%253fmodule%253dlodetails%2526lo%253d28f341de-0dfd-4066-ba33-30c9aa1e355b)
- [Presentation](./Presentation/Introduction_to_PSOC(TM)_Edge_Security.pdf)
- [Training manual](./Manual/PSE84_Security_Introduction_Training_Manual.pdf)
- [Solution to labs](./Lab_Source/)

## References and resources

- [PSOC™ Edge MCUs](https://www.infineon.com/products/microcontroller/32-bit-psoc-arm-cortex/32-bit-psoc-edge-arm)
- [Infineon Edge Protect](https://www.infineon.com/promo/edge-protect)
- [Introduction to PSOC™ MCUs and ModusToolbox™](https://www.infineon.com/product-information/psocdeveloper)
- [PSOC™ Edge E84 training collection](https://infineon-academy.csod.com/samldefault.aspx?ouid=1&returnURL=%252fDeepLink%252fProcessRedirect.aspx%253fmodule%253dphnxdriver%2526routename%253dAdmin%252fPlayerPageRedirectHandler%2526Route%253d%25252flms-learner-playlist%25252fPlaylistDetails%2526Parameters%253dplaylistId%25253d8f04565f-88f4-4ca7-83b3-22e501656fbd)


## History

| Date | Version | Description |
| ---- | ---------   |-------------|
| 02/03/2026 | **  | First public release |  