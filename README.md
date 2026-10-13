# Hi, I'm Siddharth

Control System Engineer at Toshiba. Electrical engineer by degree, wrote a lot of software, came back to hardware, then fell into interpretability. Robotics is where it all meets.

Everything I've done keeps circling one problem: **if a model hasn't seen something before, how will it act?** That's all. It's a very simple problem.

You can't teach a model every single situation. A chatbot can say "I don't know". A robot can't — it has to do *something*. And the models that end up in robots won't be calling a cloud and waiting for an answer; they'll be small, sitting on the hardware, with very little compute to check themselves. That's the part I want to work on: embedded software, embedded hardware, and models that behave safely and predictably on stuff they were never trained on.

Next: master's in robotics / ECE, Fall 2027. I don't want to do the same old thing again and again. I want to understand systems and build new ones.

[Website](https://siddharth-j.com) · [LinkedIn](https://linkedin.com/in/siddharth-j-246525201)

---

## Papers

- **An Assurance Is Not Evidence: Answerability Claims Change What Agents Assert** — tells an LLM agent "this is answerable" and measures how it starts asserting unsupported answers instead of abstaining. *Being submitted to an AAAI 2027 workshop.*
- **[Decomposed Swarm Fusion (DSF): A Hypothesis for Multi-Axis Conceptual Fidelity Through Functionally Specialized Lightweight Networks](https://zenodo.org/records/20360400)** — single-author hypothesis paper. Instead of one big model holding every axis of meaning, a swarm of small specialised networks sharing one latent space. Predictions + falsification criteria, no experiments yet. Zenodo preprint, DOI [10.5281/zenodo.20360400](https://doi.org/10.5281/zenodo.20360400).
- **Capability degradation mapping** — [code](https://github.com/Sid3548/capability-relationship-map). Remove MLP neurons from a small language model task by task: when does a capability fall off a cliff, and what breaks along with it? Pilot + v2 done, write-up paused.

## Things I've built

**At Toshiba / power systems**
- **[DR Collector — IEC 61850](https://github.com/Sid3548/libiec61850)** — Toshiba wanted a cheaper in-house disturbance recorder instead of buying one. Task landed on me. Built it in C on libIEC61850: relay trips, stores the record, the workstation pulls the COMTRADE files over MMS automatically, with reconnect handling.
- **[Wire-tracer](https://github.com/Sid3548/Wire-tracer)** — phase one of automating our cable schedules: read the wiring straight out of the PDF drawings instead of tracing it by hand.
- **AI agent at work** — asks an engineer when it's unsure instead of inventing an answer. That rule had to be built in; rechecking everything yourself is doing the whole problem again. (Internal, can't share.)
- **CONNECTOR-02** — one-piece wire-clamp connector for relay panels, designed in Fusion 360. Indian provisional patent filed May 2026.

**Embedded AI**
- **[esp32-signal-fault-mlp](https://github.com/Sid3548/esp32-signal-fault-mlp)** — ~2 KB int8 neural net that tells a healthy signal from a faulty one on an ESP32. Simulated in Wokwi, synthetic data, and it says so.

**Learning the internals**
- **[ARENA](https://github.com/Sid3548/ARENA_materials)** — working through the interpretability curriculum. Own ResNet-34 matches torchvision's predictions; transformers next.
- **[SLM-](https://github.com/Sid3548/SLM-)** — built a small language model from scratch, just to see what everyone was talking about.

**Other stuff**
- **[Conductor](https://github.com/Sid3548/conductor)** — routes my work between Claude Code, Codex and Gemini CLIs depending on the task.
- **[GeoOSINT-GLOBE](https://github.com/Sid3548/GeoOSINT-GLOBE)** — 3D globe with seven live feeds: satellites, aircraft, ships, earthquakes, wildfires, weather, cameras.
- **[PDF-Studio](https://github.com/Sid3548/PDF-Studio)** — PDF editor in Flask, with tests.
- **[event-intel](https://github.com/Sid3548/event-intel)** — for capturing contacts and notes at conferences.
- **[Open Classroom](https://github.com/Sid3548/openclassroom-open)** — multi-agent AI classroom from a PDF or a topic.

---

## How I got here
- **Advance Auto Parts (intern, 2024)** — first time working with models for real. They couldn't get enough test data. We tried four or five GAN models for about 40 days, none worked, then changed the model itself and it clicked: CTGAN took 10,000 rows to 100,000 coherent ones.
- **Accenture (Oct 2024 – Mar 2025)** — put in financial analysis. Not my thing. Left.
- **Toshiba (May 2025 – now)** — joined in Transformers, came second in an internal ideation competition on digital substation monitoring, moved to control & relay panels / substation automation. SAS architecture, IEC 61850, a lot of talking to customers and vendors, and the guy who tries the new AI tools.

**Education:** B.Tech EEE, VNR VJIET Hyderabad, 2024 (8.25/10, First Class with Distinction) · IIT Madras BS Data Science, Foundation level

**Tools:** Python · PyTorch · C · IEC 61850 (MMS/GOOSE) · Modbus · MATLAB/Simulink · Fusion 360 · TypeScript/React · FastAPI
