# M490C · Input Pre Amps

Ward-Beck Systems M490C, 1978|11. Wiki page: [M490C on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M490C.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 5 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 1 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 5 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 20 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 0 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 2 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 23 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [5 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1978 - M490C - 004.jpg](MANUALS/1978%20-%20M490C%20-%20004.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Input sensitivity** | -10 to +20 dBm (ref_ 600 ohm source) |
| **Frequency response** | ±0.5 dB from 30 Hz to 20 kHz |
| **Noise** | 70 dB be ]ow nomina ] operating level _ with SENSITIVITY set at -10 dBm, mixing attenuator set at 15 dB in-hand (20 Hz to 20 kHz) Noise decreases a $ SENSITIVITY is decreased |
| **Harmonic distortion** | Less than 0.35 % from 30 Hz to 20 kHz at 20 dB above nomina] operating Teve 1 or Tess Less than 0.1% at kHz at 20 dB above nomina operating level or Tess _ Less than 0.5% at kHz through cue channel at 20 dB above nomina operating level or Tess |
| **Source impedance** | 600 ohms or Tess, balanced/unbalanced. |
| **Input impedance** | 24,000 ohms |
| **Output impedances** | 30,000 ohms = baLanced (program circuits) 60,000 ohms balanced (cue circuits) _ Output Leve] dBm nomi na ] +25 dBm maximum (equivalent voltage 600 ohms) _ Input and output terminals designated by numbers are in phase, or Tower number of numbered pa jr is in phase with lower number of other numbered pair |
| **Phasing** |  |
| &nbsp;&nbsp;Input levels | (to operate ch On, Ch 0FF Logic to +13 volts_ Logic 1: +16 to +24 volls_ Externa] Contro] Output: (Open collector currents ink.) |
| **Minimum load impedance** | Maximum Toad current: 600 ohms 40 mA |

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSnVyV2JRTVZyS0U/view?resourcekey=0-avCx5WSV-x9_NvDhLnb4Bw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSnVyV2JRTVZyS0U&resourcekey=0-avCx5WSV-x9_NvDhLnb4Bw" width="240" alt="1978 - M490C - Front Panel.jpg"></a><br><sub>1978|11 · Front Panel</sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M490C.stl`](MECHANICAL/M490C.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M490C)

- **Size:** 43.18 × 266.85 mm panel, 165 mm deep, 3.2 mm plate (the drawing sheet, taken as drawn 1:1)
- **From the drawing:** 10 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M490C - front panel.svg`)
- the drawn panel is 0.11 wide to high, the size 0.16: placed by its height
- Made by `tools/module_models.py` (→ `MECHANICAL/M490C.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWFVwVkFPd3drYjQ/view?resourcekey=0-jUomaHqCxkOU3rZN4ASjFQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWFVwVkFPd3drYjQ&resourcekey=0-jUomaHqCxkOU3rZN4ASjFQ" width="240" alt="1978 - M490C - 490-02-004 - ADDED CEB ENG.jpg"></a><br><sub>1978|11 · 490-02-004 - ADDED CEB ENG · <a href="SCHEMATICS/1978%20-%20M490C%20-%20490-02-004%20-%20ADDED%20CEB%20ENG%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaXJqOHZPNlBaLTQ/view?resourcekey=0-TyYXM8yuVGsO7p_qeeNjPw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaXJqOHZPNlBaLTQ&resourcekey=0-TyYXM8yuVGsO7p_qeeNjPw" width="240" alt="1978 - M490C - Functional.jpg"></a><br><sub>1978|11 · Functional</sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M490C - RTO-144 Connections.pdf`

## RTO-144 pinout

