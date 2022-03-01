---
layout: page
title: "Lab: Mapping"
---

In this lab, we will work with a couple of derived datasets related to the correspondence series of the Rutgers College War Service Bureau records. The plan is to import these datasets into a web-based application called [Palladio](https://hdlab.stanford.edu/palladio/), where we will experiment with visualization.

## Needed for this lab

- Your favorite browser
- The [`wsb_palladio_letters.csv`](https://rutgers.box.com/s/c71qee7r2lbvblmkqsiupct8osogytl8) dataset
- The [`wsb_palladio_places.csv`](https://rutgers.box.com/s/yu9hme5vk5jsrv7xmzm1x9qoz7p7qpsi) dataset

## Getting started

Download the the CSV files above to your desktop by right clicking, and selecting *Save link as* Open it up in a spreadsheet application (e.g. Numbers, Excel, or Google Sheets) and have a look at the data and the headers. Notice any inconsistencies and NA values. How might those have come about?

I was hoping to get us as far as creating our own location data in connection with our assigned alumni, but I underestimated the time it would take to get through the text encoding lab. My bad. Instead, I am sharing with you the correspondence metadata I have so far gathered in connection with the WSB letters. One of the perks associated with nice structured data like TEI XML is that data extraction and manipulation becomes fairly easy (not easy easy, but reasonably so for someone with a bit of programming know-how). Certainly much easier than parsing a bunch of unstructured textual data. Can you connect some of these data points back to places in the TEI XML letters that you were asked to complete?

## Loading Data

Let's follow Palladio's tutorials for loading and extending data:

- [How to load data in Palladio](https://hdlab.stanford.edu/palladio/tutorials/data/)
- [How to extend data in Palladio](https://hdlab.stanford.edu/palladio/tutorials/extendtable/)

We will need to start first with loading the letters dataset. Then, we will extend `source-location-id` and `destination-location-id` with the places dataset.

## Visualizing Data

Next, we will follow this tutorial to create a "Point to point" visualization to see our correspondence network.

- [Create a map](https://hdlab.stanford.edu/palladio/tutorials/map/)

Finally, let's create a Timeline filter to see the number of letters by date sent. Let's **not** filter out NA values, which might be a reasonable choice if not for the fact that this dataset has some inconsistencies, and instead visualize all the data for this step.

- [Create a Timeline Filter](https://hdlab.stanford.edu/palladio/tutorials/timeline/)

## Questions to Explore

1. What do you notice about the "Point to point" visualization in Palladio? Were you surprised by any of the locations appearing on the map?
2. When do you speculate might have been Earl Reed Silvers's busiest month, according to these data? What was going on in the war at that time?
3. How might a map visualization shed light on to a collection of historical letters? What can it tell us that reading the letters might not?
