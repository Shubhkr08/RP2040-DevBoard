# RP2040-DevBoard
I made a custom devboard based on RP2040 chip ,it has a USB type C  and the design utilizes most of its gpio pins , I did the Schematic and PCB design in Kicad and renders in Fusion.
## Overview
I started by looking at the guide project and did the schematics , choose the particular footprint as per guided and ended up with a proper schematics which acted as the base to the project,
then I started up with placing every particular components in a systematic way as (decoupling capacitors are close to there connected pins) as well as they are well arranged so that I don't have to deal with much problem while Routing afterwards. I kept a proper look to all components as they are placed in there specific area and has there required footprint, after that I Started with routing the PCB ,there were many problem that i came across like no space for rounding the wires, misconnection, no space for Via but i dealt with the problem, did multiple alterations while routing and ended up with a properly finished Rp2040 Devboard
## Features
- RP2040 Chip Based
- 2-layer compact PCB
- Most of the gpio avialable 
- USB connection for programming and power
- Onboard  voltage regulation
- Compact footprint for small projects
- Educational focus for learning MCU integration and PCB design

## 🧾 Bill of Materials (BOM)

| Qty | Manufacturer Part Number | Description | Supplier | Unit Price (USD) | Total (USD) |
|-----|--------------------------|-------------|----------|------------------|-------------|
| 2 | C0402C105K9PACTU | CAP CER 1UF 6.3V X5R 0402 | DigiKey.in | 0.08000 | 0.16 |
| 11 | 0402B104K160CT | CAP CER 0.1UF 16V X7R 0402 | DigiKey.in | 0.00300 | 0.03 |
| 2 | LMK107BBJ106MALT | CAP CER 10UF 10V X5R 0603 | DigiKey.in | 0.08000 | 0.16 |
| 2 | CL05C330JB5NNNC | CAP CER 33PF 50V C0G/NP0 0402 | DigiKey.in | 0.10000 | 0.20 |
| 1 | USB4215-03-A | USB C RECEPTAC, SHT BODY, USB2.0 | DigiKey.in | 0.49000 | 0.49 |
| 2 | RC0402FR-075K1L | RES 5.1K OHM 1% 1/16W 0402 | DigiKey.in | 0.10000 | 0.20 |
| 2 | ERA-2AEB273X | RES SMD 27K OHM 0.1% 1/16W 0402 | DigiKey.in | 0.10000 | 0.20 |
| 2 | RMCF0603FT1K00 | RES 1K OHM 1% 1/10W 0603 | DigiKey.in | 0.10000 | 0.20 |
| 1 | RC0201FR-0710KL | RES 10K OHM 1% 1/20W 0201 | DigiKey.in | 0.10000 | 0.10 |
| 1 | SW-PB9-AB00AQE-5 | Subminiature Pushbutton Switch | DigiKey.in | 3.39000 | 3.39 |
| 1 | SC0914(13) | IC MCU 32B EXT MEM 56QFN RP2040 | DigiKey.in | 0.70000 | 0.70 |
| 1 | MCP1700T-3302E/TT | IC REG LINEAR 3.3V 250MA SOT23-3 | DigiKey.in | 0.51000 | 0.51 |
| 1 | AT24CS02-SSHM-T | IC EEPROM 2KBIT I2C 1MHZ 8SOIC | DigiKey.in | 0.31000 | 0.31 |
| 1 | STDCRA3-8M | CRYSTAL 8.0000MHZ 8PF SMD | DigiKey.in | 0.84000 | 0.84 |
| 2 | DW-10-15-T-D-420-LL | CONN HDR 20POS 0.1 STACK T/H TIN | DigiKey.in | 1.99000 | 3.98 |

---

## 💰 Cost Breakdown

| Item | Cost (USD) |
|------|------------|
| Parts Total (DigiKey) | 11.47 |
| DigiKey Shipping | 20.00 |
| JLCPCB + Stencil | 11.47 |
| JLCPCB Shipping | 25.11 |
| Discount | -5.00 |
| **Grand Total** | **63.05 USD** |

---

### 🧮 Final Total: **$63.05 USD**

## Schematic & PCB
<br><img width="1029" height="712" alt="Screenshot (108)" src="https://github.com/user-attachments/assets/bbef5e52-335d-478e-85d1-fe733156dd36" /><br>
<br><img width="342" height="643" alt="Screenshot (118)" src="https://github.com/user-attachments/assets/a6779f1f-83e6-415f-b5f6-72a0a45fe9c9" />
<br>

 ## 3d Render
<br><img width="1250" height="862" alt="Screenshot (111)" src="https://github.com/user-attachments/assets/12679640-6588-45de-b97f-0cbd64c767ee" />
<br>
<br><img width="405" height="833" alt="Screenshot (116)" src="https://github.com/user-attachments/assets/04862832-c875-406a-b763-b9952221b944" />
<br>
<br><img width="480" height="950" alt="Screenshot (115)" src="https://github.com/user-attachments/assets/97ec3d4d-37b7-47f7-ab94-d7e9dde2760f" />
 <br>


