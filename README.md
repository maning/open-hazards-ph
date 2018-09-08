# open-hazards-ph

A repo for archiving publicly available hazards geospatial data created by various agencies in the Philippines.
Data is available as a simple download for everyone to use.

## What is the license of the data?

We respect the license of the original source, each data source have a corresponding license file.  License varies from different agencies, in most cases government data are public domain.

## How do I access the data?

Data are hosted in AWS S3, the public access are available at: `https://s3.amazonaws.com/open-hazards-ph/`.
For example, to download landslide vector for Abra, go to: 
`https://s3.amazonaws.com/open-hazards-ph/noah/LANDSLIDE/vector/Abra_LandslideHazards.shp.geojson.zip`

## Is there an API to access the data?

None at the moment, this might change, patches welcome!
But you can programatically access the data in some form, check the [examples](/examples) directory.

## Most data archived here are available in other government websites, why do this?

Philippine government data policy changes from the tenure of an administration to another, we want to ensure
that what was public will remain public even if projects ran out of funds or there is a change in access policy.

## I found some cool hazards data, will you host it?

Yes! Please [open a ticket](../../issues/new) and let's discuss.

## Who maintains this repo?

* Maning Sambale **[@maning](https://github.com/maning)**
* RK Aranas **[@rukku](https://github.com/rukku)**
