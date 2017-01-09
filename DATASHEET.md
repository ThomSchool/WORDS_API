# WORDS API

Alpha - January 9th, 2017

## NodeMCU program for UART comunication using ESP8266 and respective APIs

The module will create a mesh network using a NodeMCU script and let microcontrollers comunicate with each other like UART direct connection, with a simple addressing method.

## Milestones
 We aim to reach certain endlines in the development of this project. Here are a few of them:
 
### Use Case: Two Arduinos sending a signal
Very basic scenario with one Arduino setting the ESP as hotspot and the other one connecting to it. The first one will have a button
connected to and when pressed, will send the signal to the second one, which will turn on the onboard LED and send back confirmation,
the first one will then blink the onboard LED to show that a confirmation has been received
