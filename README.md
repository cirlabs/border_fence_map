# border_fence_map
GIS data for the U.S.-Mexico border fence (perhaps a wall in the future)

### Copyright and license
Reveal's border fence shapefiles are open data, licensed under the Open Data Commons Open Database License (ODbL) by Reveal from The Center for Investigative Reporting.

You are free to copy, distribute, transmit and adapt the shapefiles, so long as you:

- Credit Reveal as specified below.
- Inform Reveal that you are using the shapefiles in your work by emailing Michael Corey at mcorey@revealnews.org.

If you alter or build upon our data, you may distribute the result only under the same licence. The [full legal code](https://opendatacommons.org/licenses/odbl/1.0/) explains your rights and responsibilities.

###How to credit Reveal

We require that you use the credit “Reveal from the Center for Investigative Reporting and OpenStreetMap contributors”.

You must also make it clear that the data is available under the Open Database License. If you are distributing the shapefiles in a data form, you can name and [link directly to the license](https://opendatacommons.org/licenses/odbl/1.0/). 

### Fields in the data

The first six fields are the primary fields of interest for most users. The remaining fields are to preserve references to OpenStreetMap data from [our original fence map project](http://cironline.org/blog/post/surprising-tools-cir-used-map-us-mexico-border-fence-6255). While the current fence data has not been imported into OpenStreetMap, we hope to do so in the future.

|Column name|Format|Description|
|---|---|---|
|id|integer|Row ID|
|gen_type|string|General type of fence. Options are "pedestrian," "vehicle" and an empty string for unknown fence types.|
|project|string|Which government project was the segment built under. Options are "Legacy" (i.e. built before the Secure Fence Act), "PF225", "VF300", "PF70" and an empty string for unknown fence types.|
|seg_name|string|The U.S. government name for the segment. All non-legacy fencing segments should have designations.|
|created|date/time stamp|The date/time when the segment was created in Reveal's database.|
|updated|date/time stamp|The date/time when the segment was last updated in Reveal's database.|
|last_osm_d|date/time stamp|The date/time when the segment was last edited in OpenStreetMap, where applicable.|
|way_id|integer|OpenStreetMap way id when downloaded, where applicable.|
|barrier|string|OpenStreetMap barrier tag, where applicable.|
|taglist|string|OpenStreetMap tag list, where applicable.|

### More about the project
You can [read more about our fence/wall mapping work on our website.](https://www.revealnews.org/article/the-wall-building-a-continuous-u-s-mexico-barrier-would-be-a-tall-order/)
