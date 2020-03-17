# Arduino timer

The main idea is to make a timer  with and arduino, a coin counter ( from and arcade machine) and display the time in a BCD led display.
When idle, the raspberry pi with retro pi installed will be with the usb disconnected, this stops the use of joystick and arcade buttons.
When a coin is introduced in the slot, a pulse is sent to arduino, which starts the timer. Time slots will be 30 min per coin. 
In the last minute the arduino has to start sending an audio signal to advert the user that the time is limited. Then the control board will send a signal to the raspberry pi to disconnect USBs and block joysticks. 

