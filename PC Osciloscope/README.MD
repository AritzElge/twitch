# PC Osciloscope
Keeping in mind sharing osciloscope readings with the audience during twitch live streams a small Data Adquisition System is build using an Arduino UNO.

## Basic Theory
We won't be explaining anything about ADC or other microcontroler peripheral here. Arduino UNO is set to 'read' its analog input every X (where X is 
a preprogramed microsecond variable) time. Once the data is readen, it's send by Serial comunication (which is conected to the USB).

- First version: The Serial port comunication is matched with the Serial plotter of the Arduino IDE in order to see the data adquired on screen.
