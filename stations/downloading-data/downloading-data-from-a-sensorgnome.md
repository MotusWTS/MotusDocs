# Downloading Data from a SensorGnome

## Downloading data from a SensorGnome (Version 2) using the web interface

### Equipment

You will need a laptop or a smartphone. Using a laptop is recommended, but a phone will work if needed.

### Connecting to SensorGnome web interface using a HotSpot

1. Stand next to the Motus station with your laptop or smartphone. On your device, look for available WiFi networks (the SensorGnome creates a hotspot).
2. You should see an available network where the name is the SensorGnome’s serial number. Click on that network and enter the password. It’s often the same as the network, which is the SensorGnome’s serial number, or it was changed during set up by you or your collaborators.

<figure><img src="../../.gitbook/assets/image (69).png" alt=""><figcaption></figcaption></figure>

3. A web browser window to the interface like the image below should automatically pop-up. Click either of the hyperlinks to continue to the SensorGnome web interface. If a web browser window does not open automatically, you can open one. If the window does not show the image below, type [http://192.168.7.2](http://192.168.7.2) into the URL bar and hit enter to connect to the SensorGnome.

<figure><img src="../../.gitbook/assets/image (70).png" alt=""><figcaption></figcaption></figure>

4. You will be prompted to enter a password again. Enter the same one as before. You should now see the web interface.

<figure><img src="../../.gitbook/assets/image (71).png" alt=""><figcaption></figcaption></figure>

### Downloading data on web interface

1. To download data, click on the FILES tab in the top bar. Then click the red button that says DOWNLOAD. If there are a lot of files, this can take a while and it may seem like your laptop is not doing anything, but just wait a few minutes. Your browser may show the download as from an unknown source, and the download will not complete until you click “Keep”.

<figure><img src="../../.gitbook/assets/image (72).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (73).png" alt=""><figcaption></figcaption></figure>

2. Save the downloaded folder with another folder named with the Motus station name so that you know where it came from.
3. To download logs (which are helpful for troubleshooting issues), go to SOFTWARE tab, and click DOWNLOAD LOGS button on the top right under “System Troubleshooting”.

<figure><img src="../../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>

4. Save the downloaded log folder with another folder named with the Motus station name so that you know where it came from.

### Additional Motus station maintenance on web interface

{% hint style="warning" icon="bell-exclamation" %}
**Reminder:** Please take screenshots of each tab on the SensorGnome interface so that station operation can be verified and troubleshot at a later date.
{% endhint %}

1. On the HOME tab (i.e., tab with 4 squares), check that the station is getting a GPS fix and that the Time Source is coming from the GPS. Also check that it is showing the appropriate number of radio devices for how many antennas you have plugged in. Check also that the date and time are correct (it will show UTC time).

<figure><img src="../../.gitbook/assets/image (75).png" alt=""><figcaption></figcaption></figure>

2. On the RADIOS tab, check that Lotek and CTT radio numbers match up with what’s installed and that there are no invalid ports. Under “Port Mapping”, check that the antennas are plugged into the ports you are expecting. If needed, determine which antenna is plugged into which port by unplugging/plugging one radio at a time and observing which Port number disappears/reappears in real time.

<figure><img src="../../.gitbook/assets/Port Mapping.png" alt=""><figcaption></figcaption></figure>

3. To check the internet connection (so that the station can transfer data automatically back to the Motus database), click on the NETWORK tab. In the top left corner, you’ll see a box for _Network Connectivity_. If it’s working, you should see a green OK under _Motus.org_ and _Internet_.

<figure><img src="../../.gitbook/assets/Network connectivity.png" alt=""><figcaption></figcaption></figure>

4. If the internet connection is not working as expected, check that the WiFi ssid (username) and passphrase (password) is correct under the WiFi Client. You can edit this configuration by clicking the pencil icon and clicking the green check mark when complete.
5. After you have connected to the station and downloaded data, if the internet connection is not working, you can try rebooting the station. There are several methods to do so:

A) Sometimes, the power cord has a button that you can press to turn off, wait 30 seconds or so, then press to turn on again. It should look similar to this:

<figure><img src="../../.gitbook/assets/image (77).png" alt=""><figcaption></figcaption></figure>

B) If you do not have a button, the next best method to reboot your SensorGnome through the web interface. On the SOFTWARE tab, click “Enable buttons”, and click REBOOT. The SensorGnome will temporarily disconnect from your device, and you will need to log back in to the hotspot after it turns back on.

<figure><img src="../../.gitbook/assets/image (78).png" alt=""><figcaption></figcaption></figure>

C) A final option is to unplug the power cord from the Raspberry Pi. We recommend avoiding this method, when possible, as frequent plugging/unplugging can damage the port.



6. Once the station is back on, reconnect to the web interface and check if it is now connecting to internet under the NETWORK tab. It’s also good to confirm it has a GPS fix and is showing the radio devices as described in the steps above.

