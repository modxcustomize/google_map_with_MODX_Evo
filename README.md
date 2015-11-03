# MODX EVOLUTION google map integration with markers 
A document can serve as a MAP center point and it's child documents can serve as markers on it

#### Coded with Love by modxdeveloper
[![Twitter]](http://twitter.com/modxdeveloper)
[![Youtube]](https://www.youtube.com/watch?v=WmAt3QbbP0s&feature=youtu.be)
[![Facebook]](http://facebook.com/pages/Modx-support/159804034043556)
[![Google+]](https://plus.google.com/109498197448404992305)
[![Email]](mailto:modx.customize@gmail.com)
[![MODX EVOLUTION google map integration with markers]( http://www.phpcmsmodx.info/assets/images/gm.png)](https://www.youtube.com/watch?v=WmAt3QbbP0s&feature=youtu.be "MODX EVOLUTION google map integration with markers")

## To install:
1. Download
2. Unzip the downloaded file.
3. Add a new template.html with the code from the template or add the code from this file into needed template 
4. Create a new chunk: scriptwrapper and update it with a content from file scriptwrapper.chk
5. The template uses the chunk {{scriptwrapper}} and the chunk scriptwrapper uses a Ditto call to iterate through the child documents of this page (the map document should be a container)
6. Create a new chunk for this Ditto snippet call to load results parsed via this teplate: google.maps.tpl and update it with a content from file google.maps.tpl.chk
7. Create 2 TV for latitude and longitude, set them as text. Also create another TV and name it as markerImage type image.
8. Update TV values of latitude,longitude with the coordinates of the map center, and set markerImage TV value with the image needed on the map per each marker.
9. Create child documents in the MAP document container to be used as markers on your map. Each document must have set the TV values per coordinates, i.e. latitude,longitude. Each document pagetitle will serve as a title of the marker.
10. Done.  
 

## Features
* **  
* **  
 
## Compatibility
MODX Evolution CMS

## Community
- ** Find a bug?** [Open an issue](https://github.com/modxcustomize/google_map_with_MODX_Evo/issues). Try to be as specific as possible.
- ** Have a feature request** [Open an issue](https://github.com/modxcustomize/https://github.com/modxcustomize/google_map_with_MODX_Evo/issues). Tell me why this feature would be useful, and why you and others would want it.

