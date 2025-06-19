# Downloading Data

## Instructions

Methods for downloading data from a Motus receiver depends on the model of receiver being used. Select a model from the links below to view instructions:

* [SensorGnome](https://docs.motus.org/sensorgnome/)
* [CTT SensorStation](https://store.celltracktech.com/pages/installation-guides)
* [Lotek SRX](lotek-srx.md)

{% hint style="info" %}
**Automated data uploads**\
\
Both SensorGnomes and CTT SensorStations can be programmed to automatically upload data to Motus with an internet or cellular connection. Review their guides for more information.
{% endhint %}

### **Uploading data to Motus**

1. Prepare the data for uploading&#x20;
   1. Add all files for a receiver to a .zip or .7z archive
   2. Ensure that each archive contains data from _only one receiver_
   3. Do _not_ change any of the detection data filenames. The name of the archive itself doesn't matter, but it's best to give it a description name for your own benefit
2. Log in to Motus.
3. Select your project from the dropdown menu.&#x20;
4. Select '[Upload Detection Files](https://motus.org/data/project/sgJobs)' from the management menu.
5. Follow the instructions on that page to upload these data.
6. After processing is complete (usually 1-6 hours, but sometimes longer) you'll receive a \
   "Processing complete"  email. Ensure that you review this email and the job log as it may contain important information about your upload.

{% hint style="info" %}
Don't worry if you accidentally upload data to the wrong project. This will not have any impact on the data, and all detections will be associated with the correct project and station on the back-end. However it will result in the job log being found in the wrong project, and there will be a statement in the "Processing complete" email that "there is no deployment found for this receiver". Otherwise, there is no impact.
{% endhint %}
