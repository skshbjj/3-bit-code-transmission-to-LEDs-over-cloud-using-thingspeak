Connections are pretty simple.
Connect 3 LEDs via !k resistors each to 3 digital pins of NodeMCU. Connect ground from 
NodeMCU to cathodes of each LED. Finally upload the code to NodeMCU via USB. Don't 
forget to give Wi-Fi creadentials and channel code. You can use my channel code as well 
as i have kept it public.


Thingspeak

Sign-up or Sign-in and make your channel. Get the channel code and put in your arduino 
code. Create 3 fields, one for each LED.
Get the link given in API keys. Go to the link and alter the link by changing field
values from 0 and 1 or any number and see the results on LEDs.
eg. field1=0field2=1field3=1  will make your 2nd and 3rd LEDs glow. 011 message is 
in the form of LEDs.

You can use as many LEDs as you want. How to do this using Blynk app? Check my 
another repository for the same.

