# STM32 Timer and ADC Application

## Description
This project demonstrates the use of STM32 microcontroller for timer-based operations and analog-to-digital conversion. The system reads analog input signals and processes them using the internal ADC of the STM32.

## Features
- Timer-based operation
- Analog signal acquisition using inbuilt ADC
- Embedded firmware implementation using STM32

## Components Used
- STM32 microcontroller
- Analog input source
- Development environment (STM32 software)

## Working
The STM32 microcontroller is configured to perform analog-to-digital conversion using its internal ADC. A timer is used to control the display cycle of the output.
The ADC reads the analog input signal and the converted digital value is displayed for 2 seconds. After this, the display is cleared for 1 second. This cycle repeats continuously, resulting in a total timer-controlled cycle of 3 seconds.
This implementation demonstrates the use of timer-based scheduling along with ADC for periodic data acquisition and display control.

## Output
Refer to the uploaded video for working demonstration.

## Author
Rishika
