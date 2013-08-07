idDHTLib
=======

Interrupt driven DHT11 & DHT22 library

	VERSION: 	0.0.3

	PURPOSE: 	Interrupt driven Lib for DHT11 and DHT22 with Arduino.

	LICENCE:	GPL v3 (http://www.gnu.org/licenses/gpl.html)

	DATASHEET: http://www.micro4you.com/files/sensor/DHT11.pdf

	DATASHEET: http://www.adafruit.com/datasheets/DHT22.pdf
	
	Based on idDHT11 library: https://github.com/niesteszeck/idDHT11

	Based on DHTLib library: http://playground.arduino.cc/Main/DHTLib

	Based on code proposed: http://forum.arduino.cc/index.php?PHPSESSID=j6n105kl2h07nbj72ac4vbh4s5&topic=175356.0

	Changelog:
	
		v 0.0.1
		
			fork from idDHT11 lib
			
			change names to idDHTLib
			
			added DHT22 functionality
		
		v 0.0.2
		
			Optimization on shift var (pylon from Arduino Forum)

		v 0.0.3

			Timing correction to finally work properly on DHT22 (Dessimat0r from Arduino forum)

Thanks to Dessimat0r we finally can say that is ready, please try it and if you have some trouble I'll glad to accept changes that solve this problems.