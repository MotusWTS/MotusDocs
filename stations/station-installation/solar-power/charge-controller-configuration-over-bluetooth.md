---
description: >-
  This document outlines configuration steps for installing the Victron Energy
  BlueSolar MPPT 75/15 and the Victron Energy SmartSolar MPPT 75/15 charge
  controllers.
---

# Charge Controller Configuration Over Bluetooth

<div><figure><img src="../../../.gitbook/assets/image (3) (3).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../../.gitbook/assets/image (2) (2).png" alt=""><figcaption></figcaption></figure></div>

## About

The charge controller comes preconfigured with a load output mode that isn't optimal for Motus stations and should be changed. In addition, the default charging profile is designed for AGM Lead Acid batteries so it should be switched to Lithium Iron Phosphate if you are using that chemistry.

## Prerequisites

* [VictronConnect App](https://www.victronenergy.com/victronconnectapp/victronconnect/downloads)
* [VE.Direct Bluetooth Smart Dongle](https://a.co/d/08uN3tWr) (if working with Victron Energy BlueSolar MPPT 75/15)

## Instructions

### Connecting for the first time

{% columns %}
{% column %}
1. The charge controller needs to be connected to a battery in order to connect to it.
2. Remove the jumper and discard it (circled in red).
{% endcolumn %}

{% column %}
<figure><img src="../../../.gitbook/assets/image (115).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}
{% endcolumns %}



{% columns %}
{% column %}
#### Victron Energy BlueSolar MPPT 75/15

1. Plug the VE.Direct Bluetooth Smart Dongle into the charge controller.
2. Open up the VictronConnect App and attempt to connect to the smart dongle.
3. It might ask to update the firmware if this is the first time connecting - let it do the update.
{% endcolumn %}

{% column %}
#### Victron Energy SmartSolar MPPT 75/15

1. Open up the VictronConnect App and attempt to connect to the charge controller.
2. It might ask to update the firmware if this is the first time connecting - let it do the update.
{% endcolumn %}
{% endcolumns %}

### Setting the Load Output Mode

1. Go to the settings (gear icon, top-right).

<figure><img src="../../../.gitbook/assets/Screenshot_20261007_085308.jpg" alt="" width="375"><figcaption></figcaption></figure>

1. Select "Load output".

<figure><img src="../../../.gitbook/assets/Screenshot_20261007_085354 (1).jpg" alt="" width="375"><figcaption></figcaption></figure>

3. Change "Operation mode" to "Conv. algorithm 1".

<div><figure><img src="../../../.gitbook/assets/Screenshot_20261007_090243 (1).jpg" alt=""><figcaption></figcaption></figure> <figure><img src="../../../.gitbook/assets/Screenshot_20261007_085518.jpg" alt=""><figcaption></figcaption></figure></div>

### Setting Battery Type to Lithium

1. Go to the settings (gear icon, top-right).

<figure><img src="../../../.gitbook/assets/Screenshot_20261007_085308 (2).jpg" alt="" width="375"><figcaption></figcaption></figure>

2. Select "Battery".

<figure><img src="../../../.gitbook/assets/Screenshot_20261007_085354 (1).jpg" alt="" width="375"><figcaption></figcaption></figure>

3. Press the dropdown arrow next to "Battery preset" then "Select preset".

<div><figure><img src="../../../.gitbook/assets/Screenshot_20261007_085553.jpg" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../../../.gitbook/assets/Screenshot_20261007_085606.jpg" alt="" width="375"><figcaption></figcaption></figure></div>

4. Select "Smart Lithium"

<figure><img src="../../../.gitbook/assets/Screenshot_20261007_085615.jpg" alt="" width="375"><figcaption></figcaption></figure>

### Turning off "Streetlight Mode"

1. Go to the settings (gear icon, top-right).

<figure><img src="../../../.gitbook/assets/Screenshot_20261007_085308 (2).jpg" alt="" width="375"><figcaption></figcaption></figure>

2. Select "Streetlight".&#x20;

<figure><img src="../../../.gitbook/assets/Screenshot_20261007_085354 (2).jpg" alt="" width="375"><figcaption></figcaption></figure>

3. Make sure the toggle is in the off position.&#x20;

<figure><img src="../../../.gitbook/assets/Screenshot_20261015_103726 (1).jpg" alt="" width="375"><figcaption></figcaption></figure>

## References

* Victron Energy [MPPT solar charger manual for BlueSolar MPPT 75/10 up to 100/20](https://www.victronenergy.com/upload/documents/Manual_BlueSolar_MPPT_75-10_up_to_100-20/29694-MPPT_solar_charger_manual-pdf-en.pdf)
* Victron Energy [MPPT solar charger manual for SmartSolar MPPT 75/10 up to 100/20](https://www.victronenergy.com/upload/documents/Manual_SmartSolar_MPPT_75-10_up_to_100-20/29694-MPPT_solar_charger_manual-pdf-en.pdf)

