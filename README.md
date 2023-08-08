# CUCM-install
CUCM install in VMware Player 17
![001](https://github.com/Matthew-Requejo559/CUCM-install/assets/136190678/e9bd66bd-b6b8-4907-930c-5bc00f35839a)
![002](https://github.com/Matthew-Requejo559/CUCM-install/assets/136190678/b7a4df3f-0948-4919-a273-02eef1210e8a)
![003](https://github.com/Matthew-Requejo559/CUCM-install/assets/136190678/7b824307-6006-470b-ae83-7cf94565c9d2)
![004](https://github.com/Matthew-Requejo559/CUCM-install/assets/136190678/43d0b0cf-b0c5-4c77-9de0-ea20f3e73b63)
![005](https://github.com/Matthew-Requejo559/CUCM-install/assets/136190678/2db6e934-94cc-4b28-a1c4-0a6d5a7e63c3)
![006](https://github.com/Matthew-Requejo559/CUCM-install/assets/136190678/17f1c5fc-dde6-444a-9e7e-1556fa5b99f9)
![007](https://github.com/Matthew-Requejo559/CUCM-install/assets/136190678/2002efed-d2cc-4369-9ba3-6c5a1bdb35e3)
![008](https://github.com/Matthew-Requejo559/CUCM-install/assets/136190678/b2f3ae70-043f-4292-a2c4-8373b2bb2396)
![0001nat](https://github.com/Matthew-Requejo559/CUCM-install/assets/136190678/70dea517-9361-4d26-afeb-72c3de43d6cd)
![0002vmnet](https://github.com/Matthew-Requejo559/CUCM-install/assets/136190678/3852c24c-95fd-4313-ae24-125001f9ab9b)




This is what you will see if you click test

during set up in bridge mode, the NTP server was unreachable. I think it is because i switched bridged and NAT settings a few times during setup. I had previously set up this server in NAT mode and 
then changed it to bridge mode and updated the IP scheme manually later. I tore it down to make this walkthrough, and tried to set it up in bridge mode first, but it messed up. I had to revert back 
to NAT mode and restart the machine a few times, then change the IP scheme manually again. which is ok, because it forces you to interact with the CUCM CLI. 

if you run into a 404 error when trying to log into admin portal from the web GUI for the first time, try restarting the tomcat service from the CLI with: utils service restart Cisco Tomcat
