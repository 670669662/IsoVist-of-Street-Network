
# 2D Isovist and Pedestrian trajectory

## Introduction
This algorithm is for mimics Pedestrian's trajectory in the city while filtering Visible range and marking out the information of the surrounding buildings they see.

The project uses two grasshopper plug-ins, 'caribou' and 'decodingSapce'.

## Example
![01](https://user-images.githubusercontent.com/70087271/130240732-769e06e4-6d7d-44c8-9ad6-96e70d18b2c8.png)
![02](https://user-images.githubusercontent.com/70087271/130240739-162b4ea7-9886-4fed-bda7-d4cb56ca0a3a.png)
![03](https://user-images.githubusercontent.com/70087271/130240744-109e7db4-4302-4284-be5f-11e3d84d42fb.jpg)

## Use

- Step 1

Use caribou to select building information and output redundant buildings without specific information.
![Step 1](https://user-images.githubusercontent.com/70087271/130242282-9d50c405-f1dd-46db-91b4-e23157778441.png)


- Step 2

Select motion trajectory and perform time simulation.
![Step 2](https://user-images.githubusercontent.com/70087271/130242290-48af050c-7b50-4fed-97e2-c33653644c14.png)



- Step 3

Use the core command isovist to perform calculations. Note that you can use gpu to improve operating efficiency.

![Step 3](https://user-images.githubusercontent.com/70087271/130242298-aedbcd95-8d53-41f3-a34a-b2f1bdcb1965.png)



- Step 4

Simulate the people's field of vision during walking, and at the same time select the obstructive buildings that people see, and visualize the basic information of these buildings in real time.

![Step 4](https://user-images.githubusercontent.com/70087271/130242303-2df4bd9a-b997-45a2-841a-fd409dc9250d.png)





## Reference
https://toolbox.decodingspaces.net/tutorial-2d-and-3d-isovists-for-visibility-analysis/

https://caribou.philipbelesky.com/



