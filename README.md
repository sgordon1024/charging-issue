# Case Study: Nations 48V + Wakespeed WS500 stopped charging — failed alternator temp sensor

2024 Entegra Launch (Sprinter) · Lithionics 51V · Victron Cerbo GX · **Resolved**

**[Read the full case study](https://sgordon1024.github.io/charging-issue/)** — root-cause analysis, what every system showed during the failure, the 10-minute diagnostic path, dead ends to skip, measurements, and serial evidence.

TL;DR: WS500 **fault 42** ("required sensor missing", alt-temp field `-99`) = the alternator temperature sensor failed **open** — likely thermal fatigue at the alternator-case mount after repeated 4-5 kW summer charging sessions. One thermistor + one ignition cycle = charging restored at 4.4 kW.

Files:
- `index.html` — the case study (served via GitHub Pages)
- [`ws500-evidence-for-nations.txt`](ws500-evidence-for-nations.txt) — plain-text evidence pack
- `ws500-capture-*.log` — raw WS500 serial capture
