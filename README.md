# Custom-PC-stand
<img width="1410" height="2000" alt="THE custom PC stand" src="https://github.com/user-attachments/assets/d42caac8-d585-46d1-b536-2db97565a9b5" />
Since I got my new laptop, I always wanted to get a stand for easier usage but most of the designs i found online were either too expensive or couldn't support the weight of my PC (3kgs). So I decided to make my own design with adjustable width going from 135mm to 215mm and angles.


<img width="1279" height="554" alt="Screenshot 2026-05-29 130837" src="https://github.com/user-attachments/assets/6eb90ba0-c32a-45c5-be18-d9e32fd383df" />


you can choose 4 angles to set your PC on which are : 
1- 33 degrees
2- 28 degrees
3- 22 degrees
4- 15 degrees


<img width="1122" height="447" alt="image" src="https://github.com/user-attachments/assets/d946f54e-87da-4977-b873-bddbae1987e8" />



The design can also be disassembled for easier carrying ! It is mainly composed from 5 parts that are easy to connect and to disconnect. I designed hinges suitable for 3d printing because thats how I was planning to build it so I wouldn't recommend using other materials than plastic. The extremeties of the parts have to be bent so they can fit through. Also I would recommend using PETG filament instead of PLA because it can support heating and the weight better than the PLA.


<img width="469" height="528" alt="image" src="https://github.com/user-attachments/assets/b1f79d57-147f-4920-a2c3-4a62d8369f5b" />


The design also include two 12V DC fans mounted in parallel to cool down my laptop. The fans are powered by the 5V USB-c output of my laptor, so I will use a boost converter XL6009 to elevate the Voltage from 5V to 12V with ceramic and electrolytic capacitors and a polyfuse.
I will cut a USB-c wire and directly solder it to the capacitors and the boost converter.

Here is the wiring :
https://app.cirkitdesigner.com/project/a9c20a31-ab86-427d-9aed-42c307f47625


<img width="427" height="731" alt="Screenshot 2026-05-29 122412" src="https://github.com/user-attachments/assets/6bd708b2-f0cc-4ea0-bc02-fc5604ad5868" />


The fans are connected to the overall structure using M3 countersunk flat head crossed screws and M3 hex nuts. I designed the slots of the fan to fix it according to the exact model I was planning to buy.


<img width="659" height="589" alt="image" src="https://github.com/user-attachments/assets/3a43e16d-d09d-43f4-adf2-35081d649015" />

<img width="482" height="803" alt="image" src="https://github.com/user-attachments/assets/d0bf2714-ab34-47f3-be72-3253d8c4a35a" />

I also made a case for the XL6009E1 boost converted with each pin written on the outside

<img width="880" height="657" alt="Screenshot 2026-06-05 160744" src="https://github.com/user-attachments/assets/8dc9da3b-8b29-497c-9943-844bcf280f6a" />

<img width="472" height="317" alt="Screenshot 2026-06-05 160819" src="https://github.com/user-attachments/assets/4746bb5c-c108-4191-8855-bb7530135392" />


# BOM :
- 2 40mmx40mmx10mm 12V DC fans https://little-son.tn/accueil/1542-ventilateur-12v-40x40x10mm-2-fils.html
- 4 M3 12mm countersunk flat head crossed screws
- 8 M3 16mm countersunk flat head crossed screws
- 8 M3 hex nuts
- 4 M3 heat set inserts for 3d printing
- 1 boost converter XL6009E1 https://little-son.tn/accueil/627-module-xl6009-elevateur-regulateur-de-tension-dc-dc-3-32v-a-5-35v.html
- 2 100µF electrolytic capacitors
- 1 10nF ceramic capacitor
- 1 10µF ceramic capacitor
- 1 500mA polyfuse
