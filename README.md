# STM Sensors Projects

Welcome to my collection of embedded systems projects! This repository contains a variety of projects working with different sensors, communication protocols, and peripherals, primarily targeting STM32 microcontrollers. 

These projects serve as examples, experiments, and practical implementations of interfacing hardware components with microcontrollers.

## 📁 Projects Overview

Here is a breakdown of the projects included in this repository:

### 📡 Communication Protocols & Interfaces
* **[UART_try](./UART_try)** & **[UART_receive](./UART_receive)** - Universal Asynchronous Receiver-Transmitter basic setup and data reception.
* **[accelerometer_i2c](./accelerometer_i2c)** - Interfacing with an accelerometer using the I2C protocol.
* **[accelerometer_i2c_dma](./accelerometer_i2c_dma)** - Advanced accelerometer interfacing using I2C with Direct Memory Access (DMA) for efficient, non-blocking data transfer.
* **[led_matrix_spi](./led_matrix_spi)** - Controlling an LED matrix via the SPI protocol.

### 🔴 Infrared (IR) Communication
* **[IR_Transmit](./IR_Transmit)** - Sending basic IR signals.
* **[IR_Receive](./IR_Receive)** - Receiving and decoding IR signals.
* **[IR_Transmit_and_Receive](./IR_Transmit_and_Receive)** - Combined infrared transmission and reception in a single project.
* **[IR_transmit_char](./IR_transmit_char)** - Transmitting specific characters or data payloads via infrared.

### 🌡️ Sensors & Data Acquisition
* **[temperature_i2c](./temperature_i2c)** - Reading data from an I2C temperature sensor.
* **[ldr_adc](./ldr_adc)** - Light-Dependent Resistor (LDR) reading using the Analog-to-Digital Converter (ADC).
* **[voltage_acquisition_DMA](./voltage_acquisition_DMA)** - Efficient analog voltage reading using ADC paired with DMA.

### ⌨️ Input / Output Peripherals
* **[keyboard](./keyboard)** - Interfacing with a keypad/keyboard matrix for user input.
* **[lcd_try](./lcd_try)** - Driving a basic Liquid Crystal Display (LCD) to show text.
* **[play_song](./play_song)** - Generating audio/tones using a buzzer or speaker to play a melody.

### 🧪 Test Projects
* **[progetto_prova](./progetto_prova)** - Initial trial/test project.
* **[prog_test2](./prog_test2)** - Secondary test project.

## 🛠️ Getting Started

To get started with any of these projects:
1. Clone this repository to your local machine.
2. Navigate to the project folder you want to explore.
3. Open the project in your preferred STM32 IDE (such as STM32CubeIDE).
4. Compile/build the project and flash the resulting binary to your microcontroller.

---
*Feel free to explore the code in each directory to see how the peripherals and sensors are configured and used!*
