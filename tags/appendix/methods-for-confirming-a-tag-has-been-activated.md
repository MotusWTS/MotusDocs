# Methods for confirming a tag has been activated

## Lotek tags

Lotek tag activators use infrared to turn on battery powered tags, however they do have a method for confirming tags have been successfully activated. Confirming a tag is active is a critical step because activating tags can be challenging.

All it takes is to have a radio device that is tuned to the correct frequency that you can use to see or hear tag transmissions. The following methods can be used:

### Methods

1. [Lotek receiver](methods-for-confirming-a-tag-has-been-activated.md#lotek-receiver)
2. [Radio dongle and Laptop](methods-for-confirming-a-tag-has-been-activated.md#radio-dongle-and-laptop)
3. [SensorGnome or SensorStation receiver and FUNcube dongle](methods-for-confirming-a-tag-has-been-activated.md#sensorgnome-or-sensorstation-receiver-and-funcube-dongle)
4. [Use a standalone radio (Bearcat BC 125AT)](methods-for-confirming-a-tag-has-been-activated.md#use-a-standalone-receiver-bearcat-bc-125at)

The first method is by far the simplest method and is what Lotek and Birds Canada recommends. However, receivers are not always available to collaborators.\
The second method works with many models of radio dongles, but you need software installed that may not be available if you're in a pinch.\
The third method is a bit more challenging, but also works well.

### Lotek receiver

We will not go into details on how to use a Lotek receiver here since there exist guides on Lotek's website for how to use their receiver.\
However, here are some helpful tips:<br>

* Use a whip antenna with the receiver to slightly extend its range.
* Place the activator on top or right next to the receiver while you are trying to activate the tag.
* Increase the gain of the receiver to just below the threshold of where it becomes overwhelmed by noise.
* If you hear the receiver "chirp", check the tag ID on the receiver to confirm that it matches the tag you are trying to turn on.

{% embed url="https://www.youtube.com/watch?v=s1QOKtZiz4E" %}

### Radio dongle and laptop

You can still pick up your tags using just a radio dongle and a laptop with the right software installed. It also works with most radio dongles, including the FUNcube dongle and others. This method has been tested with the following radio dongles:<br>

* FUNcube dongle Pro Plus
* RTL-SDR
* AirSpy Mini
* AirSpy HF+ Discovery

{% embed url="https://www.youtube.com/watch?v=wah9R4SepP4" %}

#### Steps

1. [Install SDR++ (works on Linux, MacOS, and Windows)](https://www.sdrpp.org/)
2. If you are using the FUNcube dongle, you will also need to download the FUNcube dongle frequency control program from their website: [https://www.funcubedongle.com/?page\_id=1225](https://www.funcubedongle.com/?page_id=1225)
3. Plug in your radio dongle of choice and start up SDR++
4. On the left hand pane, under "Source", use the first dropdown to select your dongle of choice.
5. If you are using the FUNcube dongle, select "Audio". You will then need to run the FUNcube dongle frequency control program (FCHID) downloaded in step 1 and use it to enter the correct frequency you want to listen to (in KHz) and click "set frequency".
6. Use the second dropdown below it to select the correct device.
7. If no device appears, click "Refresh".
8. If you are using the FUNcube dongle, select "Line (FUNcube Dongle V2.034)"
9. Use the third dropdown to select the sample frequency.
10. The FUNcube dongle will need to be set to 48 KHz. Other dongles it doesn't matter as much.
11. Next to the volume controls at the top of the window, set the frequency to the tag frequency, minus 4 KHz. For example, if you want to listen to 166.380 MHz, set it to 166.376 MHz.
12. This is to avoid the DC spike which occurs at the tuned frequency which can obscure the tag signals.
13. Now you can click on the "play" button at the top left of the window to start listening to the radio.
14. Use the controls on the right-hand size of the window to set the zoom level and min/max gain settings to make it easier to make it easier to see or hear the signal from the tag.
15. Zoom in until the high frequency visible is about 2 KHz above the actual tag frequency.
16. Set the maximum signal to the lowest value.
17. Increase the minimum signal until you start seeing noise appear in the background.

### SensorGnome or SensorStation receiver and FUNcube dongle

This method can work well, but you won't be able to confirm the tag ID of the tag. For this reason, you need to be more careful about your setup.<br>

* Ensure no antennas are plugged into the FUNcube dongle
* Keep all other tags several metres away from the tag you are trying to active and/or place other tags in a metal box to help eliminate signals if any of them are activated.

{% hint style="info" %}
This method is made a lot easier if you are first able to upload a copy of your tag database to the receiver. See instructions here:

SensorGnome: [https://docs.motus.org/sensorgnome/maintenance/localtagdb](https://docs.motus.org/sensorgnome/maintenance/localtagdb)

CTT SensorStation: [https://docs.motus.org/sensorgnome/v1/appendix/localtagdb](https://docs.motus.org/sensorgnome/v1/appendix/localtagdb)
{% endhint %}

#### Steps

1. Power on the receiver and plug in your FUNcube dongle
2. Connect to the receiver using either your phone or laptop and navigate to the receiver's web interface.
3. On the SensorStation, click on the "SensorGnome interface" button to view the live pulse feed.
4. On the SensorGnome, go to the "radios" tab to view the live pulse feed.
5. Before you try activating your tag, watch the pulse feed to see if it's picking up any tags or if there's too much environmental noise. If this is the case, _this method will not work since you will not be able to easily distinguish your tag from the other pulses._
6. You can try isolating the receiver in a way that decreases environmental noise by surrounding it be tinfoil or placing some other kind of metal shielding around it.
7. Try activating your tag
8. If you are succesful, you should see a series of 4 pulses in close succession appearing in the pulse window. If you uploaded your tag database to the receiver, you should also see the tag ID appear in the "Lotek tags" window.

### Use a standalone receiver (Bearcat BC 125AT)

{% embed url="https://www.youtube.com/watch?v=fc6w3i1_s8o" %}

