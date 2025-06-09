# Tag Metadata

Metadata informs Motus when to look for tags in raw detection data, when tag codes can be reissued, helps ensure that the permanent data archive is accurate and complete, and makes data presentable to the public.

## Required tag metadata

### Tag registration

All tags used with Motus [must first be registered.](tag-registration.md)

### Tag deployments

The table below outlines the minimum requirements for tag metadata to acquire detections from Motus.

<table><thead><tr><th width="211.97548774387195">Name</th><th align="center">Importance</th><th>Description</th></tr></thead><tbody><tr><td>Deployment start date and time</td><td align="center"><mark style="color:red;"><strong>Required</strong></mark></td><td>The time when the tag was activated and attached to an animal</td></tr><tr><td>Species</td><td align="center"><mark style="color:red;"><strong>Required</strong></mark></td><td>The species the tag was attached to. For tests, please do not enter a species and check the 'test deployment' box.</td></tr><tr><td>Latitude and longitude</td><td align="center"><mark style="color:red;"><strong>Required</strong></mark></td><td>The location where the animal was released with the tag attached and activated</td></tr><tr><td>Federal band (ring) number</td><td align="center"><mark style="color:red;"><strong>Required (when available)</strong></mark></td><td>The band number or ring number of the bird or bat. Insect tag numbers are optional. </td></tr><tr><td>Other measurements</td><td align="center"><mark style="color:green;"><strong>Recommended</strong></mark></td><td>Any additional measurements of the tagged animal, such as weight, age, and sex, should also be included.</td></tr></tbody></table>

## <mark style="color:orange;">Entering Metadata</mark>

{% hint style="warning" %}
* To ensure the most accurate detection data, please enter your updated tag metadata as soon as possible, and **allow 24 hours before uploading your receiver detection data** after submitting tag metadata.&#x20;
* **Do not** enter a deployment end date unless the tag was actually recovered and deactivated. Otherwise, Motus will automatically calculate the end date of the tag using a generous buffer in case the tag lasts longer than anticipated.
* If you do you end up _not_ deploying tags and holding on to them for future use, create a placeholder deployment record with a start date well in the future to ensure that the tag code / burst interval combo is not reissued.
{% endhint %}

## Why metadata is so important

Metadata is a critical part of the Motus infrastructure. Not only does it inform our algorithms which search for tag detections on when to look for specific tags, it also helps make sense of data that are presented to the public. As the Motus community grows, the importance of accurate and up to date metadata grows exponentially.

### How metadata is used to detect tags

Motus stations receive radio signals from Lotek radio transmitters (i.e.; tags attached to animals) as a series of pulses that are all on the same frequency. It's the specific timing between these radio pulses that encodes the ID number of these tags (see [**How Tags Work**](../../tags/how-tags-work.md)). We decode Lotek tags from radio signals ourselves using a complex algorithm called [_**tag finder**_](../../about-motus/how-data-are-processed/tag-finder.md). This algorithm takes into account the possibility of multiple tags being present and emitting a signal at the same time.

To improve the performance and accuracy of _tag finder_, Motus only search for tags that are known to be active at any given time. To accomplish this, _tag finder_ references a master list of all registered tags along with the dates when they were active (‘_deployments’_). Occasionally, some tag detections are missed because \_tag finder \_doesn't know that certain tags are active, usually because of missing or inaccurate metadata in our system.

## How does Motus know when tags are active?

Most tags are deployed on animals and never seen again, so most tag deployments will have a start date, but no end date. This is the correct way to enter deployment metadata if a tag is not retrieved again after deployment as it allows our system to calculate the end date on its own. This end date is calculated as the predicted lifespan (provided to us by the manufacturer) plus an additional 50% to account for unusually long-lasting tags. This predicted lifespan is calculated based on the tag model number, so it’s important to ensure that information is correct as well. The examples below use a theoretical tag with a predicted lifespan of 60 days.

![](../../.gitbook/assets/tag-metadata-ex1.png)

### Default deployment date

In reality, it’s impractical to enter tag deployment metadata immediately upon releasing each animal, so we have built in a couple safe guards to help mitigate this issue. The first is that tags will be searched for by Motus immediately upon registration if no deployment exists for those tags. The registration date has historically been recorded as the _quarter-annum_, so tag finder will act as though each tag was deployed on the first day of that _quarter-annum_. Not desirable, but better than nothing.

![](../../.gitbook/assets/tag-metadata-ex2.png)

### Anticipated deployment date

Default deployment dates are only present as a backup in case the researcher has forgotten to include their _earliest_ _anticipated start date_ during tag registration. An anticipated start date is basically the earliest day on which the researcher plans to deploy tags. This should provide ample time to update the tag metadata after the field season is over.

![](../../.gitbook/assets/tag-metadata-ex3.png)

### Deployed tags

Once a tag has been deployed, it's deployment metadata should be updated to reflect the real deployment date. Otherwise, tag finder might think the tag expired too early.

{% hint style="warning" %}
**Remember:** providing an anticipated deployment date will buy you more time before you need to update these data.
{% endhint %}

![](../../.gitbook/assets/tag-metadata-ex4.png)

### Undeployed tags <a href="#undeployed-tags" id="undeployed-tags"></a>

Because of the limited number of tag code / burst interval combinations, tags with these properties may be reissued to other projects if the tags are presumed to be dead or inactive. Tags that were not deployed during the expected tagging period should be given placeholder deployment recorders well into the future. This will ensure that they remain on the "active tags" list and are not reissued.&#x20;

**Example:** You had 20 tags you expected to deploy in June 2023 and for which you made placeholder deployment record with anticipated start dates (as described above). However you were only able to deploy 18 of the tags and want to retain the remaining two tags for next year. You would modify the deployment record for the two undeployed tags and change the start date to some date in the future -- say July 1, 2024. This will ensure that the tag codes will not be reissued to another project. After you do finally deploy them, update the tag deployment metadata to reflect the actual deployments.

{% hint style="info" %}
Undeployed tags should:

1\) be stored in correct conditions. See [**Tag Storage**](../../tags/tag-storage.md) for more information

2\) be given placeholder deployments with start dates well into the future to ensure that the unique code/burst interval combo is not reissued
{% endhint %}

## Consequences of bad metadata

Bad metadata to be information related to deployments which is either missing or inaccurate. We can use the example scenario above to predict what might happen when metadata isn't kept up to date.

* If there is no deployment data for a tag, _tag finder_ will assume the tag has expired and will stop searching for it long before it should. In our example, the default deployment period has no overlap with the actual active period, meaning it will only search for the tag before it was actually ever deployed. Therefore, no detections would exist for this tag.
* If only an anticipated deployment date exists, there may be some overlap with the actual deployment period, but there could still be a lot of data missing from the end of the tag lifespan.
* If there are left over tags after the field season or if a tag is recovered and the existing deployments aren't terminated, manufacturers might reissue the tags which can result in ambiguous detections. That means there could be two tags deployed at the same time that appear identical to each other deployed at the same time, making it difficult or impossible to accurately identify the individual.

![](../../.gitbook/assets/tag-metadata-ex5.png)
