

# DC-DC Buck Converter

## Project Overview

In this project, we developed a DC-DC buck converter to step down a 10V input to a stable 7.5V unregulated output. This converter was designed and implemented using the TL494 module for pulse width modulation (PWM) control of the MOSFET, ensuring efficient voltage regulation. The project was completed as a group effort under the Electrical Machines and Power Electronics Lab course.

## Specifications

- **Input Voltage:** 10V
- **Output Voltage:** 7.5V
- **Switching Frequency:** 5 kHz
- **Output Current:** 1A
- **Modes:** Continuous Conduction Mode (CCM) and Discontinuous Conduction Mode (DCM)

## TL494 Module Details

The TL494 is a versatile PWM control circuit designed for controlling the duty cycle of the switching element in DC-DC converters. It provides several key features:
- **PWM Control:** Generates PWM signals for precise control of the MOSFET.
- **Error Amplifiers:** Contains two error amplifiers for voltage feedback control.
- **Oscillator:** Built-in oscillator with adjustable frequency, set to 5 kHz for this project.
- **Dead-Time Control:** Prevents overlap of the MOSFET switching to avoid short circuits.
- **Output Control:** Configurable output control for single-ended or push-pull operation.

## Project Steps

### 1. Simulation
- Simulated the DC-DC buck converter circuit to verify design specifications.
- Obtained simulation plots showing the expected behavior of the converter in both CCM and DCM.

### 2. TL494 Module Configuration
- Configured the TL494 module to generate PWM signals with a frequency of 5 kHz.
- Adjusted the duty cycle to achieve the desired output voltage of 7.5V.

### 3. Hardware Implementation
- **Component Soldering:** Soldered the components on a general-purpose PCB, ensuring proper isolation between the drive circuit ground and the power circuit ground.
- **MOSFET Control:** Integrated the TL494 module for PWM control of the MOSFET, ensuring efficient switching.
- **Voltage Regulation:** Achieved reliable voltage regulation across various applications through precise PWM control.

### 4. Testing and Validation
- **CCM Operation:** Verified the converter's operation in Continuous Conduction Mode by observing the switch current and diode voltage waveforms.
- **DCM Demonstration:** Demonstrated Discontinuous Conduction Mode by reducing the switching frequency and observing the corresponding waveforms.
- **Performance Evaluation:** Recorded and analyzed waveforms to ensure the converter met the specified performance criteria.

## Results and Observations
- Successfully converted a 10V input to a stable 7.5V output with an output current of 1A.
- Demonstrated effective control and operation in both CCM and DCM.
- The TL494 module provided precise PWM control, ensuring efficient and reliable performance of the buck converter.

## Conclusion
This project effectively showcased our ability to design, implement, and test a DC-DC buck converter using the TL494 module. The experience gained from this project will be valuable for future endeavors in power electronics and control systems.

