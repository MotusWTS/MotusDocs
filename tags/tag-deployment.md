---
description: Everything you need to know about deploying tags
---

# Tag Deployment

## Tag Management

This chapter pertains to tag deployment methods in the field. For information on the management of tag deployment metadata within the Motus system, see [**Tag Management**](../project-management/tag-management/).

## Tag Deployment Best Practices

### Before you deploy your tags, consider the following:

* Ensure local stations and any other stations you may rely on are active and _working_. Never assume that stations are working. Communicate with collaborators that manage stations from which you may expect detections. You may need to regularly check on stations yourself to confirm stations are functional.
* Tag deployments are most effective when made in close proximity to an active station. Detections on a local station allow you to confirm your tags are working.&#x20;
* Be sure that tags are activated prior to their deployment using a receiver or an active Motus station.
* Create a deployment with an anticipated start date prior to deployment. See [Anticipated deployment date](../project-management/tag-management/tag-metadata.md#anticipated-deployment-date).&#x20;
* Plan to record the required metadata during deployment and update it as soon as you can following deployment. See [Tag Metadata](../project-management/tag-management/tag-metadata.md).

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

{% file src="../.gitbook/assets/LegLoop-SOP_Feb 2 2024.pdf" %}

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

## Tag Harness sizes

This table lists harness sizes for the pre-fabricated ‘figure eight’ leg loop harness method based on real sizes used on individuals tagged in the field. Sizes include the length of a single leg-loop, not include overlap with the tag. Weights can be used to help specify which harness size to use.

<figure><img src="../.gitbook/assets/tag harness size (1).png" alt=""><figcaption><p>Example tag harness measured to 28mm, not including the tag width of 4mm.</p></figcaption></figure>

Please note that these are guidelines. Regardless of what sizes you find here, the harness should always be fitted to the individual. Please see a [**How to Tag Animals**](tag-deployment.md#how-to-tag-animals) above for more information.

<table><thead><tr><th width="192">Species</th><th width="180">Harness Size (mm)</th><th width="122">Weight (g)</th><th width="120">Wing (mm)</th><th>Sample size</th></tr></thead><tbody><tr><td>Yellow-billed Cuckoo</td><td>50-61</td><td>43-80</td><td></td><td>10</td></tr><tr><td>Black-billed Cuckoo</td><td>52</td><td>34</td><td></td><td>1</td></tr><tr><td>Hammond's Flycatcher</td><td>29</td><td>9.5</td><td></td><td>1</td></tr><tr><td>Dusky Flycatcher</td><td>34</td><td></td><td></td><td>1</td></tr><tr><td>Say's Phoebe</td><td>37</td><td>23.5</td><td></td><td>1</td></tr><tr><td>White-eyed Vireo</td><td>28-34</td><td>9-12</td><td></td><td>5</td></tr><tr><td>Warbling Vireo</td><td>33-35</td><td>13-14</td><td></td><td>3</td></tr><tr><td>Red-eyed Vireo</td><td>39-42</td><td>15-20</td><td></td><td>100+</td></tr><tr><td>Bank Swallow</td><td>32-34</td><td>10-13</td><td></td><td>50+</td></tr><tr><td>Barn Swallow</td><td>34-37</td><td>17-19</td><td></td><td>80+</td></tr><tr><td>House Wren</td><td>33</td><td>11</td><td></td><td>1</td></tr><tr><td>Eurasian Reed Warbler</td><td>30</td><td>9-13</td><td></td><td>60+</td></tr><tr><td>Gray-cheeked Thrush</td><td>50-54</td><td>26-37</td><td></td><td>30+</td></tr><tr><td>Bicknell's Thrush</td><td>46-50</td><td>24-30</td><td></td><td>12</td></tr><tr><td>Swainson's Thrush</td><td>48-52</td><td>25-36</td><td></td><td>100+</td></tr><tr><td>Brown Thrasher</td><td>62</td><td>67</td><td></td><td>1</td></tr><tr><td>Golden-winged Warbler</td><td>27-30</td><td></td><td>58-65</td><td>51</td></tr><tr><td>Orange-crowned Warbler</td><td>29-32</td><td>8-10</td><td></td><td>4</td></tr><tr><td>Kentucky Warbler</td><td>34-35</td><td>12-15</td><td></td><td>2</td></tr><tr><td>Hooded Warbler</td><td>30-34</td><td>9-14</td><td></td><td>4</td></tr><tr><td>Cerulean Warbler</td><td>26-28</td><td></td><td></td><td></td></tr><tr><td>Magnolia Warbler</td><td>24-28</td><td></td><td></td><td>?</td></tr><tr><td>Blackpoll Warbler</td><td>33-36</td><td>10-22</td><td></td><td>200+</td></tr><tr><td>Black-throated Blue Warbler</td><td>26-28</td><td></td><td></td><td>?</td></tr><tr><td>Palm Warbler</td><td>26-34</td><td>9-12</td><td></td><td>5</td></tr><tr><td>Yellow-rumped Warbler (Myrtle)</td><td>31-34</td><td>10-15</td><td></td><td>100+</td></tr><tr><td>Prairie Warbler</td><td>26-29</td><td>7-10</td><td></td><td>7</td></tr><tr><td>Canada Warbler</td><td>34</td><td>10-12</td><td></td><td>?</td></tr><tr><td>Yellow-breasted Chat</td><td>40-42</td><td>22-25</td><td></td><td>4</td></tr><tr><td>Saltmarsh Sparrow</td><td>36-39</td><td>18-20</td><td></td><td>60+</td></tr><tr><td>Clay-colored Sparrow</td><td>30-31</td><td>9-12</td><td></td><td>7</td></tr><tr><td>Field Sparrow</td><td>30-32</td><td>12-13</td><td></td><td>6</td></tr><tr><td>Lark Sparrow</td><td>32-42</td><td>20-28</td><td></td><td>1</td></tr><tr><td>White-crowned Sparrow</td><td>44</td><td>31</td><td></td><td>1</td></tr><tr><td>White-throated Sparrow</td><td>45-50</td><td>23-31</td><td></td><td>100+</td></tr><tr><td>Savannah Sparrow (Ipswich)</td><td>38-44</td><td>21-30</td><td></td><td>100+</td></tr><tr><td>Eastern Towhee</td><td>50</td><td>40</td><td></td><td>1</td></tr><tr><td>Summer Tanager</td><td>39-40</td><td>26-27</td><td></td><td>2</td></tr><tr><td>Blue Grosbeak</td><td>37</td><td>26</td><td></td><td>1</td></tr><tr><td>Indigo Bunting</td><td>34-36</td><td>14-17</td><td></td><td>10</td></tr><tr><td>Painted Bunting</td><td>34</td><td></td><td></td><td>1</td></tr><tr><td>Dickcissel</td><td>38-44</td><td>22-32</td><td></td><td>3</td></tr><tr><td>Orchard Oriole</td><td>40-42</td><td>19-22</td><td></td><td>2</td></tr></tbody></table>

## **How to avoid tag aliasing**

Aliasing can occur when multiple tags emit a signal at the same time. Sometimes these interacting signals can produce a pattern which match a different tag that is not actually present. This is due to the nature of how the unique tag ID is encoded in the signal. However, the parameters used to define these IDs are quite stringent, making aliasing only an issue in specific conditions.

### _Strategic tag deployment_

To help mitigate aliasing, we recommend keeping numbers low at any given tagging site. This can be done by staggering deployments, either spatially or temporally. Most aliasing is caused by tags which have the same burst interval but a different Lotek ID. That means if you have more than one burst interval in your selection of tags, you can deploy more tags at any given site with a reduced risk of aliasing. However, do not deploy more than one tag with the same Lotek ID, even if they have different burst intervals!

[**Read more about how to avoid tag aliasing.**](tag-aliasing.md#how-to-avoid-tag-aliasing-1)
