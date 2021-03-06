# Flicker data processing
This application is in Scala and uses a MapReduce architecture.

## Description
This dataset contains a list of photos and videos. This list is compiled from data available on Yahoo! Flickr. All the photos and videos provided in the list are licensed under one of the Creative Commons copyright licenses, and as such they can be used for benchmarking purposes as long as the photographer/videographer is credited for the original creation. In particular, the data in this dataset was made available under one of the following licenses:

* [Attribution-NonCommercial License](http://creativecommons.org/licenses/by-nc/2.0/)
* [Attribution-NonCommercial-ShareAlike License](http://creativecommons.org/licenses/by-nc-sa/2.0/)
* [Attribution-NonCommercial-NoDerivs License](http://creativecommons.org/licenses/by-nc-nd/2.0/)
* [Attribution License](http://creativecommons.org/licenses/by/2.0/)
* [Attribution-ShareAlike License](http://creativecommons.org/licenses/by-sa/2.0/)
* [Attribution-NoDerivs License](http://creativecommons.org/licenses/by-nd/2.0/)

Note that, before publishing any photo or video in a report or elsewhere, it must be ensured that the photo is still available in the public domain.

This dataset is formed by a single file that contains the following tab-separated fields per line:
* Photo/video identifier
* User NSID
* User nickname
* Date taken
* Date uploaded
* Capture device
* Title
* Description
* User tags (comma-separated)
* Machine tags (comma-separated)
* Longitude
* Latitude
* Accuracy
* Photo/video page URL
* Photo/video download URL
* License name
* License URL
* Photo/video server identifier
* Photo/video farm identifier
* Photo/video secret
* Photo/video secret original
* Photo/video extension original
* Photos/video marker (0 = photo, 1 = video)

The fields that contain free-form text have been URL-encoded. Not all fields may have a value, in particular the camera, title, description, tags, EXIF, longitude, latitude and accuracy fields may remain empty.

In case researchers need photo/video content for their work, we kindly ask that they download the data responsibly, e.g. do not use a distributed system to download the photos and videos massively in parallel.
