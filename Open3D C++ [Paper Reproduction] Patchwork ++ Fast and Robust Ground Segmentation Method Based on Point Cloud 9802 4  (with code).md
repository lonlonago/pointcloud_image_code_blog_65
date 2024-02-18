##  First, the principle of the algorithm 

###  1. Git source code 

  This is the latest article from the Korean team in 2022: Patchwork ++: Fast and Robust Ground Segmentation Solving Partial Under-Segmentation Using 3D Point Cloud. Source code: https://github.com/url-kaist/patchwork-plusplus.git 

###  2. Overview of the paper 

  In the field of 3D sensing using 3D lidar, ground segmentation is a basic task for various operations such as drivable area detection and object recognition. There are many ground segmentation methods, but they all have some limitations. First, some methods require parameter tuning, which is time-consuming and laborious. Second, even after the parameters are adjusted, undersegmentation occurs in some areas, which means that the segmentation fails. Finally, when the ground is above another structure (e.g. the curb), a suitable ground cannot be segmented. To solve these problems, we propose a robust ground segmentation algorithm called Patchwork ++, which is an upgrade of Patchwork. Patchwork ++ uses adaptive ground likelihood estimation (A-GLE) to calculate the appropriate parameters based on the previous ground segmentation results. In addition, Temporary Ground Recovery (TGR) takes advantage of temporary pavement properties to solve some of the under-segmentation problems. At the same time, regional vertical plane fitting (R-VPF) is introduced to correctly segment the ground even at different heights. Finally, we propose a Reflected Noise Removal (RNR) method based on a 3D lidar reflection model, which can effectively eliminate virtual noise points. We use the SemanticKITTI dataset for qualitative and quantitative evaluation. 

###  3. References 

>  [1] Patchwork++: Fast and Robust Ground Segmentation Solving Partial Under-Segmentation Using 3D Point Cloud 

##  Code implementation 

patchworkpp.h 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574530477
 ```  
patchworkpp.cpp 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574530477
 ```  
nain.cpp 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574530477
 ```  
##  III. Display of results 

![avatar]( 894a0db788b6479db6068a71e567eb26.png) 

##  IV. Relevant links 

[1] 2022年最新成果——Patchwork++地面分割 [2] Patchwork++：基于点云的快速、稳健的地面分割方法 

