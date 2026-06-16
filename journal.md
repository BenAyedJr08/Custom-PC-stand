# Day one
today i started my project by 3d modeling essential parts to the PC stand using solidworks. 
I was planning to 3d print the parts so i searched on youtube for some tips to design 3d printable hinges for the rotation of my stand and i got started. I designed the first 3 parts of my project and assembled them to see how they fit and to look for any flaws. throughout these few hours that i spent on 3d modeling, i got more used to 3d softwares and learned a lot from my mistakes.

<img width="1182" height="662" alt="image" src="https://github.com/user-attachments/assets/0a0788a6-d45c-498b-bd43-cabdb4309506" />

<img width="1163" height="609" alt="image" src="https://github.com/user-attachments/assets/115c67d9-441f-40c9-9a37-890f40a5639b" />

<img width="323" height="739" alt="image" src="https://github.com/user-attachments/assets/785670d4-a297-444d-8b1f-301e773be414" />

## Entry 2

After finishing exams, I came back to resume working on my pc stand projects so i started by making the supporting rod which will help adjust the angle of the stand then i rectified some mistakes from last time with the hinges. i didnt leave enough room for the parts to rotate to small angles like 15 or 20 degrees which are the most used angles in pc stands. so i removed some excess material and added a small obstacle for the supporting rod to help support the weight of the pc at this angle. I also added some material under the pc to :
1- help support its weight
2- allow me to fix the fans on them
so here is the final result ! next time i will work on the electric part (2 fans and LED rgb)


<img width="1061" height="660" alt="image" src="https://github.com/user-attachments/assets/0bc31afb-f0bd-4caa-b9ca-ca3248c9b0eb" />

## Entry 3

Today, I finished working on the CAD of my PC stand. I started by correcting 2 mistakes from last time.

First of all, I forgot to remove some material on the left part of the stand which allows it to rotate to small angles (20-15 degrees) so i corrected it this time.

Then, I removed a chunk of material on the supporting rod to allow it to bend and connect with the hinge. 

Next, I started working on the electrical part. I started by choosing the components and finding their datasheet. I will use :
-two 24V 40*40*28 fans 
-16 RGB diode LEDs 
-two AA 3 case battery holders. 

I used the datasheets to design the slots for these components so they can be fixed on the overall design.


<img width="441" height="715" alt="image" src="https://github.com/user-attachments/assets/e9ba8913-ab09-4e8b-9001-20746ce66b3e" />

<img width="869" height="489" alt="image" src="https://github.com/user-attachments/assets/3d9852b3-47f4-47c2-8fc8-55cf98b71f1b" />

<img width="1142" height="686" alt="image" src="https://github.com/user-attachments/assets/72410165-7775-495c-b5f3-8fe275a5ab92" />

<img width="1099" height="662" alt="image" src="https://github.com/user-attachments/assets/7795a5d0-ef80-46c3-b7ad-fd68a6a5e905" />


## Entry 4

So I started working on the electrical part of my project. I was planning to use 2 fans and 16 RGB LEDs so i worked on the schematics. i got no problem with the fans, connecting them in parallel and with 24V alimentation, a switch and a potentiometer. However, i thought i had to create my own custom part on cirkit with 3 pins on the fan, only to realize that i didn't actually need the 3rd pin (sensor). then, I downloaded the 3d models of the fans from grabcad so I can add them to the assembly. but when i started working on the RGB LEDs, I faced many challenges that were way too difficult to solve for me. I didn't know how to connect them to control the light switch and with the alimentation. I didn't want to use more than two 3.7 lithium batteries so it should have been connected partially in parallel, which i couldn't solve due to the high number of pins of the RGB diodes (4). so after trying to understand the circuit and searching on Youtube and letting AI explain it to me, I realized that it was too much for me as a beginner. I'm not also a big fan of electronics, I find it difficult to understand circuits and I like more the mechanical aspect of projects. So I decided to use LEDs strips instead of making my own LED circuit. I came back to the CAD files and removed the LED slots and was going to start working on the strips slots but I was too exhausted for it today and I will resume working on it tomorrow.

<img width="286" height="252" alt="image" src="https://github.com/user-attachments/assets/a30743a3-0d02-4d8b-950a-b8d3c6501295" />