{% hint style="info" %}
More details on this process can be found at:&#x20;

[https://docs.motus.org/sensorgnome/setup-and-operation/whattobring](https://docs.motus.org/sensorgnome/setup-and-operation/whattobring) and [https://docs.motus.org/sensorgnome/setup-and-operation/downloading-data](https://docs.motus.org/sensorgnome/setup-and-operation/downloading-data).
{% endhint %}

## Downloading data from a SensorGnome (Version 2) using FileZilla

### Equipment

Laptop (with FileZilla)

{% hint style="info" %}
**Note:** You will need to have the free program FileZilla installed on your laptop. Download here: [https://filezilla-project.org/download.php](https://filezilla-project.org/download.php).
{% endhint %}

### Connecting to Sensorgnome using a HotSpot

1. Stand next to the Motus station with your laptop. On your laptop, look for available WiFi networks (the SensorGnome creates a hotspot).
2. You should see an available network where the name is the SensorGnome’s serial number. Click on that network and enter the password. It’s often the same as the network, which is the SensorGnome’s serial number, or it was changed during set up by you or your collaborators.

<figure><img src="../../.gitbook/assets/image (79).png" alt=""><figcaption></figcaption></figure>

### Downloading data via FileZilla

1. On your laptop, create a new folder in your Documents or on your Desktop and name it with the Motus station name and the date you are downloading data. This is where you will save the downloaded data.

<figure><img src="../../.gitbook/assets/image (80).png" alt=""><figcaption></figcaption></figure>

2. Open the FileZilla program. In the left panel named “Local site:”, navigate to the folder you created on your laptop’s Desktop where you will save the downloaded data. Click on the folder so it appears in the bottom left panel.

<figure><img src="../../.gitbook/assets/Filezilla screenshot.png" alt=""><figcaption></figcaption></figure>

3. In the top left bar, enter the following:

* Host: **sftp://sgpi.local**
* Username: **gnome**
* Password: **same password to connect to hotspot**

4. Click “Quickconnect”. There will be a pop-up window that says “server’s host key is unknown”. Click “**OK**” and continue.

<figure><img src="../../.gitbook/assets/image (82).png" alt=""><figcaption></figcaption></figure>

5. In the right panel named “Remote site:”, you will see the file directory for the SensorGnome. Click the “/” at the top. Expand the file directory and click on following folders: “dev”, then “sdcard”, then “SGdata”. A list of files with folders for each date will appear in the bottom right pane. Select all the folders for the dates you want to download. (Click the earliest date, then scroll down to the current date, hold Shift and click the current date to select all folders from first to last date.)
6. Right click on the selected folders and click “Add to queue”. At the bottom left of the page, you will see a tab named “Queued files” with the number of files.

<figure><img src="../../.gitbook/assets/Filezilla screenshot (1).png" alt=""><figcaption></figcaption></figure>

7. At the top left, click the “Transfer” menu button, then click “Process queue”. The files will begin copying to the folder you created on your laptop’s Desktop. You should see a progress bar and the number of “Queued files” decreasing and the number of “Successful transfers” increasing.
8. Wait until the queued files finish transferring. Check the folder on your Desktop – you should see a folder for each date there (all the transferred data). If the files are there, return to FileZilla and click the button with a little white computer and a red X (at the top under “Bookmarks”) to disconnect the SensorGnome.

<figure><img src="../../.gitbook/assets/Filezilla screenshot (2).png" alt=""><figcaption></figcaption></figure>

## Downloading data from a SensorGnome (Version 1) using FileZilla

### Equipment

{% columns %}
{% column %}
Ethernet cable

<figure><img src="../../.gitbook/assets/image (84).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column %}
USB to ethernet adapter &#x20;

<figure><img src="../../.gitbook/assets/image (85).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column %}
Laptop (with FileZilla)

<figure><img src="../../.gitbook/assets/image (83).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}
{% endcolumns %}

{% include "../../.gitbook/includes/note-you-will-need-to-have....md" %}

### Checking the SensorGnome web interface

{% hint style="warning" icon="bell-exclamation" %}
**Reminder:** Please take screenshots of all details on the SensorGnome interface so that station operation can be verified and troubleshot at a later date.
{% endhint %}

1. Ensure the SensorGnome is on – you should see a small red LED light.

<figure><img src="../../.gitbook/assets/image (86).png" alt=""><figcaption></figcaption></figure>

2. Plug the Ethernet cable into the Ethernet port on the Raspberry Pi and connect the other end of the Ethernet cable to your laptop. You may need to use a USB-Ethernet adapter to connect to your laptop – even for laptops that have an Ethernet port, plugging into a USB port with an adapter seems to work better.

<figure><img src="../../.gitbook/assets/image (87).png" alt=""><figcaption></figcaption></figure>

3. Wait 30-60 seconds, then open a web browser (Chrome or Firefox).
4. Visit the URL: http://sgpi.local
5. The SensorGnome web interface will now be displayed on your web browser. If it doesn’t load right away, wait a minute then try refreshing your browser. If that still doesn’t work, try restarting your laptop.

<figure><img src="../../.gitbook/assets/image (88).png" alt=""><figcaption></figcaption></figure>

6. On the SensorGnome web interface, check that the date, time, and GPS location are populated and look correct (the time stamp will be in UTC). You can also check that the 166 MHz antennas are active. The funcube dongle is the piece wrapped in shiny silver tape. The USB ports these are plugged into on the Raspberry Pi should correspond to the USB ports listed in the “What I’m doing now” and “Devices” sections on the web interface (e.g., USB port 1 in the screenshot below).

<figure><img src="../../.gitbook/assets/image (89).png" alt=""><figcaption></figcaption></figure>

### Downloading data via FileZilla

1. On your laptop, create a new folder in your Documents or on your Desktop and name it with the Motus station name and the date you are downloading data. This is where you will save the downloaded data.

<figure><img src="../../.gitbook/assets/image (90).png" alt=""><figcaption></figcaption></figure>

2. Open the FileZilla program. In the left panel named “Local site:”, navigate to the folder you created on your laptop’s Desktop where you will save the downloaded data. Click on the folder so it appears in the bottom left panel.

<figure><img src="../../.gitbook/assets/image (91).png" alt=""><figcaption></figcaption></figure>

3. In the top left bar, enter the following:

* Host: **sftp://sgpi.local**
* Username: **root**
* Password: **root**

4. Click “Quickconnect”. There will be a pop-up window that says “server’s host key is unknown”. Click “OK” and continue.

<figure><img src="../../.gitbook/assets/image (92).png" alt=""><figcaption></figcaption></figure>

5. In the right panel named “Remote site:”, you will see the file directory for the SensorGnome. Click the “/” at the top. Expand the file directory and click on following folders: “dev”, then “sdcard”, then “SGdata”. A list of files with folders for each date will appear in the bottom right pane. Select all the folders for the dates you want to download. (Click the earliest date, then scroll down to the current date, hold Shift and click the current date to select all folders from first to last date.)
6. Right click on the selected folders and click “Add to queue”. At the bottom left of the page, you will see a tab named “Queued files” with the number of files.

<figure><img src="../../.gitbook/assets/image (93).png" alt=""><figcaption></figcaption></figure>

7. At the top left, click the “Transfer” menu button, then click “Process queue”. The files will begin copying to the folder you created on your laptop’s Desktop. You should see a progress bar and the number of “Queued files” decreasing and the number of “Successful transfers” increasing.
8. Wait until the queued files finish transferring. Check the folder on your Desktop – you should see a folder for each date there (all the transferred data). If the files are there, return to FileZilla and click the button with a little white computer and a red X (at the top under “Bookmarks”) to disconnect the SensorGnome.

<figure><img src="../../.gitbook/assets/image (94).png" alt=""><figcaption></figcaption></figure>

9. You can now unplug your laptop from the Raspberry Pi. Leave the Raspberry Pi on and close the SensorGnome case.

## Downloading data from SensorGnome by copying data from the microSD card

It is possible to copy detection data files directly from the Raspberry Pi’s microSD card. This can be performed the same way on Version 1 and 2 SensorGnomes. Usually this is not the preferred method since it introduces more potential for problems, but works fine if you follow these instructions. It can be used if the SensorGnome does not have power and you can’t connect to the web interface.

### Equipment

You will need a laptop and a microSD card adaptor (if your laptop does not have a microSD card port).

### Downloading data via microSD card

1. Completely power down the SensorGnome by disconnecting the cable that plugs it into the power source. Pull out the microUSB or USB-C end that plugs into the Raspberry Pi.

<figure><img src="../../.gitbook/assets/RPI port.png" alt=""><figcaption></figcaption></figure>

2. Remove the microSD card from the Raspberry Pi. You can typically just pull it out with your thumb or finger. If the Raspberry Pi is in a case, you may need tweezers to pull out the SD card. It is near the bottom of the Raspberry Pi on the side around the corner from the microUSB power port.

<figure><img src="../../.gitbook/assets/image (95).png" alt=""><figcaption></figcaption></figure>

3. Insert the microSD card into your computer. If your computer doesn’t have a microSD card slot, you will need an adapter.
4. Open the file explorer on your computer and select the SD card (it should show up in the file explorer as **DATA** (Version 2 SensorGnomes) or **SG** (Version 1 SensorGnomes), then open the **SGdata** folder and copy the folders for all the dates you want over to your computer. There is no need to delete the files on the card.

<figure><img src="../../.gitbook/assets/image (96).png" alt=""><figcaption></figcaption></figure>

5. Put the microSD card back in the SensorGnome’s Raspberry Pi. Plug the power cable back in to the SensorGnome and make sure it is connected to the power source. If it has enough power to turn on, check the web interface to make sure it’s working properly.
