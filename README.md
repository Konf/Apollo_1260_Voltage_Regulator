# Apollo 1260 Voltage Regulator

Voltage Regulator PCB for Apollo 1260 Amiga accelarator card.

This regulator should also work for Apollo 4060 and Apollo 3060, but not tested. 

Inspired by this project: https://www.ikod.se/apollo-vr-12604060/

Created in Altium Designer 17. Gerber files included.

## Some helpful info if you want to make this PCB

Use 35um thick copper foil. Traces width was calculated with 35um foil in mind.

If you are going to overclock hard (75MHz+) it's a good idea to cool the regulator, as it will get hot. Some airflow inside A1200 case will be OK.

Be careful with tantalum capacitors. They tend to explode if installed with wrong polarity. "+" is marked with a dot on silk-layer.

## Bill of materials

| Part                                  | pcs |
| --------------------------------------|-----|
| LT1085-3.3 in TO-220 package          | 1   |
| 10uF type B tantalum capacitor        | 2   |
| 0.1uF 1206 ceramic capacitor          | 1   |
| [optional] 2.54 2x8 female connector  | 1   |

Use 10-16V+ capacitors, especially the ceramic one.
