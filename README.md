# Bread Board Power Supply (KiCad 9)

Compact breadboard-compatible power supply PCB designed in KiCad 9 for quick prototyping on standard solderless breadboards.

## Status
- KiCad version: 9.0
- Prototype status: Prototype built
- Files included: schematics, PCB layout, Gerbers, BOM, documentation

## Preview
<img width="1115" height="763" alt="Screenshot 2025-12-05 214350" src="https://github.com/user-attachments/assets/78462620-73d9-4221-b1df-619d560feddb" />
<img width="1919" height="1018" alt="Screenshot 2025-12-06 191623" src="https://github.com/user-attachments/assets/7f6bd5ac-44ce-4671-9207-e68af765f398" />
<img width="1724" height="992" alt="Screenshot 2025-12-05 214451" src="https://github.com/user-attachments/assets/a4909c31-fd7b-46f6-b303-f47505813859" />
<img width="1919" height="1022" alt="Screenshot 2025-12-05 214550" src="https://github.com/user-attachments/assets/f961d7e3-572b-42d5-be14-7dcc5d456d0c" />




## Key features
- Breadboard-compatible footprint
- 5V Output voltage
- Adjustable or additional rails:3.3 V 
- Short-circuit / thermal protection:
- Compact form factor suitable for prototyping

## Specifications
- Input voltage: 7–12 V DC
- Output voltage(s): 5 V, 3.3 V
- Maximum output current:up to 1 A
- Board dimensions:
- Connector types: 

## Repository layout
- Bread_Board_Power_Supply001.kicad_pro  — KiCad project file
- Bread_Board_Power_Supply001.kicad_sch  — Schematic
- Bread_Board_Power_Supply001.kicad_pcb  — PCB layout
- Gerber_Files/                          — Gerber files for fabrication
- LICENSE                                — Project license (see LICENSE file)
- README.md                              — This file

## Getting started
1. Install KiCad 9.x and open Bread_Board_Power_Supply001.kicad_pro.
2. Review the schematic and footprints; verify design rules.
3. Generate fabrication files: File → Plot (Gerber) and drill files.
4. Inspect BOM located in the repository (add path when available).

## Manufacturing & assembly
- Gerbers: check Gerber_Files/ before sending to your PCB house.
- BOM: add part numbers, package types and vendor links in the BOM folder.
- Assembly notes:
  - Follow polarity markings for electrolytic capacitors, diodes, and regulators.
  - Hand-solder or use reflow for SMDs depending on your workflow.

## Testing procedure
1. Visual inspection for solder bridges and component orientation.
2. Continuity test between power rails and ground.
3. Power the board with a current-limited supply and verify output voltages with a multimeter before connecting loads.
4. Verify thermal behavior under expected load.
5. Record test results in docs/test-report.md.

## Safety & disclaimer
- Use appropriate current limiting when powering a newly assembled board.
- Confirm correct polarity of the input connector.
- This design is provided as-is. The author is not responsible for damage from improper use. Verify suitability for your application.

## Contributing
Contributions are welcome. Please:
1. Fork the repository.
2. Create a descriptive feature branch.
3. Submit a pull request with a detailed explanation of changes and test results.

When contributing PCB changes, include updated KiCad files, BOM updates, and test logs.

## License
See the LICENSE file in this repository for license details.

## Contact
Maintainer: YUKESH0620
GitHub: https://github.com/YUKESH0620

## Changelog
- v0.1 — Initial KiCad 9 design and repository (update as needed)

---

Note: Many values above are placeholders. Replace bracketed placeholders with verified specifications, images, BOM links, and test reports before manufacture.
