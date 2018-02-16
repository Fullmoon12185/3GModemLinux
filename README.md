# 3GModemLinux
Brief for setup an internet connection on Raspberry Pi with SIM5320 Modem.
Materials:
1. Raspberry Pi 3
2. SIM5320 Modem (with battery + GSM Antenna + USB cable for Pi)
3. 2G/3G SIM with data enabled (line activation done with a real phone)

Bootstrap:
1. SIM activation on real phone
2. Gather APN from GSM service provider

Procedure:
1. Follow instructions on https://github.com/sixfab/rpiShields/tree/master/tutorials/tutorial3
2. Setup APN
3. Run test and verify pppd0 interface created: # sudo pppd call gprs