4 contacts (P1), 22 contacts (P2). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 | LEFT PGRM 1 | audio | A3 + | high |
| 1 | MIC IN A | in | A1 + | high |
| 2 | LEFT PGRM 1 | audio | A3 - | high |
| 3 | RIGHT PGRM 1 | audio | A4 + | high |
| 3 | MIC IN B | in | A2 + | high |
| 4 | RIGHT PGRM 1 | audio | A4 - | high |
| 5 |  | unread |  | low |
| 6 | INSERT SEND | out | B1 + | high |
| 7 | INSERT RETURN | in | B2 + | high |
| 12 |  | unread |  | low |
| 13 |  | unread |  | low |
| 15 |  | unread |  | low |
| 17 |  | unread |  | low |
| 18 |  | unread |  | low |
| 19 | -25 V | power |  | high |
| 20 | COMMON | ground |  | high |
| 21 | +25 V | power |  | high |
| 22 |  | unread |  | low |
| A | MIC IN A | in | A1 - | high |
| C | MIC IN B | in | A2 - | high |
| E |  | unread |  | low |
| F | INSERT SEND | out | B1 - | high |
| H | INSERT RETURN | in | B2 - | high |
| N |  | unread |  | low |
| P |  | unread |  | low |
| V |  | unread |  | low |

