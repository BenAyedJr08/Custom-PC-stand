# Day one
today i started my project by 3d modeling essential parts to the PC stand using solidworks. 
I was planning to 3d print the parts so i searched on youtube for some tips to design 3d printable hinges for the rotation of my stand and i got started. I designed the first 3 parts of my project and assembled them to see how they fit and to look for any flaws. throughout these few hours that i spent on 3d modeling, i got more used to 3d softwares and learned a lot from my mistakes.

![image_2026-05-16_221616658.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTYzODQsInB1ciI6ImJsb2JfaWQifX0=--469e4051dab665cf01758b83de5be90111354393/image_2026-05-16_221616658.png)

![image_2026-05-16_221655098.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTYzODYsInB1ciI6ImJsb2JfaWQifX0=--1be2ae8264620c6b286f660ab8b3c20718c06066/image_2026-05-16_221655098.png)

![image_2026-05-16_221726713.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTYzODcsInB1ciI6ImJsb2JfaWQifX0=--57a990cb85982c1c0dfa519be60203996cecdf59/image_2026-05-16_221726713.png)

## Entry 2

After finishing exams, I came back to resume working on my pc stand projects so i started by making the supporting rod which will help adjust the angle of the stand then i rectified some mistakes from last time with the hinges. i didnt leave enough room for the parts to rotate to small angles like 15 or 20 degrees which are the most used angles in pc stands. so i removed some excess material and added a small obstacle for the supporting rod to help support the weight of the pc at this angle. I also added some material under the pc to :
1- help support its weight
2- allow me to fix the fans on them
so here is the final result ! next time i will work on the electric part (2 fans and LED rgb)


![image_2026-05-23_180030303.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTkwNTIsInB1ciI6ImJsb2JfaWQifX0=--7315d03cd0815ce487a5d13f54fa3c91e5039dd2/image_2026-05-23_180030303.png)

## Entry 3

Today, I finished working on the CAD of my PC stand. I started by correcting 2 mistakes from last time.

First of all, I forgot to remove some material on the left part of the stand which allows it to rotate to small angles (20-15 degrees) so i corrected it this time.

Then, I removed a chunk of material on the supporting rod to allow it to bend and connect with the hinge. 

Next, I started working on the electrical part. I started by choosing the components and finding their datasheet. I will use :
-two 24V 40*40*28 fans 
-16 RGB diode LEDs 
-two AA 3 case battery holders. 

I used the datasheets to design the slots for these components so they can be fixed on the overall design.



![image_2026-05-25_132903148.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjAxNDUsInB1ciI6ImJsb2JfaWQifX0=--bcc1e1ea59e5904329bedab9bd72da2a51f9bad0/image_2026-05-25_132903148.png)

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjAxNTAsInB1ciI6ImJsb2JfaWQifX0=--00719f8614f794981f2f5535dfb84d23d7cf95c6/image.png)

![Screenshot 2026-05-25 130826.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjAxNTIsInB1ciI6ImJsb2JfaWQifX0=--76b77b2eb1363a4588d08fe8888eae816456cce7/Screenshot 2026-05-25 130826.png)

![Screenshot 2026-05-25 130842.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjAxNTMsInB1ciI6ImJsb2JfaWQifX0=--47783de8898c7d77bc6cb0769adbbfd045caaafa/Screenshot 2026-05-25 130842.png)


## Entry 4

So I started working on the electrical part of my project. I was planning to use 2 fans and 16 RGB LEDs so i worked on the schematics. i got no problem with the fans, connecting them in parallel and with 24V alimentation, a switch and a potentiometer. However, i thought i had to create my own custom part on cirkit with 3 pins on the fan, only to realize that i didn't actually need the 3rd pin (sensor). then, I downloaded the 3d models of the fans from grabcad so I can add them to the assembly. but when i started working on the RGB LEDs, I faced many challenges that were way too difficult to solve for me. I didn't know how to connect them to control the light switch and with the alimentation. I didn't want to use more than two 3.7 lithium batteries so it should have been connected partially in parallel, which i couldn't solve due to the high number of pins of the RGB diodes (4). so after trying to understand the circuit and searching on Youtube and letting AI explain it to me, I realized that it was too much for me as a beginner. I'm not also a big fan of electronics, I find it difficult to understand circuits and I like more the mechanical aspect of projects. So I decided to use LEDs strips instead of making my own LED circuit. I came back to the CAD files and removed the LED slots and was going to start working on the strips slots but I was too exhausted for it today and I will resume working on it tomorrow.

![Screenshot 2026-05-25 184030.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjAyOTQsInB1ciI6ImJsb2JfaWQifX0=--37579fa2a4ff6a819a092ae49a8fe4d890b0ec6d/Screenshot 2026-05-25 184030.png)

