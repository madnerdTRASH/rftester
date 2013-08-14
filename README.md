Dependancies
===
Wiringpi
* apt-get install git-core
* git clone git://git.drogon.net/wiringPi
* cd wiringPi
* git pull origin
* ./build



Compile the program
===

gcc RFtester.cpp RCSwitch.cpp -o RFtester -lwiringPi

To use it
===
./RFtester PIN

* Where PIN is the gpio where the receiver is plugged in:
* http://blog.idleman.fr/wp-content/uploads/2013/02/raspin.jpg
