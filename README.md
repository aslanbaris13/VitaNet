# VitaNet 🌐

> **Autonomous Agentic Crisis Management Network**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-000000?style=flat)
![Whisper](https://img.shields.io/badge/Whisper_Edge-412991?style=flat&logo=openai&logoColor=white)
![BLE](https://img.shields.io/badge/BLE_Mesh-0082FC?style=flat&logo=bluetooth&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concept%2FIdeathon-orange?style=flat)
![Award](https://img.shields.io/badge/AI4Change_Ideathon-🏆_1st_Place-gold?style=flat)

---

## Overview

VitaNet transforms a standard smartphone into an **autonomous crisis agent** — operating entirely offline via mesh networking, processing voice and text on-device, and directing rescue teams with actionable commands instead of passive maps.

> 🏆 **1st Place** — Kodluyoruz AI4Change Ideathon, 6th Term (2025)  
> 4-person team. Presented at final ideathon jury.

---

## Problem Statement

On February 6 at 04:17, billion-dollar infrastructure collapsed. Smartphones became flashlights.

- **48 hours** — critical "Golden Hours" for survival
- **80% delay** — caused by manual data processing
- **0 communication** — when cell towers go down

> *"The real disaster isn't the destruction — it's the silence."*

---

## How It Works: 3-Layer Architecture

```
Layer 1 — Offline Mesh Network
  Protocol: BLE (Bluetooth Low Energy) + Wi-Fi Direct
  Range: 5-7 hops (~500m coverage)
  Security: AES-256 End-to-End Encryption
  Power: Heartbeat Ping (no continuous scan → battery savings)
  
  [Victim] → [Bridge] → [Bridge] → [Bridge] → [Rescue Team]

Layer 2 — Edge AI & Multimodal Analysis
  Whisper STT (Quantized INT8, ~40MB) → speech to text
  Multimodal SER → detects fear and urgency from voice tone
  LangChain Agent → classifies, prioritizes, decides locally
  
  No cloud. No central server. The device itself decides.

Layer 3 — Logistics & Stock Integration
  Offline routing: OpenStreetMap vector maps cached on device
  Stock awareness: regional depot inventory
  Result: Right team, right equipment, right location
```

---

## Key Differentiators

| Feature | Traditional | VitaNet |
|---|---|---|
| Internet | Required | **Zero / Mesh** |
| Decision | Waits for human operator | **Autonomous Agent** |
| Routing | Google Maps (online) | **OSM Offline Cache** |
| Emotion Analysis | None | **Voice + Text (Multimodal)** |
| Task Assignment | Passive map | **Direct Command ("Ahmet, go there")** |

---

## Tech Stack

| Layer | Technology |
|---|---|
| Mobile App | Flutter |
| Mesh Network | BLE + Wi-Fi Direct |
| Speech-to-Text | Whisper (quantized, on-device) |
| Emotion Recognition | Multimodal SER (audio + text) |
| Agent Orchestration | LangChain |
| Offline Maps | OpenStreetMap (cached) |
| Security | AES-256 E2EE |

---

## Risk & Mitigation

| Risk | Solution |
|---|---|
| Battery drain | BLE Deep Sleep (no continuous scanning) |
| Misrouting | Human-in-the-Loop (autonomous only at >90% confidence) |
| Scalability | Priority packet queue |

---

## Business Model

- **MVP operational cost: ~$0** — citizen's phone, open-source AI, BLE+Wi-Fi infrastructure
- Cloud services: pay-as-you-go only when connectivity is restored
- Roadmap: AFAD pilot → logistics integration → national-scale pre-crisis inventory optimization

---

## Team

| Name | Background |
|---|---|
| **Barış Aslan** | 
| Ahmet Şamil Akgün | 
| Belemir Tonyalı |
| Rüveyda Özsoy |

---

## Status

🏆 **AI4Change 6th Term Ideathon — 1st Place (2025)**  
🗂️ Concept stage. Not yet in development.
