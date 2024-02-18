##  First, the principle of the algorithm 

###  1. Overview of the principle 

  First, the points are sorted according to the curvature value of the points, and the point with the smallest curvature value is selected as the initial seed point. The area where the initial seed point is located is the smoothest area. Growing from the smoothest area can reduce the total number of segmented segments and improve efficiency. 

###  2. Algorithm flow 

##  Code implementation 

RegionGrowing.h 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574547530
 ```  
RegionGrowing.cpp 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574547530
 ```  
main.cpp 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574547530
 ```  
##  III. Display of results 

![avatar]( c382185d4a484575a27eccdb417808f8.png) 

##  IV. Relevant links 

[1] PCL：超详细的基于法向量和曲率的区域生长算法原理以及源码解读 [2] PCL 区域生长分割 

