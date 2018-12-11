# otto_touch_sensor
This is a easy software to use a Otto Robot with a touch sensor.

You can find the Otto library in https://github.com/OttoDIY/DIY/tree/master/libraries

	This switch three modes
	Mode 1: Otto avoid obstacles
	Mode 2: Otto follow the hand
	Mode 3: Otto dances!
	
			--^--       <== Touch Sensor 12
          	 --------------- 
        	|     O   O     |
	        |---------------|
	YR 3==> |               | <== YL 2
         	 --------------- 
		    ||     ||
	RR 5==>   -----   ------  <== RL 4
 	         |-----   ------|

	 ==> Ultrasound Sensor:
	     -- Trigger 8
	     -- Echo    9
	 ==> Buzzer    11