![Screenshot 2026-05-25 184034.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjAyOTYsInB1ciI6ImJsb2JfaWQifX0=--10b62bf776c94aa71631eddbd21e50f7dfc15398/Screenshot 2026-05-25 184034.png)

![Screenshot 2026-05-25 180806.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjAyOTcsInB1ciI6ImJsb2JfaWQifX0=--1ba6e9ad659fc82c047ff9c823019dfe62fa2a28/Screenshot 2026-05-25 180806.png)

![Screenshot 2026-05-25 180811.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjAyOTgsInB1ciI6ImJsb2JfaWQifX0=--33961b437b20a5d652089f956109d76bef9d4fa3/Screenshot 2026-05-25 180811.png)


## Entry 5

After consideration, I decided to end my project today but without RGB LEDs. I realized that this was going to be too much of an effort and too time consuming for me as a beginner to work on the RGB LEDs and understanding the circuits, calculating the power distribution adaptation etc... So I would prefer staying with the mechanism and two fans and ending this project to start working on others. So today I finished by setting the screws and the bolts. I used M3 hex bolts and M3 hex nuts for the 3.7mm diameter of the fan holes.
![Screenshot 2026-05-26 123949.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjA3NDMsInB1ciI6ImJsb2JfaWQifX0=--7985523d1d10ca6e62f96f6eb8faad078161cbbf/Screenshot 2026-05-26 123949.png)
![Screenshot 2026-05-26 124013.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjA3NDYsInB1ciI6ImJsb2JfaWQifX0=--d6cb2bc0c73e239a35e2f8d1e7bdad7cc13c3062/Screenshot 2026-05-26 124013.png)


## Entry 6

After showing my design to some friends, they gave me some advice so I made adjustments.
First of all, I removed the lithium batteries and decided to use the 5V output of my laptop. Using 6 lithium batteries is very expensive and not optimal. So I removed the battery casing slots in my design.
My second adjustment was using 12V fans instead of 24V. Then I worked on the circuit. I will use a 500mA polyfuse to protect it, 2 100µF electrolytic capacitors, a 10nF and a 10µF ceramic capacitor for better stability. To elevate the voltage from 5V to 12V, I chose the XL6009 boost converter.
and to connect the 5V power supply to the circuit, I will cut a USB-c wire and directly solder it to the components.
I also designed a small fixing rod to fix the width of the pc stand.
![Screenshot 2026-05-29 122412.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjI4NTQsInB1ciI6ImJsb2JfaWQifX0=--8c16d2956758cbcfca048b2936b9e35553c34fa8/Screenshot 2026-05-29 122412.png)
![Screenshot 2026-05-29 124339.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjI4NTUsInB1ciI6ImJsb2JfaWQifX0=--225572dc6c66d8f3a7a893247dd525235e017b3a/Screenshot 2026-05-29 124339.png)
![Screenshot 2026-05-29 130846.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjI4NjQsInB1ciI6ImJsb2JfaWQifX0=--8113fd98abc0b05d1713a027e6756a11d1a39ae1/Screenshot 2026-05-29 130846.png)

## Entry 7

Yesterday I started building my project irl ! So I saved all the parts of my pc stand as step files and imported them to bambu lab studio. I worked on the parts placement and tried to minimize the time and filament usage for my prints. 
my main concern was the strength of the two left and right supporting parts because they have to hold the weight and heat of the pc so I used PETG filament instead of PLA and added the number of walls (3)
![image_2026-06-03_152055878.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjYzODgsInB1ciI6ImJsb2JfaWQifX0=--5203804b298ed34acf9f3ebe9643cab4e4bc1adb/image_2026-06-03_152055878.png)
the whole process took more than 13 hours so I finished printing today morning. 

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjYzOTMsInB1ciI6ImJsb2JfaWQifX0=--e02fdad2ba2fba121e96c64eea7a9d676b77611f/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjYzOTUsInB1ciI6ImJsb2JfaWQifX0=--d0b55591ca2f3ba6288e262efd2e1d66e7ce35b2/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjYzOTYsInB1ciI6ImJsb2JfaWQifX0=--3e2effb5c10c4e1c5fcd1cdf121120b653d76333/image.png)


## Entry 8

After finishing printing my parts, I started by removing the supports. I had some trouble with this part as the trees were located deep inside the right part.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjY5MzQsInB1ciI6ImJsb2JfaWQifX0=--a843a55a0360df9d336fc5a4dae1091720192c1b/image.png)
then I assembled all the parts but i found out that I did a big mistake with the angles as I didn't remove enough material for the stand to rotate to 15 degrees.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjY5MzUsInB1ciI6ImJsb2JfaWQifX0=--cf4b733dfb6a803e92c95b8b1cd367ac3e0e7eb8/image.png)
also the 0.4mm tolerance I left for the right and left right so they can fit easily was apparently not enough.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjY5MzcsInB1ciI6ImJsb2JfaWQifX0=--75c64bb212563a2b4d8fbdf5b31e91fb0b91623f/image.png)
But at least the assembly was complete and I tested it with my friends computer and it worked.
Next time I will fix the issues with the CAD and reupload the new files.
![9e32641d-c1ac-4841-902b-e39d5d8ccd1d.jpg](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjY5MzksInB1ciI6ImJsb2JfaWQifX0=--c5c9a5b38ffe845448b6d6218e22f5cefd87a3fb/9e32641d-c1ac-4841-902b-e39d5d8ccd1d.jpg)


