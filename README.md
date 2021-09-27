
# 2D IsoView movement Comparison

## Introduction
The purpose of the grasshopper plug-in development is to facilitate urban designers and landscape designers to compare the value of isoview on the way when the road traffic reaches the green space. The plug-in is different from other isoview plug-ins in that it introduces the concept of segmentation and comparison, so as to facilitate the designer to compare the difference between the past and the current planning or the difference between different parts of the city.

Before you start：

- Grasshopper in rhino 6/7
- Install “caribou”plugin ＆ “Decoding scape" （You can download it through rhino's package manager or food 4rhino）
- Use open streetmap download data （You can download data from this website “openstreetmap.org/#map=5/38.007/-95.844”

Color and graphic Display
- orange：isoview bases on human position
- White：Berlin Wall (or other city barrier)
- Green: Park area
- Pink: Start point
- Blue: End point

Note：
1. Please try to keep the osm file size within 100mb, too large files will cause the plug-in to crash or the computer crashes
2. After loading the file, please give the computer a few minutes to extract the osm data
3. Users can selectively turn on the isoviewGPU acceleration module according to their computer configuration to increase the calculation speed

## Operating Procedures

01.Plugin frame work

![微信图片_20210927114321-01](https://user-images.githubusercontent.com/70087271/134842852-7adbf9ff-395c-410a-93c9-ba9276879a5d.jpg)

02.Plugin Operation

![微信图片_20210927115410](https://user-images.githubusercontent.com/70087271/134843183-dc8a327a-269f-4429-b168-8f94ec3dd2ab.png)

## Operating Reults

01.Isoview Comparison

![1632710287(1)](https://user-images.githubusercontent.com/70087271/134843207-b6c55556-e406-4e56-b568-9d94cd070bee.jpg)

02.Optional Comparison Data

![1632710755(1)](https://user-images.githubusercontent.com/70087271/134843285-02a7a641-b9a4-42b4-8247-f884e46885ab.png)
![微信图片_202109271107191](https://user-images.githubusercontent.com/70087271/134843289-b57fbe3d-8b50-4f28-8967-eaf32eb5b861.png)













## Reference
https://toolbox.decodingspaces.net/tutorial-2d-and-3d-isovists-for-visibility-analysis/

https://caribou.philipbelesky.com/



