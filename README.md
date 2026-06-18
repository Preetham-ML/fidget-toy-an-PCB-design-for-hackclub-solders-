# Fidget Dashboard

A handheld fidget toy PCB built for Hack Club's **Solder** program. It combines manual button-triggered LEDs with a light-sensing (photoresistor) circuit that turns LEDs on automatically depending on ambient light.

## What it does
- **Manual circuit:** Two push buttons (SW1, SW2) feed into a pair of 2N3904 transistors (Q1, Q2), which switch power to an LED (D1) when pressed.
- **Light-sensing circuit:** A GL5528 photoresistor (R7) and a 10kΩ potentiometer (RV1) form a light-dependent voltage divider. This feeds a third 2N3904 (Q3), which switches a pair of LEDs (D2, D3) on or off automatically as ambient light changes — the potentiometer lets you tune the sensitivity/threshold.

Power comes from a battery cell behind VCC/GND rails feeding both halves of the circuit.

## Bill of Materials

| Part                  | Reference  | Qty | 
| --- | --- | --- |
| 2N3904 NPN transistor | Q1, Q2, Q3 | 3 | 
| 220Ω resistor         | R3, R5, R6 | 3 | 
| 4.7kΩ resistor        | R1, R2, R4 | 3 |
| 10kΩ potentiometer    | RV1 | 1 |
| GL5528 photoresistor  | R7 | 1 |
| 5mm LED               | D1, D2, D3 | 3 |
| 6mm push button       | SW1, SW2 | 2 |
| CR2032 battery cell   | BT1 , BT2 | 2 | 

## Screenshots

- [ <img width="1920" height="1080" alt="Screenshot (1521)" src="https://github.com/user-attachments/assets/e525dd56-8174-4995-8e9b-8ea4be470923" />
] Schematic screenshot    
- [<img width="1920" height="1080" alt="Screenshot (1520)" src="https://github.com/user-attachments/assets/26a0eb2c-8080-4372-a5a8-69ae3c1f11bd" />
 ] PCB layout screenshot (front + back if double sided)
- [<img width="1920" height="1080" alt="Screenshot (1522)" src="https://github.com/user-attachments/assets/e0f4ac51-aeb9-4311-bec0-19a3247c067d" />
 ] 3D render screenshot

## Files in this repo
all the files of my fidget dashboard are upload in repo 
## Slack username
preetham ml
## Notes / Reflections
> - This my first every PCB project. I had to learn all the basic electronics how to use kicad but its kinda fun knowning no errors looking at 3d model. i like the feel. yep it took me 5 days from learning basic electronics to design my first pcb (btw its scecond before truning down like 5-10 desings, first was battery resistor and an bulb.)
> - ahhh The reason select this design cause every one loves when light when darks up (atleast for me ) and also wanted to be fun toy so i add the two push button led.
> - THE tricky part was the wiring its alone took 2+days its hell.
> - what i learn - was like every thing is new to me  but to undo the trickyness of wiring make pcb desing as similar to schematics 