<img width="352" height="252" alt="image" src="https://github.com/user-attachments/assets/d69928c4-1574-4431-861d-e393b83a3e5f" />

<img width="758" height="544" alt="image" src="https://github.com/user-attachments/assets/1a3787c6-b513-43a1-891f-6374f2bb118f" />

<img width="829" height="509" alt="image" src="https://github.com/user-attachments/assets/07daf802-d951-4afd-a71e-cae3bde3789d" />


## Entry 5

After consideration, I decided to end my project today but without RGB LEDs. I realized that this was going to be too much of an effort and too time consuming for me as a beginner to work on the RGB LEDs and understanding the circuits, calculating the power distribution adaptation etc... So I would prefer staying with the mechanism and two fans and ending this project to start working on others. So today I finished by setting the screws and the bolts. I used M3 hex bolts and M3 hex nuts for the 3.7mm diameter of the fan holes.

<img width="1359" height="736" alt="image" src="https://github.com/user-attachments/assets/a126b4d3-a406-40e6-b6f4-49aad6848451" />

<img width="1250" height="570" alt="image" src="https://github.com/user-attachments/assets/6df0ac2b-b128-4966-a562-9ecaf2a98a60" />


## Entry 6

After showing my design to some friends, they gave me some advice so I made adjustments.
First of all, I removed the lithium batteries and decided to use the 5V output of my laptop. Using 6 lithium batteries is very expensive and not optimal. So I removed the battery casing slots in my design.
My second adjustment was using 12V fans instead of 24V. Then I worked on the circuit. I will use a 500mA polyfuse to protect it, 2 100µF electrolytic capacitors, a 10nF and a 10µF ceramic capacitor for better stability. To elevate the voltage from 5V to 12V, I chose the XL6009 boost converter.
and to connect the 5V power supply to the circuit, I will cut a USB-c wire and directly solder it to the components.
I also designed a small fixing rod to fix the width of the pc stand.

<img width="427" height="731" alt="image" src="https://github.com/user-attachments/assets/55048bf9-d957-42f1-9e3b-7ba8f40d68ea" />

<img width="949" height="503" alt="image" src="https://github.com/user-attachments/assets/5cd698e5-3a76-4b6b-8528-9d9be328fb8c" />

<img width="467" height="646" alt="image" src="https://github.com/user-attachments/assets/4d8bc7ad-1a1d-4977-a0b8-3392966cff9d" />

## Entry 7

Yesterday I started building my project irl ! So I saved all the parts of my pc stand as step files and imported them to bambu lab studio. I worked on the parts placement and tried to minimize the time and filament usage for my prints. 
my main concern was the strength of the two left and right supporting parts because they have to hold the weight and heat of the pc so I used PETG filament instead of PLA and added the number of walls (3)

<img width="755" height="558" alt="image" src="https://github.com/user-attachments/assets/85a49d51-dbdd-4ca7-9647-ce2615df98ba" />

the whole process took more than 13 hours so I finished printing today morning. 

<img width="1536" height="2048" alt="image" src="https://github.com/user-attachments/assets/749f5e49-412b-4fa4-a8c7-59d59ec3b645" />

<img width="1536" height="2048" alt="image" src="https://github.com/user-attachments/assets/e578c2ed-e4ee-4521-9704-8f603bd09370" />

<img width="1536" height="2048" alt="image" src="https://github.com/user-attachments/assets/a61f5007-000a-4c75-a3e8-86eb783d8e2f" />


## Entry 8

After finishing printing my parts, I started by removing the supports. I had some trouble with this part as the trees were located deep inside the right part.

<img width="1536" height="2048" alt="image" src="https://github.com/user-attachments/assets/79ee885e-a0f4-415a-aa52-3ce7c6f61a0c" />

then I assembled all the parts but i found out that I did a big mistake with the angles as I didn't remove enough material for the stand to rotate to 15 degrees.

<img width="1147" height="656" alt="image" src="https://github.com/user-attachments/assets/d5ca20d7-4766-4be1-adac-99a46d1998fe" />

also the 0.4mm tolerance I left for the right and left right so they can fit easily was apparently not enough.

<img width="787" height="403" alt="image" src="https://github.com/user-attachments/assets/5f963529-924b-46d1-8884-474e4796a20b" />

