# nRF Connect BLE Gyro Mouse

This project implements a Bluetooth Low Energy (BLE) mouse using a gyroscope for motion control, built on the Zephyr RTOS. It's designed for the Seeed XIAO BLE Sense board with the XIAO Expansion board.

## Features

- BLE HID device implementation
- Gyroscope-based cursor movement
- Button controls for click actions
- Battery level reporting

## Hardware

- Seeed XIAO BLE Sense (nRF52840)
- Seeed XIAO Expansion Board

## Build

To build the project, use the following West command:

```
west build -b xiao_ble/nrf52840/sense --shield seeed_xiao_expansion_board -p auto
```
