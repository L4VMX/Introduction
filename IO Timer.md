# L4VMX IO Timer

## Timer IO Mode

When using the following IO modes, VMX built-in timers will be used.

- PWM Generator
- Input Capture
- Encoder

## Timer Channel

### FlexDIO

| Timer 0 |      | Timer 1 |      | Timer 2 |      | Timer3 |      | Timer 4 |      | Timer 5 |      |
| ------- | ---- | ------- | ---- | ------- | ---- | ------ | ---- | ------- | ---- | ------- | ---- |
| 0       | 1    | 2       | 3    | 4       | 5    | 6      | 7    | 8       | 9    | 10      | 11   |

### HighCurrentDIO

| Timer 6 | Timer 7 | Timer 8 | Timer 9 | Timer 10 | Timer 11 | Timer 12 | Timer 13 | Timer 14 | Timer 15 |
| ------- | ------- | ------- | ------- | -------- | -------- | -------- | -------- | -------- | -------- |
| 12      | 13      | 14      | 15      | 16       | 17       | 18       | 19       | 20       | 21       |

## Issues

Since some IO pins use the same timer, we can't open the pin if the timer opened.  

For example, if opened pin 0 in PWM Generator mode, than you can't open pin 1 in Input Capture mode, but you still can open in IO mode not using timer such as Digital Input/Output.

## How to use a sensor need two timer

Due to the problem of the timer, we cannot use some sensors, such as ultrasonic sensors, in two pins of one timer, so we recommend you to use one FlexDIO pin as the echo pin and the other HighCurrentDIO pin as the trigger pin.  

Ultrasonic sensor example: Trigger pin = 12 (Timer 6), Echo pin = 11(Timer 5).  

And you still can use pin 10 in Digital Input/Output mode.  



## Powered By ReMiSYS

![logo](./assets/logo.webp)

Copyright © 2023 ReMiSYS Technology Co., Ltd.