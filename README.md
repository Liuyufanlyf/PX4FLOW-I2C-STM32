# PX4FLOW-I2C-STM32
A driver wrapping the I2C communication with a [PX4FLow](https://docs.px4.io/master/en/sensor/px4flow.html) Optical Flow Tracker.

## Usage

- Clone this repository on your local system
- Copy PX4Flow.c/.h to your project target
- Modify I2C port in PX4Flow.h, `hi2c4` for a instance
- Start using it by including "PX4Flow.h" in your project

