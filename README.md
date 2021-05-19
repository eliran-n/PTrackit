# PTrackit
Package Tracking Manager 
-------------------------

The App enables to track for a registered mail. Once you enter a tracking number to check the status,
all the deatails on the package will be print to the main text box (Last Check - Date & Time, Current Status, Total days of delivery, Source & Destination country and additional tracking information). And at the same time it will automatically be stored in a database (locally - using sql lite). 

The requested tracking number will appear on the right
panel of the App - colored according to the status of the package marked by the color legend at bottom of the App. 
Every new tracking number will be added to the right panel, 
While existing tracking number will just be updated in case of a return tracking check. 

The user will be able to clear the Delivered tracking numbers from the list (database) and just keep tracking on "In transit" packages. 
Selecting or Highlighting a tracking number from the right panel will print out the last information to the text box.
You can delete single tracking number, multiple or all of them from the top panel.
You can expending the view of the app or using it in compact view mode.

The App was written in Python environment using Tkinter GUI library, sqlite3, google translate library, threading and more.
Based on 17Track API. It supports more than 500 carries & 229 regions. 
The API response translated from Chinese to English and decode status codes to convenient readable translation.

The Demo version doesn't make real API calls. It's creating a random status infomation for demonstration purposes. 
Since 17Track API cost money and only gives about 100 calls per month for free use.
For the real version you can contact me.
