# Siddharth Janapareddy

**Control System Engineer at Toshiba · robust AI for robots and embedded systems**

One question runs through my work: *when a system meets something it has never seen, how should it act?*
At Toshiba I built an AI agent that asks an engineer when it is unsure instead of guessing. On my own I study why models behave as they do (mechanistic interpretability) and how small models run on embedded hardware, where there is no cloud to fall back on. Next: a master's in robotics / ECE (Fall 2027), because a robot cannot stop to ask — it still has to act.

[Website](https://siddharth-j.com) · [LinkedIn](https://linkedin.com/in/siddharth-j-246525201)

---

## Projects

### Research & interpretability
| Project | What it is |
|---|---|
| [capability-relationship-map](https://github.com/Sid3548/capability-relationship-map) | How far can you remove MLP neurons from a small language model before a capability breaks — and what happens to the other capabilities when you do? Task-conditioned ablation experiment. |
| [DSF — Decomposed Swarm Fusion](https://zenodo.org/records/20360400) | Single-author hypothesis paper (Zenodo, DOI 10.5281/zenodo.20360400): a swarm of small, functionally specialised networks sharing one latent space, with testable predictions and falsification criteria. |
| [ARENA_materials](https://github.com/Sid3548/ARENA_materials) | Working through the ARENA curriculum — tensors, CNNs/ResNets (own ResNet-34 matching torchvision), then transformers and interpretability. |
| [SLM-](https://github.com/Sid3548/SLM-) | A small language model built from scratch to understand the internals. |

### Embedded AI / TinyML
| Project | What it is |
|---|---|
| [esp32-signal-fault-mlp](https://github.com/Sid3548/esp32-signal-fault-mlp) | ~2 KB int8 neural network that tells healthy signals from faulty ones on an ESP32 (simulated in Wokwi; synthetic data, documented as such). |

### Power systems & industrial automation
| Project | What it is |
|---|---|
| [DR Collector — libiec61850](https://github.com/Sid3548/libiec61850) | C tool on libIEC61850/MMS that subscribes to relay reports and automatically downloads COMTRADE disturbance records, with reconnect handling. |
| [Wire-tracer](https://github.com/Sid3548/Wire-tracer) | Reads and traces wiring in electrical engineering drawings (PDF), automating manual wire reading. |
| **CONNECTOR-02** (patent) | One-piece wire-clamp connector for relay panels, designed in Fusion 360. Indian provisional patent application filed May 2026. |

### AI agents & software
| Project | What it is |
|---|---|
| [Conductor](https://github.com/Sid3548/conductor) | Orchestrator that routes tasks between Claude Code, Codex and Gemini CLIs by task type. |
| [GeoOSINT-GLOBE](https://github.com/Sid3548/GeoOSINT-GLOBE) | Real-time 3D globe fusing seven live feeds (satellites, aircraft, ships, earthquakes, wildfires, weather, cameras). React, FastAPI, PostGIS, TimescaleDB, CesiumJS. |
| [PDF-Studio](https://github.com/Sid3548/PDF-Studio) | Flask PDF editor: interactive text editing, page operations, conversion, security tools, automated tests. |
| [event-intel](https://github.com/Sid3548/event-intel) | Captures contacts, notes and insights at conferences. Next.js. |
| [Open Classroom](https://github.com/Sid3548/openclassroom-open) | Multi-agent AI classroom generated from PDFs or topics (professor, TA, students on a shared whiteboard). |

<sub>Private: native SwiftUI health tracker with an on-device food model; interactive paper reader that turns static paper figures into interactive ones.</sub>

---

## Experience
- **Toshiba (TTDI), Hyderabad** — Control System Engineer, *Sep 2025 – present*: substation automation system (SAS) architecture, control & relay panels, IEC 61850; the department's go-to person for trying new AI tools. Joined May 2025 in Transformers; moved to SAS after placing second in an internal ideation competition on digital substation monitoring.
- **Accenture** — Associate Software Engineer, *Oct 2024 – Mar 2025*.
- **Advance Auto Parts India** — IT Intern, *2024*: CTGAN-based synthetic data framework with a Streamlit front end.

## Tools
Python · PyTorch · C (embedded, int8 inference) · IEC 61850 (MMS/GOOSE) · Modbus · MATLAB/Simulink · Fusion 360 · TypeScript / React / Next.js · FastAPI · PostgreSQL

## Education
- **B.Tech, Electrical & Electronics Engineering** — VNR VJIET, Hyderabad (2024) · CGPA 8.25/10 · First Class with Distinction
- **IIT Madras** — BS in Data Science, Foundation level