## Entry 9

After building my project irl, I realized I made some mistakes. I thought I left a 0.4mm tolerance between the left and right parts but in reality it was only 0.1mm. Thats why it was difficult to insert. So I changed it to 0.3mm. also I had to remove some material in the supporting parts so the stand could rotate to the minimum angle.
I also updated the files in the github repo.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjY5NzAsInB1ciI6ImJsb2JfaWQifX0=--dcd0920e7167aa6fc2c4cf9c69c11cb5bb5f65b3/image.png)


## Entry 10

Today I finished the CAD by designing a case for the XL6009E1 boost converter. 
![Screenshot 2026-06-05 160744.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjc2NzcsInB1ciI6ImJsb2JfaWQifX0=--e08982120373cb60549ba996a4ed4156fde79ec8/Screenshot 2026-06-05 160744.png)
I made four elongated holes so the copper wires could pass and associated for each pin its name with the hole

![Screenshot 2026-06-05 160819.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjc2NzgsInB1ciI6ImJsb2JfaWQifX0=--037f5e265ce4bbfa64ddc468b30a356e72613436/Screenshot 2026-06-05 160819.png)
I used M3 heat set inserts and M3 12mm countersunk flat head crossed screws to connect the case with its upper part.
I also replace the hex bolts in the pc stand assembly that connects the mechanism with the fans with the same screws (but 16mm instead of 12mm) as it is more accurate.
![Screenshot 2026-06-05 160357.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjc2NzksInB1ciI6ImJsb2JfaWQifX0=--51a69b64a2df303c8d122c72d451628d72071da6/Screenshot 2026-06-05 160357.png)
![Screenshot 2026-06-05 160858.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjc2ODAsInB1ciI6ImJsb2JfaWQifX0=--956e3f29ba69b216c5d875cdecd4afd0579329ff/Screenshot 2026-06-05 160858.png)

## Entry 11

After assembling my 3d printed parts, I started working on the electric aspect of my project. It is my first time building something irl, and maybe the second time I touched a soldering iron, so I learned a lot today and got more used to building things. So I assembled the fans and fixed them with screws and bolts to the pc stand.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjc5NTQsInB1ciI6ImJsb2JfaWQifX0=--ea7d3bb7c33533df078756886082596009fce738/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjc5NTUsInB1ciI6ImJsb2JfaWQifX0=--68904543739bd9f5c9dd49389057a937996dc2b9/image.png)
I also soldered everything and used all the parts needed in my project.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjc5NTYsInB1ciI6ImJsb2JfaWQifX0=--ebd4b018a5be167af822e96da1b356ee9c8a7469/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjc5NTcsInB1ciI6ImJsb2JfaWQifX0=--52043f3f63e5a56c7ff61c98037911b23ee8e4a2/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjc5NTgsInB1ciI6ImJsb2JfaWQifX0=--3f49a0a4834a29e9d965e2becf917cbf54a3d25c/image.png)
One of the issues that I have encountered are with the pin IN- of the boost converter. the electric wire broke and fixing it was hard. 

I'm really proud of the progress I made so far even though the circuit didn't work. However I tried to find the real problem and proceeded to debugging. the voltmeter showed 0.4V on the input side of the boost converter, when it should have been 5V from the PC. The XL6009E1 accepts a minimum voltage of 3V, which way more than what my PC emitted.  I used other PCs to compare and see if the problem was my PC or something else and every time I got a very low voltage so I knew the problem was the USB-C cable I was using, as it was really old and not used in a long time. So I will get  a 3.7V li ion battery and test my wiring with it before sacrificing a new USB-C cable.

## Entry 12

After some troubleshooting and realizing that the problem was from the USB-c cable that couldn't pull 5V from the PC, I switched to two LI-ION batteries. after removing the USB-C cables and soldering the battery case wires the design finally worked and the fans started cooling. I then adjusted the boost converter so it can give the power needed for the fans to work comfortably.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkwMTEsInB1ciI6ImJsb2JfaWQifX0=--f2c39821369eae634e3a1d9cc117e4a052c54405/image.png)


## Entry 13

finally ending my project with the zine page. I made a cool black and white design with canva because I printed my project with white filament.
![THE custom PC stand.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkwNjAsInB1ciI6ImJsb2JfaWQifX0=--5b3c2525bc9139d2ab0f68240fc4b03431f39ed2/THE custom PC stand.png)
