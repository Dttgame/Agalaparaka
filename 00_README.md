# Agalaparaka

AI-powered non-invasive throat wearable using sEMG signals for real-time speech restoration.


## Problem

Many individuals who lose their voice due to medical conditions (such as laryngeal cancer, vocal cord paralysis, or throat injuries) lose the ability to communicate naturally. Existing solutions are limited, expensive, or produce unnatural robotic voices, leading to social isolation and reduced quality of life.


## Solution

Agalaparaka is a wearable AI system that detects throat muscle activity (sEMG signals) from subvocal speech and converts it into real-time spoken words or text, enabling natural communication without vocal cords.


## How it works

1. Surface electrodes capture sEMG signals from throat muscles  
2. Signals are filtered to remove noise (breathing, swallowing, movement)  
3. AI model processes patterns of muscle activity  
4. Predicted words are generated in real time  
5. Output is played through a speaker or displayed as text


## Features

- Non-invasive wearable design  
- Real-time speech decoding  
- Subvocal (silent) speech recognition  
- Offline processing (no internet required)  
- Designed for Georgian language adaptation


## Technology

- sEMG (surface electromyography) sensors  
- Lightweight neural networks  
- ESP32-S3 microcontroller (planned)  
- Signal filtering (bandpass 20–500 Hz)  
- Python for model development


## Status

This project is currently in research and early prototype development stage.


## Future work

- Build Georgian sEMG dataset  
- Improve model accuracy and vocabulary size  
- Develop wearable prototype  
- Optimize real-time performance  
- Expand to full sentence recognition


## Impact

This project aims to restore communication ability and improve quality of life for individuals with speech loss, supporting both medical accessibility and social inclusion.






