# Hi, I'm Siddharth 👋

🔌➡️🧠 Recovering power-systems engineer, currently teaching very small computers to have opinions.

My day job is wiring up substations — relays, IEC 61850, the kind of hardware that trips a breaker if you look at it wrong. Then I found out you can fit a neural network on a chip smaller than a coin, and I have not been the same since. So now I'm learning **embedded AI / TinyML in public**, one confused commit at a time.

> Recent achievement: trained a 2,113-parameter neural net to spot a faulty signal. Its only real mistake was occasionally calling a broken thing "normal." Honestly? Relatable.

I'm not the 10x-from-scratch-kernel-hacker type and I've stopped pretending to be — I'm a domain nerd who ships things, breaks them, and reads the traceback out loud like it owes me money. It's working out better than the pretending did.

---

## 🧪 Things I've built (and what I learned by breaking them)

⚡ **[esp32-signal-fault-mlp](https://github.com/Sid3548/esp32-signal-fault-mlp)** — *the new one I'm actually proud of*
Taught a ~2 KB neural net to tell a healthy sine wave from a sick one, squished it to int8 so it fits on an ESP32, and ran it in [Wokwi](https://wokwi.com) because I respect real hardware too much to let the magic smoke out. Honest artifact, synthetic data, zero hype — I even documented the part where it's *simulated* instead of quietly hoping nobody asks.

🔋 **IEC 61850 DR Processor** — [libiec61850 fork](https://github.com/Sid3548/libiec61850)
When a protective relay trips, this grabs and processes the disturbance-record oscillography automatically. Real substation automation, real "please don't crash during a fault" energy.

🎓 **[Open Classroom](https://openclassroom.online)** — [repo](https://github.com/Sid3548/openclassroom-open)
A multi-agent AI classroom: a professor, a TA, a student, and a debater arguing on a live whiteboard. Bring-your-own-key across Claude / GPT / Gemini. Somehow live, with actual users.

🧭 **[Conductor](https://github.com/Sid3548/conductor)** — [t3code fork](https://github.com/Sid3548/t3code)
An auto-router over Claude Code, Codex, and Gemini CLIs. Basically: I built a manager so my AI agents could have a manager, because I clearly have unresolved delegation issues.

🔧 **Wire Clamp Connector — patent pending**
A one-piece 3D-printed relay-panel wire clamp, designed in Fusion 360, solving a genuinely annoying mechanical problem. Yes, an ML guy filed a hardware patent. No, I won't stop bringing it up.

<sub>🪦 Also in the drawer: [Claim It](https://claimit.shop) (AI insurance claims over WhatsApp, paused on regulation), [Wire-tracer](https://github.com/Sid3548/Wire-tracer), an [Interactive Paper Reader](https://github.com/Sid3548), and a [very small, frequently confused language model](https://github.com/Sid3548/SLM-) I built from scratch to understand what everyone else was talking about.</sub>

---

## 🛠️ Stack, sorted by emotional stability

**Things I trust:** Python · IEC 61850 (GOOSE/MMS) · Modbus · MATLAB/Simulink · Fusion 360
**Things I'm learning (loudly):** PyTorch · TinyML · quantization · embedded C · on-device inference
**Things I glue together at 2am:** FastAPI · React · Tailwind · Bun · multi-agent LLM pipelines
**Things that fully trust me:** the compiler, and even then only sometimes

---

## 🎓 The serious paragraph (hi Mom)

- **B.Tech, Electrical & Electronics** — VNR VJIET, Hyderabad (8.25/10, a number I mention more often than strictly necessary)
- **Control & Relay Panel Engineer** — Toshiba TTDI · substation automation, BESS, IEC 61850
- **Data Science Foundation** — IIT Madras
- **Next:** applying for an MS in embedded / edge AI (Europe, ~Fall 2027) — the long-game goal is building efficient AI for constrained hardware, ideally at my own company someday

---

## 📫 Say hi
[LinkedIn](https://linkedin.com/in/siddharth-j-246525201) · [Open Classroom](https://openclassroom.online) · or right here, mostly confused but always committing

<sub><i>currently: professionally puzzled by a microcontroller near you.</i></sub>
