This is project for Midterm:3D Object Dectection. 
# Compute Lidar Point-Cloud from Range Image
## Visualize range image channels
Range image is showed in below picture.
![ID_S1_EX1](https://user-images.githubusercontent.com/99339837/159145228-eac0a99b-b6dc-4011-b7c7-9da4ae08f1ba.jpg)
## Visualize point-cloud 
In the PCL, cars are found. below picture shows some examples. some cars are sedan. some cars are pickup.
![ID_S1_EX2_03_cars-circled](https://user-images.githubusercontent.com/99339837/159145310-4049e955-183a-415a-919f-ddc7d9d1c2cc.jpg)
![ID_S1_EX2_01_cars-circled](https://user-images.githubusercontent.com/99339837/159145565-2d133724-f6df-466c-999f-0b5ea0c73d72.jpg)
Also some feastures can be differed. In below picure, wheels is triangled. Mirror is rectangled. Headlamp is yellow circled.
![ID_S1_EX2_features](https://user-images.githubusercontent.com/99339837/159145402-d4994a01-84f7-4a0f-94a4-08d5f46f0129.jpg)
# Create Birds-Eye View from Lidar PCL
## Convert sensor coordinates to BEV-map coordinates
Convert sensor coordinates to bev-map coordinates
![ID_S2_EX1](https://user-images.githubusercontent.com/99339837/159146088-8ee56661-0c7d-45c3-adcd-a8c2b3639c7b.jpg)
Intensity layer of bev-map

![ID_S2_EX2](https://user-images.githubusercontent.com/99339837/159145776-332da5a1-d7c1-4435-828a-ee1c8859b690.jpg)

Height layer of bev-map

![ID_S2_EX2_Height ](https://user-images.githubusercontent.com/99339837/159145780-b2daea02-7e78-4138-9f2c-ed3ea67cf0d2.jpg)
# Model-based Object Detection in BEV Image
##
##Compute precision and recall
![屏幕截图 2022-03-22 213845](https://user-images.githubusercontent.com/99339837/159494656-83368db3-2c1c-4485-b697-7b8c47836128.png)
![屏幕截图 2022-03-22 213927](https://user-images.githubusercontent.com/99339837/159494664-1c6e4503-153c-4110-8760-47c50dad1064.png)
