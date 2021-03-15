# PTrackit
Package Tracking System 
-----------------------

The App enables to track for registered mail. Once you enter a tracking number to check the status,
all the deatails on the package will be print to the main screen (Last Check - Date & Time, Current Status, Total days of delivery, Source & Destination country).
And at the same time it will automatically be stored in a database (on user machine - using sql lite library). 

The requested tracking number will appear on the right
panel of the App - colored according to the status of the package marked by the color legend at bottom of the App. 
Every new tracking number will be added to the right panel, 
While existing tracking number will just be updated in case of a return check. 

The user will be able to clear the Delivered \ Expired tracking numbers from the list (database) and just keep tracking on "In transit" packages. 

The App was written in Python environment using Tkinter GUI library, sqlite3, google translate library, threading and more.
Based on 17Track API. It supports more than 500 carries & 229 regions. 
The API response translated from Chinese to English and decode from status codes to convenient readable translation.
