# autoFanStartRaspi


Script to autostart on raspberry pi tho controll fan speed on board with transistor that can controll form 0 to 255 fan voltage from o to 5 volts.
The transistor drain is controll by PWM value form 0 to 3.1 Volts.

Made by my selft to reduce temperature and fan noise.



It use pigpio library and some python scripts.

{ http://abyz.me.uk/rpi/pigpio/pigs.html }


U can autostart it by adding:

"
sudo pigpiod
/home/pi/Skrypty/autostart/startFan.sh &
"
At the botom of the file  "/etc/rc.local"  before  "exit 0"

The "&" means it run in background.


![Screenshot](autoFanStartRaspiHtop.png)

