"# digitalworld2d - F07 Group"


Background:

Singapore University of Technology and Design (SUTD) is gearing towards being the heart of Smart Nation by building a Smart Campus that utilises technology, networks and big data.

Problem Statement:
Students often find searching for empty common rooms tedious as they have to manually check all the individual rooms in the hostel. Not only time-consuming, it is often mentally draining when one has searched the entire block yet found no available room. Hence, our group identified THE INABILITY TO CHECK THE AVAILABILITY OF COMMON ROOMS IN SUTD HOUSING as our problem.

In this 1D project, we aim to develop an application which informs the student population of the availability status of common rooms in the hostel through the application of sensor technology.

The following codes run the RPi sensors, RFID readers, Telegrambot and Kivy GUI.

1. card.py
This code imports libdw library to update the Firebase database.
When table users tap their cards on the RFID readers, it will automatically update their name in Firebase under the corresponding table's values.

2. checker.py
This code imports gspread and oauth2client

3. RFIDwrite.py



 To run our files: you will need to install modules
 1.libdw
 2.KivyApp
 3.mfrc522
 4.gspread
 5.oauth2client
 6.telepot
 7.spidev
 and have a file named secrets with your credentials for telegram bot and firebase.(provided for grading)
 We will als need a json file named client_secret for the credentials of google spreadsheet(also provided for grading)
 use pip3 install for all the modules above.


 enable spi using raspi-config
