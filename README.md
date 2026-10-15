<h1 align="center">📞 Cloud Telephony Integration Platform</h1>
<p align="center"><b>Scalable CTI & Voice Streaming Integration Gateway</b></p>

## Overview
A high-throughput cloud telephony and CTI (Computer Telephony Integration) connector engine built to bridge VoIP/SIP dialers with real-time AI voice agents. Supports WebSocket PCM audio streaming, concurrent call scheduling, and latency-optimized call dispatch.

## Features
- **Real-Time Audio Streaming:** Low-latency bi-directional WebSocket streaming for speech-to-text (Whisper) and text-to-speech pipelines.
- **Concurrency & Rate Limiting:** Dynamic batch scheduling respecting GPU capacity constraints (500+ concurrent calls).
- **Call State Management:** Robust event hooks for ring, answer, DTMF, hold, and disposition logging.

## Tech Stack
- Python, FastAPI, WebSockets, SIP, Asterisk / FreeSWITCH CTI, Docker, AWS
