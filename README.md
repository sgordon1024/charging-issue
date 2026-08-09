# Second Alternator Charging Issue — 2024 Entegra Launch

Diagnostic evidence for a Nations 48V engine generator + Wakespeed WS500 (Lithionics 51V system) that stopped charging.

- **[View the full diagnostic report](https://sgordon1024.github.io/charging-issue/)** (timeline, measurements, 7-day charging history)
- **[Download the evidence pack (txt)](ws500-evidence-for-nations.txt)** — plain-text summary + serial captures
- **Raw WS500 serial capture** — see the `ws500-capture-*.log` file in this repo

Current state: temp-sensor fault (42) fixed; WS500 fault-free and CAN-synced but delivers 0.0 A engine-running; feature-in (white wire) reads 0 V. Open question for Nations: is feature-in required-high in the 51V Lithionics program?
