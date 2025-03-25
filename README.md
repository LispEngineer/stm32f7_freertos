# Nucleo-F767ZI and Current FreeRTOS

* Author: [Douglas P. Fields, Jr.](mailto:symbolics@lisp.engineer)
* Date created: 2025-03-25
* Date updated: 2025-03-25
* License: Apache 2.0 for portions authored by Doug

## Overview

A project to integrate the current FreeRTOS,
which is 202406.01 LTS as of this writing,
into an STM32F7 project to serve as a basis
for doing the same for my existing
[Synthesizer Project](TODO).

## Components used

Hardware:

* Board: STM Nucleo-F767ZI
* Firmware: Segger J-Link (reflashed on the built-in ST-Link)

Software:

* STM32CubeIDE 1.18.0
* FreeRTOS 202406.01 LTS

## References

* [Udemy Course](https://www.udemy.com/course/mastering-rtos-hands-on-with-freertos-arduino-and-stm32fx/)