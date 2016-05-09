# cmsis
This CMSIS only include header files without any drivers to provide HAL for [mini-arm-os](https://github.com/jserv/mini-arm-os).

Where does this CMSIS comes from?
===================================
These files comes from [mbed repository](https://github.com/mbedmicro/mbed/tree/master/libraries/mbed/targets/cmsis).

And the ["STM32F429" dir is here](https://github.com/mbedmicro/mbed/tree/master/libraries/mbed/targets/cmsis/TARGET_STM/TARGET_STM32F4/TARGET_DISCO_F429ZI)

Why we need this repositroy?
==============================
When you would like to try [mini-arm-os](https://github.com/jserv/mini-arm-os).

Directory naming strategy
===========================
- (vendor name) + (your device name)
  - Ex:STM32 + f429disco = STM32f429disco

More datails/porting
===========================
See the [README in mini-arm-os](https://github.com/jserv/mini-arm-os/blob/master/README.md)
