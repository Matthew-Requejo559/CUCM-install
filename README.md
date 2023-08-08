![Uploading 007.png…]()
![Uploading 006.png…]()
![Uploading 005.png…]()
![Uploading 004.png…]()
# CUCM-install
CUCM install in VMware Player 17
![001](https://github.com/Matthew-Requejo559/CUCM-install/assets/136190678/e9bd66bd-b6b8-4907-930c-5bc00f35839a)
![Uploading 003.png…]()
![Uploading 002.png…]()
![008](https://github.com/Matthew-Requejo559/CUCM-install/assets/136190678/b2f3ae70-043f-4292-a2c4-8373b2bb2396)

This is what you will see if you click test

during set up in bridge mode, the NTP server was unreachable. I think it is because i switched bridged and NAT settings a few times during setup. I had previously set up this server in NAT mode and 
then changed it to bridge mode and updated the IP scheme manually later. I tore it down to make this walkthrough, and tried to set it up in bridge mode first, but it messed up. I had to revert back 
to NAT mode and restart the machine a few times, then change the IP scheme manually again. which is ok, because it forces you to interact with the CUCM CLI. 

if you run into a 404 error when trying to log into admin portal from the web GUI for the first time, try restarting the tomcat service from the CLI with: utils service restart Cisco Tomcat
