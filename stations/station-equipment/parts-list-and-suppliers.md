# Parts list and suppliers

## Receivers

Not all receivers are compatible with all tag types! [Read more about receivers here.](receivers.md)

| Model             | Retailer       | Link                                                                                                                                                                                                                               |
| ----------------- | -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CTT SensorStation | CTT            | [https://celltracktech.com/collections/digital-radio-products/products/sensorstation-for-sensorgnome-version-3-0](https://celltracktech.com/collections/digital-radio-products/products/sensorstation-for-sensorgnome-version-3-0) |
| SensorGnome       | Compudata      | [https://compudata.ca/sensorgnome/](https://compudata.ca/sensorgnome/)                                                                                                                                                             |
| SensorGnome       | RFS Scientific | [https://www.rfsscientific.com/store](https://www.rfsscientific.com/store)                                                                                                                                                         |
| Lotek SRX-1200    | Lotek          | [https://www.lotek.com/products/srx1200/](https://www.lotek.com/products/srx1200/)                                                                                                                                                 |

## Antennas and cables

### 166.380 MHz antennas

For Lotek Nanotags in the Western Hemisphere.

<table><thead><tr><th width="279.3333333333333">Retailer</th><th width="168">Antenna Type</th><th width="150">Antenna Model</th><th width="150">Locale</th></tr></thead><tbody><tr><td>ZDA Antennas</td><td>6, 9, 11 element</td><td>ZDADJ166-6YG, ZDADJ166-9YG, ZDADJ166-11YG</td><td>USA</td></tr><tr><td>Samco</td><td>6-Element</td><td>SAM-160</td><td>USA</td></tr><tr><td>Laird Antenna</td><td>9-Element</td><td>PLC-1669</td><td>USA</td></tr><tr><td>Laird Antenna</td><td>6-Element</td><td>PLC-1666</td><td>USA</td></tr></tbody></table>

### 434 MHz antennas

For CTT LifeTags, PowerTags, and HybridTags globally.

<table><thead><tr><th width="166.33333333333331">Retailer</th><th width="254.9022556390978">Antenna Type</th><th width="161">Antenna Model</th><th>Locale</th></tr></thead><tbody><tr><td>Data Alliance</td><td>Omnidirectional</td><td>A433O5</td><td>USA</td></tr><tr><td>Samco</td><td>3-Element Circular-polarized</td><td>SAM-450RHCP</td><td>USA</td></tr><tr><td>Laird Antenna</td><td>6-Element</td><td>YS4306</td><td>USA</td></tr><tr><td>Laird Antenna</td><td>3-Element</td><td>YS4303</td><td>USA</td></tr><tr><td>ZDA Communications</td><td>Omnidirectional</td><td>ZDAQJ430-5</td><td>USA</td></tr><tr><td>ZDA Communications</td><td>4-Element</td><td>ZDADJ433-8YG</td><td>USA</td></tr><tr><td>ZDA Communications</td><td>6-Element</td><td>ZDADJ433-10YG</td><td>USA</td></tr><tr><td>ZDA Communications</td><td>8-Element</td><td>ZDADJ433-12YG</td><td>USA</td></tr><tr><td>Telewave</td><td>Omnidirectional</td><td>ANT450F-2</td><td>Mexico</td></tr></tbody></table>

### Coaxial Cables

Most RF or antenna suppliers will sell coaxial cable cut to size and with with your choice of connection type. We recommend **LMR400** cable, which is durable and low-loss. However, due to its stiffness, we also recommend a 30 cm (12-inch) jumper cable made of a lighter grade material (e.g.; LMR-240) as strain relief for connecting between the LMR-400 cable and the FUNcube dongle. Alternatively, you may use **bulkheads** for strain relief.



| **Cable type**                                                                                                                                                                                                                                                   | **Typical price (USD)** | **Impedance** | <p><strong>Max attenuation</strong></p><p><strong>(dB/100 ft)</strong></p> | **Suggested length** |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- | ------------- | -------------------------------------------------------------------------- | -------------------- |
| [**RG-58**](https://www.pasternack.com/flexible-0.195-rg58-50-ohm-coax-cable-pvc-jacket-rg58c-u-p.aspx)                                                                                                                                                          | < 100 ft. @ $0.83/ft.   | 53.5 Ohms     | <p>4.4 @ 100 MHz</p><p>6.0 @ 200 MHz</p><p>8.5 @ 400 MHz</p>               | < 50 ft./15 m        |
| [<mark style="color:green;">**RG-213**</mark>](https://www.pasternack.com/flexible-0.405-rg213-50-ohm-coax-cable-pvc-jacket-rg213-u-p.aspx)                                                                                                                      | < 100 ft. @ $1.79/ft.   | 50 Ohms       | <p>2.3 @ 100 MHz</p><p>4.8 @ 400 MHz</p>                                   | < 100 ft./30 m       |
| <p><mark style="background-color:green;">TWS/BMR/</mark></p><p><a href="https://www.pasternack.com/50-ohm-low-loss-flexible-lmr400-pe-jacket-double-shielded-black-lmr-400-P.aspx"><mark style="background-color:green;"><strong>LMR-400</strong></mark></a></p> | $1.20/ft.               | 50 Ohm        | <p>1.5 @ 150 MHz</p><p>2.7 @ 450 MHz</p>                                   | Any length           |

### Bulkheads

Bulkheads are connectors used to attach **coaxial cables** to the **receiver**. They attach directly to the 'radios' or 'dongles' which are part of the receiver (e.g.; CTT internal radios or FUNcube dongle). These parts can be readily found online at various retailers, just make sure you search for **SMA male to Type N female** bulkhead. We recommend waterproof bulkheads for mounting on cases - these come with o-rings which can maintain the original IP rating of the case. The product below is a somewhat expensive example of what we normally purchase, yet we are usually able to find the for under $10 USD apiece at other retailers.

<table><thead><tr><th>Connector 1</th><th>Connector 2</th><th width="168">Digikey</th><th>Link</th></tr></thead><tbody><tr><td>Type N Female</td><td>SMA Male</td><td>Digikey</td><td><a href="https://www.digikey.ca/en/products/detail/amphenol-rf/095-902-530-006/12751750">https://www.digikey.ca/en/products/detail/amphenol-rf/095-902-530-006/12751750</a></td></tr></tbody></table>



{% hint style="info" %}
CTT SensorStations can be ordered with bulkheads installed.&#x20;
{% endhint %}

{% hint style="warning" %}
Careful not to accidentally order any parts that have 'RP' in the name. This stands for 'reverse polarity' and means the gender of the connector is opposite from normal so it will not connect to your cables or receiver.
{% endhint %}

### Bandpass Filters

| Frequency Range | Retailer       | Link                                                                                                                                                  |
| --------------- | -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| 137-174         | Scanner Master | [https://www.scannermaster.com/BPF\_VHF\_Band\_Pass\_Filter\_p/24-531041.htm](https://www.scannermaster.com/BPF_VHF_Band_Pass_Filter_p/24-531041.htm) |



## Power Supply

| Category | Type   | Part               | Link                                                                                                   |
| -------- | ------ | ------------------ | ------------------------------------------------------------------------------------------------------ |
| Solar    | Wiring | Fused battery lead | [Amazon](https://www.amazon.ca/gp/product/B07CK784LZ/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8\&psc=1) |

## Antenna mounting structure

| Category                   | Type                       | Part                               | Link                                                                                                                                                  |
| -------------------------- | -------------------------- | ---------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| Pop-tower                  | Tripod                     | TRM-10L                            | [Wade Antenna](http://wadeantenna.com/product/10-foot-tripod/)                                                                                        |
| -                          | Spare ¼” bolts             | ¼” x 2” hex bolt                   | [Most hardware stores](https://www.homedepot.com/p/Prime-Line-1-4-in-20-x-2-in-Grade-304-Stainless-Steel-Hex-Bolts-50-Pack-9058462/310465140)         |
| -                          | Spare ¼” nuts              | ¼” lock nut                        | [Most hardware stores](https://www.homedepot.com/p/Prime-Line-1-4-in-20-Grade-18-8-Stainless-Steel-Nylon-Insert-Lock-Nut-20-Pack-9075237/307410008)   |
| -                          | Spare 5/16” bolts          | 5/16” x 1” hex bolt                | [Most hardware stores](https://www.homedepot.com/p/Everbilt-5-16-in-18-x-1-in-Zinc-Plated-Hex-Bolt-50-Pack-800710/204281546)                          |
| -                          | Spare 5/16” nuts           | 5/16” lock nut                     | [Most hardware stores](https://www.homedepot.com/p/Prime-Line-5-16-in-18-Grade-18-8-Stainless-Steel-Nylon-Insert-Lock-Nuts-50-Pack-9075332/310550302) |
| -                          | Spare 5/16” nuts           | 5/16” hex nut                      | [Most hardware stores](https://www.homedepot.com/p/Everbilt-5-16-in-18-Zinc-Plated-Hex-Nut-25-Pack-802354/204274092)                                  |
| -                          | Mast                       | Telescoping mast                   | [Wade Antenna](http://wadeantenna.com/product-category/mounts-masts/)                                                                                 |
| -                          | Quick links                | ⅜” Quick link                      | Any hardware store                                                                                                                                    |
| -                          | Mast foot                  | Swivel base                        | [Wade Antenna](http://wadeantenna.com/product/40-50-20hd-foot-telescoping-mast-swivel-base/)                                                          |
| -                          | -                          | Base plate                         | [Wade Antenna](http://wadeantenna.com/product-category/mounts-masts/)                                                                                 |
| -                          | Guy wire                   | 3/32” stainless steel wire rope    | Some hardware stores                                                                                                                                  |
| -                          | Wire rope thimble          | 3/32” Thimble                      | [Amazon](https://www.amazon.ca/gp/product/B07WTS6PP4/ref=ppx_yo_dt_b_asin_title_o02_s00?ie=UTF8\&psc=1)                                               |
| -                          | Crimping sleeve            | 3/32” crimping sleeve              | [Amazon](https://www.amazon.ca/gp/product/B0038YY2HM/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8\&psc=1)                                               |
| -                          | Turnbuckle                 | 5M or ¼” eye to eye turnbuckle     | [Amazon](https://www.amazon.ca/gp/product/B0774S5JJQ/ref=ppx_yo_dt_b_asin_title_o06_s00?ie=UTF8\&psc=1)                                               |
| -                          | Stainless steel wire       | 20-gauge Snare wire                | [Most hardware stores](https://www.homehardware.ca/en/165-20-gauge-stainless-steel-snare-wire/p/7685837)                                              |
| -                          | In-line wire tensioner     | In-line wire tensioner             | [Gallagher](https://www.gallagherfence.net/products/permanent-wire-tightener)                                                                         |
| -                          | Ratchet                    | Wire tensioner tool                | [Gallagher](https://www.gallagherfence.net/products/ratchet-wire-tightening-tool?_pos=1&_sid=52a363e77&_ss=r)                                         |
| -                          | -                          | Regular ratchet with ½” drive      | Any hardware store                                                                                                                                    |
| -                          | Carabiner                  | 6M carabiner                       | [Amazon](https://www.amazon.ca/gp/product/B06XG4QZ5F/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8\&psc=1)                                               |
| -                          | Anchor                     | #6 rebar (5-feet)                  | [Most hardware stores](https://www.homedepot.com/p/3-4-in-x-20-ft-6-Rebar-PAR402006/205370251)                                                        |
| -                          | -                          | Ground anchor                      | [Home depot](https://www.homedepot.com/p/6-Piece-Ground-Anchor-Kit-IS-50016/202197240)                                                                |
| Non-penetrating roof mount | Non-penetrating roof mount | NPRM-series (light- to heavy-duty) | [Wade Antenna](http://wadeantenna.com/product/heavy-duty-non-penetrating-roof-mount/)                                                                 |
| -                          | Mast                       | Masting                            | [Wade Antenna](http://wadeantenna.com/product/masting/)                                                                                               |
|                            |                            |                                    |                                                                                                                                                       |
|                            |                            |                                    |                                                                                                                                                       |
|                            |                            |                                    |                                                                                                                                                       |
|                            |                            |                                    |                                                                                                                                                       |
|                            |                            |                                    |                                                                                                                                                       |
|                            |                            |                                    |                                                                                                                                                       |
|                            |                            |                                    |                                                                                                                                                       |
