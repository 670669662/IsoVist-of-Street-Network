
# IsoView of street network comparison

## Introduction
The purpose of the grasshopper plug-in development is to facilitate urban designers and landscape designers to compare the value of isoview on the way when the road traffic reaches the green space. The plug-in is different from other isoview plug-ins in that it introduced the comparison between the most calculated distance and the specific IsoView value (Area, degree of closure, elongation, etc.), so as to facilitate the designer to compare the difference between the past and the current planning or the difference between different parts of the city.

Before you start：

- Grasshopper in rhino 6/7
- Install “caribou”plugin（You can download it through rhino's package manager or food 4rhino）＆ “Decoding scape"(https://toolbox.decodingspaces.net/download-decodingspaces-toolbox/)
- Use open streetmap download data （You can download data from this website “openstreetmap.org/#map=5/38.007/-95.844”

Color and graphic Display
- orange：isoview bases on human position
- Black：Berlin Wall (or other city barrier)
- Green: Park area
- Pink: Start point
- Blue: End point

Note：
1. Please try to keep the OSM file size within 100mb, too large files will cause the plug-in to crash or the computer crashes
2. After loading the file, please give the computer a few minutes to extract the osm data
3. Users can selectively turn on the isoviewGPU acceleration module according to their computer configuration to increase the calculation speed

## Operating Procedures

01.Plugin frame work

![微信图片_20210927114321-01](https://user-images.githubusercontent.com/70087271/134842852-7adbf9ff-395c-410a-93c9-ba9276879a5d.jpg)

02.Plugin Operation


## Operating Reults

01.Static spatial distance comparison

![1633578597(1)](https://user-images.githubusercontent.com/70087271/136317653-188eb4e0-609a-4659-ac7b-57117a2e7682.png)

02.Comprehensive IsoView data comparison


![1633578957(1)](https://user-images.githubusercontent.com/70087271/136317831-e74c7f1e-27e8-48fe-b8e2-6f03004c948d.png)


03.Individual IsoView data comparison

![1633578508(1)](https://user-images.githubusercontent.com/70087271/136317841-f5473a63-8d88-4588-a283-39b9f325a5f1.png)














## Reference
https://toolbox.decodingspaces.net/tutorial-2d-and-3d-isovists-for-visibility-analysis/

https://caribou.philipbelesky.com/



