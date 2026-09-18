# Voice Recognition Research

## Project Objective

This project investigates speaker recognition using recorded voice samples from multiple speakers.

The system extracts acoustic features from speech recordings and uses a machine learning model to identify the speaker.

## Dataset

The dataset contains voice recordings from three speakers:

- ST001_Tharushi
- ST002_Malshi
- ST003_Tharusha

Each speaker has 3 recording sessions, with 3 WAV files per session.

Total recordings: 27 WAV files.

## Dataset Structure

```text
dataset/
├── ST001_Tharushi/
│   ├── session_01/
│   ├── session_02/
│   └── session_03/
├── ST002_Malshi/
│   ├── session_01/
│   ├── session_02/
│   └── session_03/
└── ST003_Tharusha/
    ├── session_01/
    ├── session_02/
    └── session_03/
