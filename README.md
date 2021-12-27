# Emergency-Ventilator
Emergency Ventilator for coping high demand
# Introduction
Critical patients with corona disease have severe coughing, shortness of breath and sore throat, in most cases they cannot breathe on their own. Then they need artificial respiration through a ventilator. The ventilator works to carry oxygen and emit carbon dioxide to the patient's lungs.
But the number of ventilators in Bangladesh is less than required. Durbar Kandari Emergency Ventilator has been created to solve the problem of this ventilator crisis in the country.
Durbar Kandari Emergency Ventilator which is made with very low cost indigenous technology and which is also very easy and safe to operate. This ventilator has been redesigned following the model of Emergency-Ventilator developed by the world renowned MIT in Corona.
# Ventilator Features
# 1. Mode
Our ventilator basically supports volume control mode. It presses an ambu bag with the help of two mechanical arms connected by a rack and pinion. Also with the help of pressure sensor can understand the value of pressure and the value of volume from the displacement of the rack and can implement the modes accordingly.

Currently it is possible to implement two modes in our ventilator. These are Assist Control Mode (AC) and Manual Mode.
# AC Mode: 
In this mode our ventilator user has to set the values ​​of Tidal Volume, Frequency, FiO2 and PEEP. The ventilator will then provide the patient with a certain volume of oxygen-rich air at a specific frequency. In this case, if the patient tries to breathe, the complete Breath Cycle will be completed. ACV is unsuitable for patients who breathe fast.
# Manual Mode: 
In this mode our ventilator user has to set the values ​​of Tidal Volume, Frequency, I / E Ratio, FiO2, PEEP, Peak Pressure. In this mode the ventilator will supply oxygen rich air of a certain volume to the patient according to a specific I / E ratio. In this case the complete Breath Cycle will be completed at a specific frequency.
# 2. Alarm
Our ventilator has a variety of alarms to ensure patient safety. Alarms - Exceeded PIP Pressure, Under Pressure, Tube leak, Unmet Tidal Volume, Over Current Fault and Mechanical Fault Alarm.

It is important to note that each alarm will display a defect on the display.
If the patient's inspiratory pressure is ever higher than the prescribed peak inspiratory pressure, the ventilator will automatically stop pressing the ambo bag and alert the person on duty via an Exceeded PIP Pressure alarm.

If for any reason the Breathing Circuit is disconnected, it will alert the person concerned through Tube Leak Alarm.

Similarly, if the value of inspiratory pressure is comparatively low due to any leakage or any other reason, the ventilator will notify the person on duty through Under Pressure alarm.
Unmet Tidal Volume alarm will alert the user if our device provides less Tidal Volume than the required Tidal Volume of the patient.
# 3. Android App
By activating the Bluetooth of the mobile phone and launching the app created for the ventilator, the user's mobile connection with the ventilator will be established and the user will be able to control the device through his mobile.By going to the mobile app, the user can set the value of BPM, Tidal Volume, PEEP etc. as per his requirement.When the value is set the device will send a confirmation message to the user and the device will start working as per instructions as soon as the device presses the “1” button and “start” button. Through the app of the phone, the user can also see the graph of the patient's pressure flow.
If the device exceeds a certain limit of current, it will alert the user via Over Current Fault Alarm.
Mechanical Fault Alarm will alert the person concerned when mechanical fault occurs.
# 4. Web App
Simultaneous retrieval and monitoring of several ventilators through a web app via Internet connection is being prepared to monitor multiple patients simultaneously. In this case, the doctor will be able to connect to the ventilator through the Internet and monitor the ventilator. Physicians can monitor multiple ventilators simultaneously through the web app. Work is underway to improve this feature.Through this web app, specialist doctors from any part of the country will be able to take care of the patient and give necessary advice. As a result, patients in remote areas will get the benefit of medical treatment under a specialist doctor. The web app will also have a specific database, which will store all the information including the patient's previous information which will make it easier for the doctor to understand the patient's condition and give treatment.The doctor will be able to send the necessary directions to the phone according to the patient's condition and the ventilator operator will operate the ventilator according to those instructions.
This ventilator can be manufactured for only 30 to 35 thousand rupees as it uses indigenous technology and is designed keeping in mind the needs of patients with corona. The ventilator was developed by Durbar Kandari Ruet, a team formed during the Corona Epidemic and Lockdown.The students of RUET associated with this have completed the work of this ventilator by coming together from different parts of the country through internet and they are working day and night to improve this ventilator.
The ventilator crisis in Bangladesh will be solved through Durbar Kandari Emergency Ventilator - this is our expectation.
# 5. About Files
-- The compressed file containing the video of operation of the ventilator can be found in the link:
https://drive.google.com/file/d/1EURlDSFRqueynMlFAGd0fwvN7exS0qcK/view?usp=sharing

