# EX.NO: 01     Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools   


## Aim:
To design and implement a CMOS inverter circuit using Cadence EDA tools, analyse its electrical characteristics, and understand the fundamental principles of CMOS technology, including the design process, layout, and simulation techniques.


## Tools Required:

•	Personal Computer

•	Cadence Virtuoso Software


## Circuit Diagram:
 
 ![IMG-20241115-WA0008](https://github.com/user-attachments/assets/2620c499-d1c4-429a-bfce-d25dab4d34e3)


## Schematic Simulation:

PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION
Commands to get into Cadence
1.	Right Click and open the terminal window
2.	Type the following commands as follows and press enter.
•	csh
•	source /cadence/install/cshrc
•	virtuoso 
Procedure for Schematic simulation using Cadence

1.	Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…”
2.	Close the 2nd window
3.	Use 1st window i.e virtuoso window(CIW) for further processing.
i.	Create a New Library
ii.	Create Schematic Cell view.
iii.	Create the Symbol for schematic Cell view.
iv.	Create the test Cell view.
v.	Analog simulation by spectre


i)	Procedure for Creating New Library.

•	File –New – Library

•	Name : Give name for ur library Ex: VLSILAB_EXP_1

•	Enable Attach to an existing technology library, Click OK

•	Attach the library to the technology library gpdk045.Click OK
ii)	Create Schematic Cell view.
•	Go to 1st window i.e virtuoso(CIW)

•	File-New-Cell view

•	Setup the new file form
	  Library: Select the one you a created.
	  Cell : Give the experiment name Ex: Inverter View_Schematic
	  Type: Schematic press OK
•	Add the required components from the libraries and make the connections.

• Go to instance fixed menu or use shortcut key “I” from keypad to go instances

•	Click on browse. This opens the library browser

•	Now select the appropriate library for components like 
• Gpdk45 ------------------------nmos1v,  pmos1v

• Create Input and Output pins

•	Make the connections by using fixed narrow wire key

•	Click Check and Save button

![Screenshot 2024-08-28 130135](https://github.com/user-attachments/assets/be67e1e7-ff6b-4f6e-b399-08c82c441b7e)



 
iii)	Creating the Symbol for schematic Cell view

•	In the schematic window, execute 

•	Create – Cell view – From Cell view

•	The cell view from cell view window appears

•	Check Lib Name, Cell Name, From View name must be schematic Press ok

•	Now Symbol generation form appears. Click Ok If No changes required

•	A new window with with default symbol is created.

•	Edit the symbol if you want to give actual symbol shape else continue.

•	Execute Create-Cell view-from cell view

•	Library Name and Cell Name must be same which you have used for schematic. Press OK

•	Check for the position of pin side.Prss OK

•	Edit for the shape by Create-Shape-Choose required options to edit.



![Screenshot 2024-08-28 000449](https://github.com/user-attachments/assets/c38bb896-4338-43ff-9612-307cbb16bf53)

iv)	Creating the new test cell view

•	Go to CIW window, Execute File-New-Cell view

•	Setup the new file form

•	Library: Select the one you created.

•	Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test

•	View: Schematic

•	Type: Schematic press OK

•	Follow the step 3(ii)  to make the required connections


![Screenshot 2024-08-28 125555](https://github.com/user-attachments/assets/316b629f-d7e1-4a9d-97bc-6f8245609c9b)

 
## Analog simulation by SPECTRE.
•	In test cell view window

•	Launch – ADE L(Analog Design Environment)

•	Execute Setup—Simulation/directory/Host A new window opens

•	Set the simulation window to spectre and click ok

•	Execute Analysis – Choose. A window opens.

•	Select the type and set the specifications and press OK

•	Execute Output s—to be plotted – Select on Schematic

•	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse

•	Execute Simulation -- Net list and Run

![Screenshot 2024-11-16 140104](https://github.com/user-attachments/assets/ef9f5764-2967-4f3b-98aa-4a03c0eee293)



## For Transient Analysis Settings and Output

![Screenshot 2024-11-16 140122](https://github.com/user-attachments/assets/8659d027-d32a-457b-8607-17237260c73a)

![Screenshot 2024-08-28 125704](https://github.com/user-attachments/assets/8423465b-c880-4d3f-a85c-12772266d398)
 
 







 ## For DC Analysis Settings and Output
 
 ![Screenshot 2024-08-28 125734](https://github.com/user-attachments/assets/3e64dfea-1fa4-4f7c-8e29-3c2859914df4)
 
 ![Screenshot 2024-08-28 125526](https://github.com/user-attachments/assets/094cfc52-561f-44dd-a85c-1b6cfcf92644)



 




 




## Result:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
	
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
  	
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











