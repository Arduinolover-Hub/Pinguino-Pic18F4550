# Pinguino 18F4550
Pinguino board, based on Pic18F4550, Programing Arduino and Pic

The well know Pinguino based on the Pic 18F4550

1. Main features:
  -Open Source
  -Programmable by his own IDE, Pinguino IDE
  -Language of programming : Arduino (Some little changes)
  -28 Digital Outputs
  -5 Analog Inputs
  -2 PWM Outputs
  *+5V Power Pin
  *+3.3V Power Pin
  -Powering by USB or External Source 9-12V

2. Schematic Diagram
  First at all, the Pinguino Project is Open Source which means that
  We can access the project information from the 
  official website : https://pinguino.cc/
  We will find a different models of boards, in this case first 
  We need to go to the basic schematic circuit and based on it, 
  we are going to make changes or add additional circuit, but the the basic circuit will always stay. 
  So in the next image We can take a look of the basic pinguino board circuit based on pic18F4550

  In the previous image, We have to pay attention to a very important aspect,
  and this is the power supply, We can see that just it shows an USB power supply, 
  so We need also to supply by external source. ,
  Now We are going to make some changes and add other circuit part to have our final Pinguino 18f4550 board.

  You can also download the Schematic in PDF :
  https://drive.google.com/open?id=1NJqQvpIOKpWS3L5fnxbpxtni6j850n4x

  So let's take a brief look of the schematic circuit, and let's begin from the USB connector, 
  We use and Femlae USB Type B, which is big but really easy to solder and place. 
  You can change it for another SMD USB connector but pay attention to the correct because you can have surprises.
  
  The next part is the External power supply, and for that You are using the very common chip 7805 
  (We can supply 9-12V for detail info please consider to check the datasheet).
  
  Also We placed a +3.3V regulator, with the chip 1117-3.3V, please be carefully 
  when you buy it, because also these chips come for negative voltages.
  
3. PCB Layout

  Before We continue with the PCB layout, it is important to indicate that You can use any software for PCB Desing,
  believe me there are many options, even if you use the best software it will not mean that you are the best pcb desinger,
  so in this case We are going to use the Powefull Altium Designer highly recommended if you want to enter in the pcb design world.

  So after We finished and check our schematic circuit We need to switch from schematic to PCB layout.
  Here after we finish the pcb layout We can get the Gerber files, there are two kind of gerber files we have to pay attention to it, 
  the first GerberX2 and the other Gerber RS274X, most of the manufacturer use the second one Gerber RS274X, 
  in some software we will just GerberX2 and Gerber (In the case of Altium Designer).

  You can also download the GerberFiles: 
  https://drive.google.com/file/d/1yC0TuM9uLK201JNJemyuS6bisvzlNaF2/view
  
4. 3D VIEW

  One of the features of Altium Designer is the 3D visualization, the 3d visualization is important and it give us the posibility
  to see and check our PCB and how it would be in real, also it can show us the components distribution and dimensions.
  
5. PDF 3D

  Something very powerful from Altium Designer is the 3d PDF, You can export the 3d view into PDF and open it anyplace you need. You can rotate your 3d view in PDF
  
6. How to Order on JLCPCB
   You have to create and user account, it is free and will keep all your order historial
  6.1.Upload the Gerber fileshttps://jlcpcb.com/IAT
  6.2.IndicatetheFeatures
  6.3.Addyourshippingaddress
  6.4.Make the payment and finish the order
  6.5.Receive your PCB

7. Why JCLPCB?
  JLCPCB has been at the forefront of the PCB industry. With over 14-year continuous innovation
  and improvement based on customers' need, we have been growing fast, and becoming a leading global PCB manufacturer,
  who provides the rapid production of high-reliability and cost-effective PCBs and creates the best customer experience in the industry.

  -Most Efficient, Economic, Innovative PCB Solutions
  -Higher Quality
  -Lower Cost
  -Faster Delivery

8. Building the PCB
  Attached you will find the BOM (bill of materials) needed to build the PCB, as you can see in the list 
  you can the designator that You can check also with the schematic circuit.

  You can donwload the BOM:
  https://drive.google.com/file/d/1AgsF1ps9nSV1UrnJHSLbTd9f7wHG-KMu/view
  
9. Programming the Board
  In order to program the board We need to donwload the Pinguino IDE, open source platform which uses the same language 
  than the Arduino. You can download here: https://pinguino.cc/
  
  The Pinguino IDE works with textual programing and also Block programing.IMPORTANT.
  When you conect the board you have some seconds to upload your program after that 
  You need to press reset boton to load the program again. Once your program is uploaded it will automatically reset and ejecute the program.
  
10. Testing the Board
  Now We can work with our board like an Arduino. Before you upload the sketch, you should configure the board like the next image

  You can donwloadtheBootloader:
  https://drive.google.com/open?id=1Slk5UCp5sOUGAKShT79YiN_5CUlCOX_E
  
11. Thanks
  Thank you JLCPCB and Pinguino Project
  
  JLCPCB: https://jlcpcb.com/IAT
  Pinguino: https://pinguino.cc/