-- The uploaded file "Emergency_Ventilator_Details.pdf" contains a detaild doucumentation to provide a comprehensive description of the work.

-- Codes of user interfacing and other relevant codes and design files have been provided in the uploaded file section.
# 6. Circuit Part
## Circuit:
The Circuit file named "DK-E-VENT-V2 Design" can be openned by Protues 8.7 or above.
The file contains RT( Real Time controller part) and UI (User Interface part)
Both the part integrated in circuit in one PCB board. 
There is two option in Proteus, “Schematic Capture” where Circuit connection and controller would be found. Another is “PCB layout” where you can find PCB board design in single layer
Different types of sensors were also included for measuring different parameters. All the component was selected after doing calculation of some parameters which should be in a ventilator.  
The details is given in  Figure : Schematic design of Real time Controller and User Interface.

## Real Time (RT) Control Unit: 
Both of the unit was embedded in same board, designed really compact and professionally. Arduino Mega Pro was used as microcontroller and BTS7960 motor driver to control the motor. This motor driver had enough voltage and current to drive the selected motor. The circuit had 12V, 5V and 3.3-volt power to run different components. So, DC-DC buck converter was used to power up the right components according to their tolerable voltage with references of datasheet. There was a buzzer for alarm. It was designed as all the sensor could easily connect with it. There was also Real time controller (RTC). Fuse was also included in design. Capacitor and resistors were placed where necessary. There were also two limit switches to ensure exhale and inhale. Figure Schematic design of  Real time Controller, gives a clearer perception on it.
## User Interface (UI): 
Some part of User Interface was on PCB and other was on body of Mechanical structure. Here Arduino mega pro was also used as microprocessor. Display and keypad were attached in main board.   In addition, Bluetooth module and wifi module was in design to make this device as IOT. All the component were powered with buck converter and capacitor and resistors was used where necessary. A picture in Figure Schematic design of User Interface shows a better view. 
Moreover, Figure: PCB design of Medical Ventilator shows a PCB design picture.

# 7. Mechanical drawing
Emergency Medical Ventilator Design: Opening Instructions

Application for SOLIDWORKS Part files (.SLDPRT), Assembly files (.SLDASM), and Drawing files (.SLDDRW): SOLIDWORKS 2021
Complete assembly file: Ventilator Full assembly.SLDASM (Open with SOLIDWORKS 2021)
For any previous SOLIDWORKS versions, open STEP Files > Ventilator full assembly.STEP. Use PDFs within Drawing Files folder to view drawing files.
Upper Portion part & assembly files:

New Folder >
Ambu Holder 2.sldprt
Bag Cover 1.sldprt
bc25.sldprt
Ambu > ENSAMBLE AMBU.SLDASM
![alt text](https://github.com/thecodebuzz/FileSizePOC/blob/master/TheCodebuzz.png?raw=true)
This assembly contains these part files:
AMBU.SLDPRT
AMBU2.SLDPRT
AMBU3.SLDPRT
AMBU4.SLDPRT
AMBU5.SLDPRT
AMBU6.SLDPRT
AMBU7.SLDPRT
AMBU9.SLDPRT

# License
The licensing information is given in the image below.
![](oshw_facts.jpg)