**Straps:** Insert: JMP.6.7 · Insert: JMP.F.H

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbnh3R1BjVVBtbTg/view?resourcekey=0-KRssSwHg4m5RCUQ6xdJIjA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbnh3R1BjVVBtbTg&resourcekey=0-KRssSwHg4m5RCUQ6xdJIjA" width="240" alt="1978 - M490C - 000 - cover.jpg"></a><br><sub>1978|11 · 000 - cover</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRGNCelEzUXBsLVU/view?resourcekey=0-myWW7PuPzQMCAmVCUtV-lQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRGNCelEzUXBsLVU&resourcekey=0-myWW7PuPzQMCAmVCUtV-lQ" width="240" alt="1978 - M490C - 001.jpg"></a><br><sub>1978|11 · 001</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNVBtNlk5U1lseWM/view?resourcekey=0-zy09ElYRootjxrNxxTVBjw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNVBtNlk5U1lseWM&resourcekey=0-zy09ElYRootjxrNxxTVBjw" width="240" alt="1978 - M490C - 002.jpg"></a><br><sub>1978|11 · 002</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKczJtRnEtWDRPdHM/view?resourcekey=0-UQDlW8lpxYsEQ3bIMYAkGA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKczJtRnEtWDRPdHM&resourcekey=0-UQDlW8lpxYsEQ3bIMYAkGA" width="240" alt="1978 - M490C - 003.jpg"></a><br><sub>1978|11 · 003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeEs4enhNbVF1aTQ/view?resourcekey=0-7wkxb5lJ36XMwmxTbqsBPA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeEs4enhNbVF1aTQ&resourcekey=0-7wkxb5lJ36XMwmxTbqsBPA" width="240" alt="1978 - M490C - 004.jpg"></a><br><sub>1978|11 · 004</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTUVTRTlnV0lNbTg/view?resourcekey=0-BQtn8Rmr0Z8kbUCHI9XAuQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTUVTRTlnV0lNbTg&resourcekey=0-BQtn8Rmr0Z8kbUCHI9XAuQ" width="240" alt="1978 - M490C - 005.jpg"></a><br><sub>1978|11 · 005</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVUZJZWFpaGx5Rjg/view?resourcekey=0-1pXjQIHQrtcnlwQ1sqbmBA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVUZJZWFpaGx5Rjg&resourcekey=0-1pXjQIHQrtcnlwQ1sqbmBA" width="240" alt="1978 - M490C - 006.jpg"></a><br><sub>1978|11 · 006</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMzJrS2dyUTFhcGc/view?resourcekey=0-NGjgPP0emXiY861tBRmmeg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMzJrS2dyUTFhcGc&resourcekey=0-NGjgPP0emXiY861tBRmmeg" width="240" alt="1978 - M490C - 007.jpg"></a><br><sub>1978|11 · 007</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZGxvMGNOT1l2QjA/view?resourcekey=0-AUlMYNoqM1wQlL-ruQ2puQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZGxvMGNOT1l2QjA&resourcekey=0-AUlMYNoqM1wQlL-ruQ2puQ" width="240" alt="1978 - M490C - 008.jpg"></a><br><sub>1978|11 · 008</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcGtBUk5DOUxXd00/view?resourcekey=0-NX7d_xcsxLw78Wz-V519GQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcGtBUk5DOUxXd00&resourcekey=0-NX7d_xcsxLw78Wz-V519GQ" width="240" alt="1978 - M490C - 009.jpg"></a><br><sub>1978|11 · 009</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSUNCRmE2ckUtRDQ/view?resourcekey=0-nkF_PPrdw-Iyz8lfNtVvNQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSUNCRmE2ckUtRDQ&resourcekey=0-nkF_PPrdw-Iyz8lfNtVvNQ" width="240" alt="1978 - M490C - 010.jpg"></a><br><sub>1978|11 · 010</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWXpjQ3laMVNwY1E/view?resourcekey=0-SKD7EU1F0n--o21wTfZ0AQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWXpjQ3laMVNwY1E&resourcekey=0-SKD7EU1F0n--o21wTfZ0AQ" width="240" alt="1978 - M490C - 011.jpg"></a><br><sub>1978|11 · 011</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKczF1aGdURjRxQzg/view?resourcekey=0-eznQJCQQdFW9UGybqLiy3g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKczF1aGdURjRxQzg&resourcekey=0-eznQJCQQdFW9UGybqLiy3g" width="240" alt="1978 - M490C - 012.jpg"></a><br><sub>1978|11 · 012</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSk5VZkhBTm1kbDA/view?resourcekey=0-fpS9AfxbdQ_StqtUcotEBw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSk5VZkhBTm1kbDA&resourcekey=0-fpS9AfxbdQ_StqtUcotEBw" width="240" alt="1978 - M490C - 013.jpg"></a><br><sub>1978|11 · 013</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS2xJY01YaDFoNms/view?resourcekey=0-RX-z8ZpWPuo1IEtaVLa_vw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS2xJY01YaDFoNms&resourcekey=0-RX-z8ZpWPuo1IEtaVLa_vw" width="240" alt="1978 - M490C - 014.jpg"></a><br><sub>1978|11 · 014</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb2wxSTYwNDlxTFE/view?resourcekey=0-D8nwDL6Z_yO6sL4UTEJfHg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb2wxSTYwNDlxTFE&resourcekey=0-D8nwDL6Z_yO6sL4UTEJfHg" width="240" alt="1978 - M490C - 015.jpg"></a><br><sub>1978|11 · 015</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRnRLUlBBQS0zMUE/view?resourcekey=0-TTskbDuQ_R0iDnLaaP4iIQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRnRLUlBBQS0zMUE&resourcekey=0-TTskbDuQ_R0iDnLaaP4iIQ" width="240" alt="1978 - M490C - 016.jpg"></a><br><sub>1978|11 · 016</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRWt0RjZLcUZ4b2M/view?resourcekey=0-6zndzBxpaqYSTUdulBrwSw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRWt0RjZLcUZ4b2M&resourcekey=0-6zndzBxpaqYSTUdulBrwSw" width="240" alt="1978 - M490C - 018.jpg"></a><br><sub>1978|11 · 018</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTm1ZTGRwbkVNZ3c/view?resourcekey=0-Q4DTQE9xTFaVP24FsY2uMQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTm1ZTGRwbkVNZ3c&resourcekey=0-Q4DTQE9xTFaVP24FsY2uMQ" width="240" alt="1978 - M490C - 019.jpg"></a><br><sub>1978|11 · 019</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1978|11 · 017](https://drive.google.com/file/d/0B0yR0b5T78SKWFJHMjhBNmlFdDA/view?resourcekey=0-cxZ1iFTdaCyGnUlCJUAbtA)

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1978 - M490C - 490-02-004 - ADDED CEB ENG.kicad_sch](KICAD/1978%20-%20M490C%20-%20490-02-004%20-%20ADDED%20CEB%20ENG.kicad_sch)
- [M490C.kicad_sym](KICAD/M490C.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
