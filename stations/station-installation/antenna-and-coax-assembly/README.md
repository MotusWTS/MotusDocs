# Antenna and Coax Assembly

Several varieties of antennas exist of which only a few will be covered here. All antennas should come with their own assembly instructions which are more or less easy to follow so we will not go into great detail here. Please see [antenna anatomy](../../station-equipment/antennas.md#antenna-anatomy) for more details on parts.

{% hint style="warning" %}
The driven element and the attached connector are the most sensitive parts of a Yagi antenna; pay special attention to prevent damage to these parts and any connections. Damage to the driven element may cause the antenna to no longer be tuned to the desired frequency resulting in an ineffective antenna.
{% endhint %}

### Recommended accessories

* **Coax seal.** This is a type of soft rubber or silicone which is used to seal antenna connections. This is typically purchased separately from the antenna. Marine Goop (with UV protectant (link), and electrician, or plumbers puddy (with link).
* **Coloured electrical tape or markers.** It can be difficult to keep track of which antenna corresponds with which cable once a station has been set up. Bring a few colours of electrical tape so you can colour code the antennas and coaxial cables.
* **Zip ties, cable ties, zap straps.** These are indispensable for coaxial cable organisation. Used to support the coax cable along the antenna boom and mast.
* **Hex nuts and bolts.** We use ¼” x 2” bolts for tripod assembly and ¼” x 1” bolts for affixing solar panels to the tripod\*\*.\*\* Use zinc-plates steel unless the station is deployed in a marine area where stainless steel should be used.

{% content-ref url="../../station-equipment/parts-list-and-suppliers.md" %}
[parts-list-and-suppliers.md](../../station-equipment/parts-list-and-suppliers.md)
{% endcontent-ref %}

### Antenna mount

Antennas are usually attached to a metal pipe or mast using a type of mounting bracket. Small antennas, like 434 MHz Yagis, all omni antennas, and 3- to 5- element Yagis for the 150-166 MHz band can be butt-mounted using a bracket which fits onto one end of the boom. Large antennas, like 6- to 9-element Yagis for the 150-166 MHz band need to be mounted along their mid-point to even out the lateral force on the mast. Larger antenna can be butt-mounted, but usually require support wires attached to the mid or end point of the antenna.

Nearly all antenna mounts use a metal plate with 4 u-bolts; 2 for the antenna boom and 2 for the mast. For most antennas, the boom is mounted perpendicular to the mast, but omni antennas will often be mounted pointing straight up, meaning both the antenna and mast will be in the same orientation.

### Coax connector

Most antennas will have a connector on the driven element for the coax cable to be connected. The driven element and this connector are the most sensitive parts of a Yagi antenna; pay special attention to these parts so they are not impacted by anything. Damage to the driven element may cause the antenna to no longer be tuned to the desired frequency.

### Antenna orientation

The orientation of an antenna changes the horizontal range relative to the vertical range. For instance, an omni antenna can be oriented straight upwards to have a uniform detectability along the horizontal and vertical axes, or it could be pointed horizontally to create a more restricted, lateral detection area. Similarly, Yagi antennas can be rotated along the boom to select a wider horizontal or vertical beamwidth.&#x20;

{% hint style="warning" %}
Most stations across Motus will orient their Yagi antennas horizontally (antenna elements pointing horizontal). We recommend all collaborators do this to maintain consistency across the network.
{% endhint %}

## Antenna spacing

Most Motus stations will host multiple antennas, but this may pose an issue depending on the types and position of the antennas.

Simple modeling by Bob Morton at Maple Leaf Communications suggests there is a significant dropoff in the detection range of Yagi antennas when they are stacked too close together.

We have developed the following guidelines based on these models:

* Antennas that facing opposite directions should be the furthest apart from one-another: at least 1/2 a wavelength (\~1 meter for 166.38 MHz).
* Antennas that are facing perpendicular directions should be at least a 1/4 wavelength apart (\~1/2 meter).

| **Antenna Type** | **Tags** | **Frequency** | **Wavelength** |
| ---------------- | -------- | ------------- | -------------- |
| 9-element Yagi   | Lotek    | 166.380 MHz   | 1.80 meters    |
| 9-element Yagi   | Lotek    | 151.500 MHz   | 1.98 meters    |
| 9-element Yagi   | Lotek    | 150.100 MHz   | 2.00 meters    |
| 9-element Yagi   | CTT      | 434 MHz       | 0.69 meters    |

{% hint style="success" %}
Antennas should be butt-mounted when possible. This is usually only practical for 434 MHz Yagi antennas due to the size of lower frequency antennas.
{% endhint %}
