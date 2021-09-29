![sanborn header](https://raw.githubusercontent.com/cam-rodriguez/sanborn/main/01790_09_1894-0000.jpg)
# sanborn ️‍🔥️‍🔥️‍🔥
digitized sanborn fire insurance maps, in .shp or .geojson format (probs). chicago-focused, chicago-made!
***
## What are you even doing? 
I noticed that there weren't a whole lot of GIS-ready Sanborn Fire Insurance maps, which sucked as someone who loves mapping and loves archives. The Sanborn Fire Insurance company _does_ have GIS-ready files (basemaps and structures) available, but I'm broke and don't plan on selling my soul in order to make a couple maps for personal interest projects.

I drew a lot of inspiration from [this project](https://www.arcgis.com/apps/webappviewer/index.html?id=f4cf486b4d7f4988aa589e7dd989f5e9) from Phillipe Gonzalez, who is a Historic Preservation Specialist in Bozeman, Montana. The approach, which is overlaying Sanborn maps with satellite imagery, was something that kind of opened my eyes to what's possible with these kinds of maps! The only problem I have with it? It's only in Montana!
***
## Okay, how are you doing it?
I'm georeferencing images that I've downloaded from the [Library of Congress Geography and Maps Division](https://loc.gov/rr/geogmap/)'s collection of [Sanborn maps](https://www.loc.gov/collections/sanborn-maps/about-this-collection/), using [a script](https://github.com/LibraryOfCongress/data-exploration/blob/master/maps/maps-downloading-querying.ipynb) that they wrote up that I modified for my own purposes and what I'm looking at. The script allows me to download a volume of Sanborn fire insurance maps in bulk, instead of individually, which I had been doing. (Live and you learn.)

Then I'll load them in to QGIS, typically in batches of about ten. From there, I'm using the [Freehand Raster Georeferencer](https://gvellut.github.io/FreehandRasterGeoreferencer/) and [tools within the Advanced Digitizing Toolbar](https://www.qgistutorials.com/en/docs/digitizing_basics.html) to do some fun stuff, including georeferencing the individual map pages and some other super fun and totally not tedious stuff like _hand-tracing structures within the different maps aka creating shapefiles of every single f*cking building_ which is, again, totally worth my time. (It is!)

![index](https://www.loc.gov/rr/geogmap/sanborn/images/index.gif)
***
## What's your plan? 
I'm still getting through georeferencing, and that'll likely take a while. I've been getting creative with file management and creating clean packages to upload here based on how Sanborn organizes their data and what makes the most sense for the modern day, so that's the main thing here. I'll likely upload by neighborhood!
***
## okay so when are you focusing on? 
It's a SECRET!! you'll find out when I start to upload stuff. :-) (or check out the header for hints)
***
## okay, right. how can i get in touch? i have questions/comments/advice/etc!
Send me a DM on [Twitter](https://twitter.com/journo_cam), and I'll get on it! Also crodri93 at depaul dot edu is a great place to start, too. 


