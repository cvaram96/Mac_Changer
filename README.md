# Mac_Changer
You should install python3

clone this python file

go to directory of the file with your terminal


sudo python3 mac_changer.py --help to identify the arugments


first get your interfaces names by using ifconfig command


Now you can put the interface name and new mac address which you prefer with th following command


I like to change wlan0 interface mac address to 00:11:22:33:44:55


sudo python3 mac_changer.py -i wlan0 -m 00:11:22:33:44:55

