# Custom-PC-stand
Since I got my new laptop, I always wanted to get a stand for easier usage but most of the designs i found online were either too expensive or couldn't support the weight of my PC (3kgs). So I decided to make my own design with adjustable width going from 135mm to 215mm and angles.


<img width="1109" height="438" alt="image" src="https://github.com/user-attachments/assets/c9b34fca-a806-49f7-8e93-c16afd546882" />


you can choose 4 angles to set your PC on which are : 
1- 33 degrees
2- 28 degrees
3- 22 degrees
4- 15 degrees


<img width="1185" height="669" alt="image" src="https://github.com/user-attachments/assets/3ec882c6-8c6e-4cb2-a37f-59c902fa04ac" />


The design can also be disassembled for easier carrying ! It is mainly composed from 5 parts that are easy to connect and to disconnect. I designed hinges suitable for 3d printing because thats how I was planning to build it so I wouldn't recommend using other materials than plastic. The extremeties of the parts have to be bent so they can fit through. 


<img width="469" height="528" alt="image" src="https://github.com/user-attachments/assets/b1f79d57-147f-4920-a2c3-4a62d8369f5b" />


The design also include two 12V DC fans mounted in parallel to cool down my laptop. The fans are powered by the 5V USB-c output of my laptor, so I will use a boost converter XL6009 to elevate the Voltage from 5V to 12V with ceramic and electrolytic capacitors and a polyfuse.
I will cut a USB-c wire and directly solder it to the capacitors and the boost converter.

Here is the wiring :


<img width="427" height="731" alt="Screenshot 2026-05-29 122412" src="https://github.com/user-attachments/assets/6bd708b2-f0cc-4ea0-bc02-fc5604ad5868" />


The fans are connected to the overall structure using M3 hex bolts and M3 hex nuts. I designed the slots of the fan to fix it according to the exact model I was planning to buy.


<img width="659" height="589" alt="image" src="https://github.com/user-attachments/assets/3a43e16d-d09d-43f4-adf2-35081d649015" />

<img width="482" height="803" alt="image" src="https://github.com/user-attachments/assets/d0bf2714-ab34-47f3-be72-3253d8c4a35a" />


BOM :
- 2 40mmx40mmx10mm 12V DC fans https://little-son.tn/accueil/1542-ventilateur-12v-40x40x10mm-2-fils.html
- 8 M3 hex screws
- 8 M3 hex nuts
- 1 boost converter XL6009 https://little-son.tn/accueil/627-module-xl6009-elevateur-regulateur-de-tension-dc-dc-3-32v-a-5-35v.html
- 2 100µF electrolytic capacitors
- 1 10nF ceramic capacitor
- 1 10µF ceramic capacitor
- 1 500mA polyfuse
