## Using the Flipper Zero UART bridge and FZEEFLasher.com to install the latest version of Marauder FW

This tutorial is using Momentum FW mntm-001 and a Rabbit Labs Minion board but other firmware and ESP32 boards should also work with slight modifications to the workflow

1.	Start the Flipper and unplug from PC, remove the board if inserted
2.	Start the UART Bridge by selecting GPIO from the main Menu \
	<img width="300" src="https://github.com/nerdyjedi/tutorials/assets/102484166/75ed3117-7dec-460a-b708-5e16d11f8c9f"> \
	**newbie mistake: it's not inside the apps menu.  Scroll if you don't see GPIO** 
3.	Select USB-UART Bridge \
    <img width="300" src="https://github.com/nerdyjedi/tutorials/assets/102484166/b9f0dba7-674a-4e41-8ace-785fc65839d2"> 
4.	While holding the boot button on the board, insert the board into the Flipper Zero GPIO pins and keep holding it for a few seconds.
	On the Minion, the boot button is the left eye.
5.	Connect your Flipper Zero USB to your computer
6.	Open Google Chrome and go to https://fzeeflasher.com/
7.	Click the Connect button in the upper right corner
	![image](https://github.com/nerdyjedi/tutorials/assets/102484166/2ff9b931-e381-49d2-9965-19a7d2273552)
8.	Select your Flipper Zero connection. \
   	![image](https://github.com/nerdyjedi/tutorials/assets/102484166/8a479637-4b82-46af-800c-baaf7f1af1e8) \
	If you don't see your Flipper Zero in the list, try re-inserting the board with the boot button pressed and refresh the page. \
	If you **still** don't see it, make sure you have a known good data cable and not a charging-only cable.
10.	You should see Connected successfully and Try hard reset.  **just wait, do nothing** FZEE Flasher is getting more information from your board.
    ![image](https://github.com/nerdyjedi/tutorials/assets/102484166/eecaaa19-f7d1-45d6-a54f-772bd03174f0)
11.	Select your board model and the firmware/version you'd like to flash the click the Program button
	<img width="700" alt="image" src="https://github.com/nerdyjedi/tutorials/assets/102484166/33b5f4c0-eecf-4e70-b92a-1437f6e977b0">
12.	The flashing process will take a few minutes and you'll get a green Flashing Process Completed message
	<img width="700" alt="image" src="https://github.com/nerdyjedi/tutorials/assets/102484166/74f3bb9e-a9db-4091-b338-d5075050fe5f">
13.	Press the back button > left arrow on the flipper to exit the UART-USB bridge and unplug your flipper USB connection
14.	On the flipper, run [ESP32] Wifi Marauder.  In Momentum and Xtreme, the app is Apps > Wifi > [ESP32] Wifi Marauder
	<img width="300" src="https://github.com/nerdyjedi/tutorials/assets/102484166/40f0f310-7ee4-48bf-9f8f-4837319c6bf8)"> \
	**newbie mistake:  The app is [ESP32] Wifi Marauder, not [Mayhem] Wifi Marauder 
15.	In the Marauder app, select Reboot \
	<img width="300" src="https://github.com/nerdyjedi/tutorials/assets/102484166/7cb5b8da-335b-403a-9827-cfe46945b3ae"> 
16.	Once the board is rebooted, scroll up to see the version of the board firmware \
    <img width="300" src="https://github.com/nerdyjedi/tutorials/assets/102484166/36d66932-ed83-4363-b233-a20ce5cf1d60"> 







	
