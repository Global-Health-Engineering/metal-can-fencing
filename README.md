# metal-can-fencing

# ALuminium Can Wire Prototype
**Semester Project — Global Health Engineering, ETH Zürich**

The repo contains the project files of a prototype machine for turning waste aluminium cans into wire intended to be used for fencing. A detailed description of the project background can be found in the proposal document. The CAD model is available both as .stl files and as a public Onshape document. A video demonstrating the prototype is available on YouTube.

---

## Video Demonstration

A full step-by-step video guide on how to build the pasteuriser is available on YouTube:

👉 **[Watch the build video](https://youtu.be/TXo4oEJUX8o?si=pCioiJgCkVSB-7HL)**

---

## Repository Structure

```
├── data/
│   ├── raw/              # Raw sensor readings from all 8 experiments (CSV)
│   └── derived/          # Cleaned and processed data (Excel)
│
├── docs/
│   ├── report/           # Final semester report
│   ├── build/            # Step-by-step build instructions
│   └── parts_list.xlsx   # Full parts list + simplified build version
│
├── src/
│   ├── arduino_code.ino  # Arduino monitoring code
│   └── serial_logger.py  # Python script for serial data logging
│
├── hardware/
│   └── wiring_diagram.pdf  # Arduino wiring schematic
│
└── README.md
```

---

## Data

The `data/raw/` folder contains sensor data collected across 8 pasteurisation experiments carried out in April 2026. Each experiment folder includes temperature readings from RuuviTag sensors and manual measurements.

The `data/derived/` folder contains the cleaned and consolidated dataset used for analysis.

> For any additional data or materials not included in this repository, feel free to reach out (see contact below).

---

## Hardware

The pasteuriser uses a gas burner system monitored via an Arduino with temperature sensors. The `hardware/` folder contains the wiring diagram and the `docs/build/` folder contains the full build instructions.

A simplified parts list for a basic build is included in `docs/parts_list.xlsx`.

---

## Software

- **Arduino**: The `src/arduino_code.ino` file runs on the Arduino and monitors temperature during pasteurisation.
- **Python**: The `src/serial_logger.py` script logs serial output from the Arduino to CSV files.

---

## Contact

**Carlos Martín Cazorla**
Semester project student, Global Health Engineering group, ETH Zürich

For questions or to request additional project files, please open an issue in this repository or contact through ETH Zürich.

---

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](LICENSE.md).
