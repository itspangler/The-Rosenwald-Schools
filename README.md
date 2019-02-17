# The-Rosenwald-Schools

Comprehensive GIS dataset of the Rosenwald schools across the US South

Rosenwald schools -- dataset of schoolhouses, whether extant or NOT

599 of 5400 -- soon I'll be making a blog post for how I put together the dataset over the summer

I would love to add to that blog post an interactive map that 1) shows the locations and names of Rosenwald schools and 2) the attribute table that people could scroll through beneath it

Good way to put this together with github pages? the workflow would be
1. states, counties, labels (scaled), schools w/ names and some other basic info from Fisk database
2. set it up to easily be embedded
3. attribute table as object that can be interacted with, scrolled through
4. form that people could say "I know of a school that isn't on here, let me submit it" -- and send to my email a lat/long/name/email address to respond -- basically a ripoff of the ArcOnline geoform

Service where you can embed a form -- get a form that can be emailed to an address or a table you can access

Service (ifeally free) that you could iframe in -- service for collecting user input -- plain design and you can iframe it into your github page -- they could then manage the html (minimum javascript) and the data (geojson but also shapefile available) and then a service attached to it that they could use -- kobo toolbox? Import geojsons, launch the forms through cellphones, etc -- free for humanitarian work
