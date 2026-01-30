---
description: Everything you need to know about deploying tags
---

# Tag Deployment

## Tag Management

This chapter pertains to tag deployment methods in the field. For information on the management of tag deployment metadata within the Motus system, see [**Tag Management**](tag-metadata-management/).

## Tag Deployment - Best Practices

### Before you deploy your tags, consider the following:

* Ensure local stations and any other stations you may rely on are active and _working_. Never assume that stations are working. Communicate with collaborators that manage stations from which you may expect detections. You may need to regularly check on stations yourself to confirm stations are functional.
* Tag deployments are most effective when made in close proximity to an active station. Detections on a local station allow you to confirm your tags are working.&#x20;
* Be sure that tags are activated prior to their deployment using a receiver or an active Motus station.
* Create a deployment with an anticipated start date prior to deployment. See [Anticipated deployment date](tag-metadata-management/tag-metadata.md#anticipated-deployment-date).&#x20;
* Plan to record the required metadata during deployment and update it as soon as you can following deployment. See [Tag Metadata](tag-metadata-management/tag-metadata.md).
* Always keep animal welfare at top of mind whenever you deploy tags. See note below:

{% hint style="warning" %}
#### **Animal welfare should be the number one priority when tagging any species**

1. **Tag weight must include the weight of all harness materials**. For lightweight species, this is especially important. Adding loops to tags for adjustable or backpack harnesses adds about 0.25-0.30 g, for instance. Due to manufacturing variance, estimating tag + harness weight is not enough on its own and fitted tags should also be individually weighed in the field before deployment.
2. **Tags should not exceed the 3% weight rule for** most bird species and 5% for bats as a general rule. However, we strongly recommend you estimate the lean (or fasting) weight of the individual for this rule. It should be possible to determine this weight using literature, or by examining your own historical banding data of this species, using wing length as a rough comparison metric.
3. **You should consider the how fat loading may impact the size of the bird** when fitting a tag to a bird using any of the 3 harnessing methods listed below. In other words, you should consider putting tags on as loosely as possible for individuals that are expected to gain a lot of fat _after_ tagging occurs.
{% endhint %}

## Tag activation

{% hint style="warning" %}
### Confirm your tag is active before deploying it!

Regardless of the tag type, you **always** want to confirm each tag is active by looking for detections of your tag on a nearby receiver before you deploy it. See [How to tell when a tag is active](tag-deployment.md#how-to-tell-when-a-tag-is-active) for more details.
{% endhint %}

### Lotek tags

#### NanoTags

Lotek tags are activated using an infrared activator which must be purchased separately from Lotek. Lotek provides instructions on how to activate tags on their support pages.&#x20;

#### Beacon tags

Lotek Beacon tags come shipped with a magnet which, once removed, causes the tag to start transmitting immediately. It can be reapplied to turn the tag off.&#x20;

### CTT tags

CTT tags activate differently depending on the type of tag:

#### LifeTags

This tag transmits continuously as long as it has sufficient sunlight.

#### HybridTags

Remote the magnet from the tag. It may require charging in sunlight for a few hours to several days before it begins transmitting a signal.

#### PowerTags

Remove the magnet from the tag. It should begin transmitting a signal immediately.

### How to tell when a tag is active

Regardless of the tag type, you **always** want to confirm each tag is active by looking for detections of your tag on a nearby receiver before you deploy it. This will need to be done using different ways depending on the tag type.

#### Lotek NanoTags and Beacon Tags

There are several ways to confirm a Lotek tag is active, but the easiest method is by using a Lotek receiver. How to tell when a Lotek tag is active for more details.



#### CTT tags (434 MHz)

Use&#x20;

## How to tag animals

As is the case for any new measurement technique for wild animals, researchers should **always** have in-person training on any tagging method before deploying tags on their own. In addition, tagging animals is hard and requires extensive experience handling birds of various sizes and species before learning how to tag.

{% hint style="warning" %}
This section is still in development as we continue to create guidelines and videos on various methods for tagging animals safely and effectively.



The following documents are drafts and should be used with caution until the final documents are published. That said, we have opted to make these documents available due to the number of requests from the research community. If you plan to share the documents, we recommend sharing links to this page to minimize circulation of outdated versions once the final documents are published.
{% endhint %}

{% file src="../.gitbook/assets/Guidelines_Feb 2 2024.pdf" %}

### Figure-8 Leg Loop Harness

{% columns %}
{% column width="33.33333333333333%" %}
#### Equipment

* Super glue
* Jewelry elastic (0.7mm)
* Baking soda
{% endcolumn %}

{% column %}
#### Tools

* Crochet hook
* Ruler
* Sharpie
{% endcolumn %}
{% endcolumns %}

#### Methods

{% file src="../.gitbook/assets/LegLoop-SOP_July 17 2025.pdf" %}

<details>

<summary>Tag harness sizes</summary>

{% include "../.gitbook/includes/tag-harness-size-table.md" %}



</details>

#### Video

{% embed url="https://youtu.be/AFR3InX2CLs" %}

### Adjustable Leg Harness

{% columns %}
{% column width="33.33333333333333%" %}
#### Equipment

* Stretch Magic (Black, 0.7mm)
* Crimp tubes (1.5mm x 4mm)
{% endcolumn %}

{% column %}
#### Tools

* Scissors
* Crimp tool
* Crochet hook
{% endcolumn %}
{% endcolumns %}

#### Methods

There is currently no SOP drafted for this method, but researchers can follow instructions published in:

> [Jirinec, V., Rodrigues, P.F. and Amaral, B., 2021. Adjustable leg harness for attaching tags to small and medium‐sized birds. Journal of Field Ornithology, 92(1), pp.77-87.](https://onlinelibrary.wiley.com/doi/am-pdf/10.1111/jofo.12353)

#### Video

{% embed url="https://youtu.be/0HAi-rQjOCM" fullWidth="false" %}

### Backpack Harness

{% file src="../.gitbook/assets/BackpackStyle-SOP_Feb 2 2024.pdf" %}

### Glue on

{% file src="../.gitbook/assets/Glue-SOP_Feb 2 2024.pdf" %}

## Trimming tags

There are a number of researchers who opt to cut the antennas of tags when deploying on smaller animals. Basic antenna theory suggests it will decrease the effective power of the transmitter, but more testing is needed to determine the magnitude of this decrease when deployed on animals. Controlled tests have shown that OOK tags (166.380 MHz) will decrease in power with length, but are most effective when cut to specific lengths (harmonics of the nominal frequency). On the other hand, FSK tags (434 MHz) appear to decrease continuously with length, not showing better performance at specific lengths like OOK tags. These tag tests were not done on animals and will likely be different in real deployments.&#x20;

That being said, if you're planning on trimming one of your Lotek tags, you should aim for one of these lengths to maximize the effect power:

<table><thead><tr><th width="153">Frequency</th><th>Lengths</th></tr></thead><tbody><tr><td>166.380 MHz</td><td>18.0 cm, 15.0 cm,  12.9 cm, 11.3 cm, 10.0 cm, 9.0 cm, 8.2 cm, 7.5 cm, 6.9 cm, 6.4 cm, 6.0 cm, 5.6 cm</td></tr><tr><td>151.5 MHz</td><td>19.8 cm, 16.5 cm, 14.1 cm, 12.4 cm, 11 cm, 9.9 cm, 9 cm, 8.2 cm, 7.6 cm, 7.1 cm, 6.6 cm, 6.2 cm</td></tr><tr><td>150.1 MHz</td><td>20 cm, 16.6 cm, 14.3 cm, 12.5 cm, 11.1 cm, 10 cm, 9.1 cm, 8.3 cm, 7.7 cm, 7.1 cm, 6.7 cm, 6.2 cm</td></tr></tbody></table>

<details>

<summary>Tag harness sizes</summary>

{% include "../.gitbook/includes/tag-harness-size-table.md" %}



</details>

## **How to avoid tag aliasing**

Aliasing can occur when multiple tags emit a signal at the same time. Sometimes these interacting signals can produce a pattern which match a different tag that is not actually present. This is due to the nature of how the unique tag ID is encoded in the signal. However, the parameters used to define these IDs are quite stringent, making aliasing only an issue in specific conditions.

### Strategic tag deployment

To help mitigate aliasing, we recommend keeping numbers low at any given tagging site. This can be done by staggering deployments, either spatially or temporally. Most aliasing is caused by tags which have the same burst interval but a different Lotek ID. That means if you have more than one burst interval in your selection of tags, you can deploy more tags at any given site with a reduced risk of aliasing. However, do not deploy more than one tag with the same Lotek ID, even if they have different burst intervals!

{% content-ref url="tag-aliasing.md" %}
[tag-aliasing.md](tag-aliasing.md)
{% endcontent-ref %}
