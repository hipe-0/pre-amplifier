# Pre-Amplifier by Hippo

This DIY amplifier brings nice overtones to my guitar or my DIY synthesizer (link on github https://github.com/hipe-0/synthesizer).
3D-Print (link on Thingiverse https://www.thingiverse.com/thing:6841592) and weld your own using the provided shematic and bill of materials!

This Guitar Amp is straightforward, it works and sounds great. Any feedback appreciated!

![oveview](https://github.com/user-attachments/assets/4b9e8350-353e-4c2c-883b-4f41ec04b319)

# Demo
https://github.com/user-attachments/assets/a7c7ef76-c136-456c-b7f8-a1a015e33860


# Features
1. Based on the simple **LM386** amplifier IC integrated circuit
 ![image](https://github.com/user-attachments/assets/3a6b4c6d-d6de-4031-835d-a87ea6fb5e87)
3. **Volume** knob, **Gain** knob, **Saturation** switch, on/off switch
4. Nice smooth amplification volume from 0 to maximum
5. Nice ovetones after 80% of high gain knob
6. No preceptible audio noise or problem
7. **Distorsion** switch: For fun, I added simple clipping circuit using a single PNP transistor (S9012) ![image](https://github.com/user-attachments/assets/480d97f4-6392-442c-ab1c-eb6f65a24034)
8. Consequence on the oscilloscope, the upper part of the guitar signal is entirely chopped-off. A very drastic clipping stage! Side effect: it reduces volume a bit and cuts trailing reverbs of guitar as often the case, but it's nice.

# Shematic
![2024-11-17 Guitar Amp with LM386 IC PCB version_schéma](https://github.com/user-attachments/assets/6841a25a-a15e-4e94-b111-990fc29eecd8)

# Prototype board view
![2024-11-17 Guitar Amp with LM386 IC PCB version_bb](https://github.com/user-attachments/assets/14b86e2b-ff39-4d20-b0dd-137a01a2d5b9)

# PCB Printed circuit board (optional)
![2024-11-17 Guitar Amp with LM386 IC PCB version_circuit imprimé](https://github.com/user-attachments/assets/9d9245cc-9326-44e2-ba8a-51a9ef83d8e9)

# Assembly
![image](https://github.com/user-attachments/assets/11bdfdc1-348a-4d9e-8980-40dbcec4e25e)


# Bill of material
- Enclosure box in PETG to print yourself (all 3D models are provided on this repository, a copy with printer settings is also on https://www.thingiverse.com/thing:6841592)
- Enclosure lid in PETG
- 4x PCB supports (to screw and glue)
- Either the printed PCB (gerber files are provided) or a prototype circuit board to weld yourself
- Wire
- 2x 6.5mm audio jack connectors (I used https://www.aliexpress.com/item/1005004458769152.html?spm=a2g0o.order_list.order_list_main.473.33de1802eYvuy3)
- IC LM386 operational amplificator
- PNP transistor S9012
- Blue LED 5mm
- Resistor 10K
- Resistor 1K
- Resistor 10 Ohm
- 2x Capacitors 0.47 mF
- 1x Capacitor 4.7 uF
- 2x Capacitor 10 uF
- 2x Potentiometer 10K with caps
- 18650 Li-ion battery with battery holder and 5v converter - charger (I used https://www.aliexpress.com/item/1005001621882169.html?spm=a2g0o.order_list.order_list_main.233.33de1802eYvuy3)