But at least the assembly was complete and I tested it with my friends computer and it worked.
Next time I will fix the issues with the CAD and reupload the new files.

<img width="2048" height="1798" alt="image" src="https://github.com/user-attachments/assets/43f09eb6-3c0a-4d22-8dd7-0fbab8b16927" />


## Entry 9

After building my project irl, I realized I made some mistakes. I thought I left a 0.4mm tolerance between the left and right parts but in reality it was only 0.1mm. Thats why it was difficult to insert. So I changed it to 0.3mm. also I had to remove some material in the supporting parts so the stand could rotate to the minimum angle.
I also updated the files in the github repo.

<img width="1054" height="752" alt="image" src="https://github.com/user-attachments/assets/d2978541-d4af-42e1-be44-3385a09e5cf7" />


## Entry 10

Today I finished the CAD by designing a case for the XL6009E1 boost converter. 

<img width="880" height="657" alt="image" src="https://github.com/user-attachments/assets/1e076d50-518b-4773-b467-88b7cb4e81ee" />

I made four elongated holes so the copper wires could pass and associated for each pin its name with the hole

<img width="472" height="317" alt="image" src="https://github.com/user-attachments/assets/75c484e6-3626-440f-bc74-0ed02c8eb4f8" />

I used M3 heat set inserts and M3 12mm countersunk flat head crossed screws to connect the case with its upper part.
I also replace the hex bolts in the pc stand assembly that connects the mechanism with the fans with the same screws (but 16mm instead of 12mm) as it is more accurate.

<img width="1056" height="450" alt="image" src="https://github.com/user-attachments/assets/7767584d-ac63-4ddd-b9d1-615ab0c92fc8" />

<img width="1122" height="447" alt="image" src="https://github.com/user-attachments/assets/8c7b04f1-0716-4256-bc34-402e33de3ff5" />

## Entry 11

After assembling my 3d printed parts, I started working on the electric aspect of my project. It is my first time building something irl, and maybe the second time I touched a soldering iron, so I learned a lot today and got more used to building things. So I assembled the fans and fixed them with screws and bolts to the pc stand.

<img width="1536" height="2048" alt="image" src="https://github.com/user-attachments/assets/0ed41a88-72e4-4996-b2e3-ea9ee620aefb" />

<img width="1536" height="2048" alt="image" src="https://github.com/user-attachments/assets/f32e20c5-5d47-4b79-b349-fb099afc7baa" />

I also soldered everything and used all the parts needed in my project.

<img width="2048" height="1536" alt="image" src="https://github.com/user-attachments/assets/b8917bc9-f59a-491c-a907-a4def3ecbc45" />

<img width="2048" height="1536" alt="image" src="https://github.com/user-attachments/assets/6fd7170a-b097-4cfc-8a42-fe7b933e9d27" />

One of the issues that I have encountered are with the pin IN- of the boost converter. the electric wire broke and fixing it was hard. 

I'm really proud of the progress I made so far even though the circuit didn't work. However I tried to find the real problem and proceeded to debugging. the voltmeter showed 0.4V on the input side of the boost converter, when it should have been 5V from the PC. The XL6009E1 accepts a minimum voltage of 3V, which way more than what my PC emitted.  I used other PCs to compare and see if the problem was my PC or something else and every time I got a very low voltage so I knew the problem was the USB-C cable I was using, as it was really old and not used in a long time. So I will get  a 3.7V li ion battery and test my wiring with it before sacrificing a new USB-C cable.

## Entry 12

After some troubleshooting and realizing that the problem was from the USB-c cable that couldn't pull 5V from the PC, I switched to two LI-ION batteries. after removing the USB-C cables and soldering the battery case wires the design finally worked and the fans started cooling. I then adjusted the boost converter so it can give the power needed for the fans to work comfortably.

<img width="1536" height="2048" alt="image" src="https://github.com/user-attachments/assets/7c8c5cd8-83df-489d-abac-3478ba172b33" />

## Entry 13

finally ending my project with the zine page. I made a cool black and white design with canva because I printed my project with white filament.

<img width="1410" height="2000" alt="image" src="https://github.com/user-attachments/assets/6db6deff-f38a-4428-ae95-8f02ed94f665" />
