# L4VMX Features

> V2.2.0 2023/04/28
>

L4VMX (LabVIEW for VMX-pi)  

L4VMX makes it possible to program Studica VMX-pi robot with LabVIEW language.  

It is stable and high-end performance.  

It is designed for ease of use, similar to NI myRIO.  

Currently support for LabVIEW 2020 Community.  

## Main Features

![image-20230428135229756](./assets/image-20230428135229756.png)

### [VMXpi](https://github.com/L4VMX/L4VMX-LabVIEW)

![image-20230428134229305](./assets/image-20230428134229305.png)

### [TitanQuad](https://github.com/L4VMX/L4VMX-LabVIEW-TitanQuad)

![image-20230428135317308](./assets/image-20230428135317308.png)

### [WorldSkills Toolbox](https://github.com/L4VMX/L4VMX-LabVIEW-WorldSkills-Toolbox)

![image-20230428135241901](./assets/image-20230428135241901.png)

### Supported Core Features

- Digital Input
- Digital Output
- PWM Generator
- Input Capture
- Analog Input
- Encoder
- IMU
- I2C
- CAN Bus
- CAN Bus Receive Stream
- Power
- RTC

### Not Yet Supported Core Features

- UART
- SPI
- LED Array (WS2812)

## VMXpi

### Digital Input

![image-20230428140047882](./assets/image-20230428140047882.png)

### Digital Output

![image-20230428140108943](./assets/image-20230428140108943.png)



### PWM Generator

![image-20230428140244910](./assets/image-20230428140244910.png)

### Input Capture

![image-20230428140307231](./assets/image-20230428140307231.png)

It can be used to capture digital signals such as ultrasonic sensor echo signals or pwm signals.  

### Analog Input

![image-20230428140445583](./assets/image-20230428140445583.png)

### Encoder

![image-20230428140507870](./assets/image-20230428140507870.png)

### IMU

![image-20230428140522096](./assets/image-20230428140522096.png)

### I2C

![image-20230428140534344](./assets/image-20230428140534344.png)

### CAN Bus

![image-20230428140548225](./assets/image-20230428140548225.png)

### CAN Bus Receive Stream

![image-20230428140649676](./assets/image-20230428140649676.png)

### Power

![image-20230428140703418](./assets/image-20230428140703418.png)

### RTC

![image-20230428140718314](./assets/image-20230428140718314.png)

### Utilities

![image-20230428140734201](./assets/image-20230428140734201.png)

### Low Level / Communication

![image-20230428140802410](./assets/image-20230428140802410.png)

## Studica TitanQuad

![image-20230428141119706](./assets/image-20230428141119706.png)

## WorldSkills Toolbox

### HC-SR04

![image-20230428141143026](./assets/image-20230428141143026.png)

HC-SR04 is a ultrasonic sensor.  

### Studica Cobra I2C

![image-20230428141200327](./assets/image-20230428141200327.png)

Studica Cobra is a line sensor.  

### ADS1X15

![image-20230428141230186](./assets/image-20230428141230186.png)

ADS1015/ADS1115 are ADC.

## Easy to Use

### Digital Input Example

![image-20230428142323826](./assets/image-20230428142323826.png)

### Encoder Example

![image-20230428142510790](./assets/image-20230428142510790.png)

### DC Motor PID Controller

![image-20230428150524204](./assets/image-20230428150524204.png)

It's really easy to write a motor pid control program.  

### IO Smart Open

![image-20230428151703773](./assets/image-20230428151703773.png)

It supports smart open, so you can put IO Open in a loop, and it will automatically initialize the port the first time, without any problem.  

### Read Ultrasonic Sensor Distance

![image-20230428152547778](./assets/image-20230428152547778.png)

Use WorldSkills Toolbox to read ultrasonic sensors without writing difficult signal processing.  



## Powered By ReMiSYS

![logo](./assets/logo.webp)

Copyright © 2023 ReMiSYS Technology Co., Ltd.
