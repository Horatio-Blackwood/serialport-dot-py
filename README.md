serialport-dot-py
=================

A wrapper around the PySerial SerialPort object that handles threading and provides customizable incoming data handling.  
serialport-dot-py takes the great work of pyserial and makes it easier to use python to get your serial port rocking.

The project uses a simple .cfg file for configuring your serial port, which allows you to specify things like the port's 
name and baudrate.

====================================
Some Sample Code:
====================================
from serialport import SerialPort

myPort = SerialPort()
myPort.sendBytes(someByteArray)
====================================

That's it.
