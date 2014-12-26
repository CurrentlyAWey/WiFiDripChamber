WiFiDripChamber
===============

EID 2014 Project, Professor Petrillo, WiFi Connected Drip Chamber


+++++++++++++++
+++  FILES  +++
+++++++++++++++


Links and General Info.txt contains external
	links to external distributors, google docs, 
	contact information, etc. Includes Device Access token, Device ID, etc 

Supplies.txt contains a supply list that will be formalized into 
	an excel spreadsheet for price optimization in the future.

Code_Firmware.txt contains attempts to write code and troubleshoot 
	the Spark.io IDE. 

Code_Firmware_SerialOut_Timer.txt contains a version of code that will update an LED Output 
	on pin D0 to reflect when the drop is completing the circuit, and counts the number of
	drops for 60 seconds. 
	It also prints out the number of drops per minute to a serial port. This can be used to 
	troubleshoot, and can later be revised by simply keeping one value of count as the incrementing 
	value the machine can "play" with, and storing that value into a Spark.variable at the end of each
	minute, for the internet to access. Thus, the value retrieved on the internet will lag behind 
	by one minute. This can be adjusted.

CostsSpreadsheet is a partslist detailing costs.

+++++++++++++++
+++ FOLDERS +++
+++++++++++++++


Contained in the Progress Report folder are status updates

Contained in the Pictures and Documentation folder are photos 
of prototypes and parts.

Contained in the Public Relations folder are presentation files
we use for pitching ideas to investors and business professionals, 
including pptx, ppsx, and scripts.

Online Sources is a Bibliography of sorts.

Link to Kickstarter: https://www.kickstarter.com/projects/1343639538/1460072307?token=864f7c7a
Link to Website: http://smartdripchamber.wix.com/wifidripchamber
Link to Youtube Video: http://youtu.be/BE1DqKXYkKc
