# Beacon tags

### Description

Beacon tags, sometimes called sentinel tags, are a special kind of tag used primarily for confirming a station's operation over time.&#x20;

They differ from typical tags in that all physical beacon tags share identical properties and cannot be distinguished from one another. They use dedicated manufacturer codes that are used only for beacon tags, and, in the case of Lotek, is used for each of the various frequencies worldwide.

| Manufacturer | Dedicated beacon tag code | Burst interval | Frequencies                      |
| ------------ | ------------------------- | -------------- | -------------------------------- |
| Lotek        | 732                       | 40 seconds     | 166.38 MHz, 150.1 MHz, 151.5 MHz |
| CTT          | 78554C33                  | 5 seconds      | 434 MHz                          |

### Registration and metadata management

Because all physical beacon tags are essentially identical, they are not registered or managed as typical tags are. Instead, all tags with the same properties share a single registration and deployment record in **Project 322** ([new explore pages](https://motus.org/dashboard/#e=profile\&d=projects\&s=322); [old explore pages](https://motus.org/data/projectTags?id=322)). Beyond confirming that the beacon tag you have exists in this project, there is no further metadata management required in order to use a beacon tag.

{% hint style="info" %}
Prior to settling on dedicated tag codes to use for beacon tags, there were several earlier cases where multiple physical tags were issued with identical properties. These were also registered to Project 322 and many of these remain active.
{% endhint %}

### Usage

Ideally, a beacon tag would not be placed too close to a receiver lest the tags' signal may be picked up directly by a dongle. This could lead to a situation where the antenna and cable assembly is not functioning, yet it appears to be working fine due to the signal being picked up directly by dongle. In practice, it's often impossible to place the beacon tag at the "perfect" distance from a particular station.
