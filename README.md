# Analog Front End (AFE) for Biopotential Signal Sensing

This repository presents the design, development, and implementation of an Analog Front End (AFE) tailored for biopotential signal sensing. Leveraging CADENCE VIRTUOSO, the AFE circuitry interfaces with biological signals such as electrocardiograms (ECG), electroencephalograms (EEG), and electromyograms (EMG). This project underscores the pivotal role of AFEs in bridging the gap between biological phenomena and digital signal processing, thus fostering applications in healthcare diagnostics and physiological monitoring.

## Introduction

The Analog Front End (AFE) for biopotential signal sensing project entails the creation of a circuitry framework capable of capturing and amplifying biopotential signals with precision. The AFE serves as an intermediary between the biological signal and digital processing systems, contributing to the extraction of valuable insights for medical diagnosis and analysis.
![image](https://github.com/aaronghosh/ANALOG-FRONT-END/assets/124378527/90825186-4787-40f6-aa6a-fef5b49a2eef)

## Scope

The scope of this project encompasses the design, prototyping, and rigorous evaluation of an AFE circuit tailored to detect and amplify biopotential signals. Key considerations include noise suppression and interference mitigation, ensuring the fidelity of the biological signal. The circuit will be realized using a 180nm CMOS process, boasting a gain of 100 V/V and a supply voltage of 1.8 V.

## Design Methodology

The AFE is constructed using CMOS design principles, capitalizing on its inherent advantages:
- Low Power Consumption
- High Speed
- Low Noise
- High Reliability
- Compact Form Factor
- Seamless Integration

## Design Constraints

The AFE design adheres to stringent constraints, encompassing both operational amplifiers and the overarching AFE architecture. These constraints include:
- Gain-Bandwidth Product
- Input Offset Voltage
- Common-Mode Rejection Ratio (CMRR)
- Slew Rate
- Overall Gain
- Noise
- Bandwidth
- Power Efficiency
- Sensitivity

## Methodology

The design process unfolds through systematic stages, featuring:
1. **Operational Amplifier Design**: Foundational opamp design, forming the bedrock of the AFE architecture.
2. **Instrumentation Amplification**: Opamp utilization to engineer an Instrumentation Amplifier, optimizing signal extraction.
3. **Precision Filtering**: Implementation of custom high-pass and low-pass filters for signal fidelity.
4. **Variable Gain Amplification**: Introduction of adaptable Variable Gain Amplification, facilitating manual or automatic signal amplification.
5. **ADC Integration**: Incorporation of an Analog-to-Digital Converter (ADC) to transition analog signals into the digital domain.

