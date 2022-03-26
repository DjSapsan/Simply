# Simply
## Starts 2 different docker images from first-time-ubuntu scratch. Use only on a hosted VM or with VPN.
_tich92/siteattconsole, erikmnkl/stoppropaganda_

After you installed Ubuntu:
 
**1. Autostart setup:**
```
crontab -e
```
Select number 1 (Text editor nano)

At the bottom add the next line:
``` 
@reboot /usr/sbin/rasha_parasha
```
Hit:
Ctrl+S, Ctrl + X
 
**2. SINGLE LINE COMMAND. After that everything is working:**
```
sudo wget https://pastebin.com/raw/MNWnLCLn --output-document=/usr/sbin/rasha_caput.sh && sudo wget https://pastebin.com/raw/Ztz5YxLR --output-document=/usr/sbin/rasha_parasha && sudo sed -i -e 's/\r$//' /usr/sbin/rasha* && sudo chmod +x /usr/sbin/rasha* && sudo /usr/sbin/rasha_caput.sh ; sudo /usr/sbin/rasha_parasha ; echo done
``` 
**3. If docker doesn't run then start the script again:**
``` 
sudo /usr/sbin/rasha_parasha
``` 
Check docker:
``` 
sudo docker ps
``` 
**4.  To change the IP and to download the latest versions it's enough to stop/start the VM on the web hosting interface.
    To just use the latest image release - type: sudo /usr/sbin/rasha_parasha**
    
   **SINGLE LINE COMMAND can be type at the any moment to fix something or to get the latest updates**

## SINGLE LINE COMMAND never changes, even in the case of scripts changes. You can always use it in the future setups

Additional info: for all docker operations you'll need to use 'sudo'

Example result on Azure (4x  1vCPU, 4 GiB RAM):
![image](https://user-images.githubusercontent.com/12209464/157055302-8aa3e306-d9b7-458d-a284-d4e5899911ec.png)
