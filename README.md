# Telecommunications Radio Link Design: Sertã - Peral

## Project Overview
* This project details the complete dimensioning of a bidirectional digital radio link between Sertã and Peral, Portugal[cite: 1].
* The system was designed to transport an STM-1 signal with a transmission rate of 155 Mbit/s[cite: 1].
* The primary objective was to ensure reliability, service quality, and strict compliance with international ITU-R standards[cite: 1].

## Engineering Challenges & Solution Architecture
* **Initial Challenge:** A direct line-of-sight link was proven technically unviable due to severe terrain obstructions causing diffraction losses and highly negative critical margins[cite: 1].
* **Optimization Attempts:** Introducing a single passive repeater, and later two passive repeaters with frequency diversity, improved conditions but still failed to meet the required 3 dB critical margin for reliability[cite: 1].
* **Final Deployed Solution:** The link was successfully redesigned using an active repeater to divide the route into two shorter, independent sections[cite: 1]. 
* **Signal Protection:** The first section implemented frequency diversity with a 0.36 GHz carrier separation and adaptive equalization to mitigate selective fading[cite: 1]. 
* **Redundancy:** A 1+1 hardware redundancy configuration (utilizing 4 switches in total) was adopted to meet strict equipment availability requirements[cite: 1].

## Technical Specifications
* **Frequency Band:** 6 GHz[cite: 1].
* **Modulation:** 4-PSK (with a roll-off factor of 0.161)[cite: 1].
* **Antennas:** Parabolic antennas with a 1.5-meter diameter[cite: 1].
* **Mast Heights:** 13 meters for the terminal stations and 29 meters for the active repeater[cite: 1].
* **Software Used:** Feixer (for link budget and Fresnel zone simulations)[cite: 1].

## Performance & ITU-R Compliance
* The final optimized link achieved a critical margin of approximately 3 dB[cite: 1].
* The system successfully complies with ITU-R quality clauses, specifically meeting the required thresholds for SESR, BBER, ESR, and overall availability[cite: 1].
* A 25-year lifecycle cost analysis was also conducted to ensure the solution's economic viability[cite: 1].

## Authors
* Dinis Prata & Rafael Custódio (Grupo 14)[cite: 1].
* ISCTE - Instituto Universitário de Lisboa[cite: 1].
* *Full methodology and calculations are available in the attached "RelatórioPST_Grupo14.pdf".*
