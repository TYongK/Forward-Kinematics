# Forward-Kinematics
These Codes are C# based Forward Kinematics for Rhino3d Grasshopper environment.
Grasshopper sample file can be downloaded from the Repository.

![insta](https://user-images.githubusercontent.com/93954052/141040882-f02d604e-0f3e-4fec-857b-0d2f9bc7f516.gif)

-Grasshopper Screenshot

![Image](https://user-images.githubusercontent.com/93954052/141043407-a0d5b869-d55b-4961-bf6e-6acf13e4d933.png)

## *Math Note*

**Rotation Matrix**

![image](https://user-images.githubusercontent.com/93954052/141042683-1bf2ecc2-a582-4873-9d04-dadbd21c244d.png)

**dot(Translation Matrix, Rotation Matrix)**

-In order to do dot producto of both rotation matrix and translation matrix,

-The matrix uses 4x4 matrix with matrix[3][3] = 1

![image](https://user-images.githubusercontent.com/93954052/140992231-b1639a53-35b7-4683-b828-9861e7c31c5a.png)

![image](https://user-images.githubusercontent.com/93954052/140984642-e915051d-1c83-4b4f-9f5d-f13740d88d72.png)
