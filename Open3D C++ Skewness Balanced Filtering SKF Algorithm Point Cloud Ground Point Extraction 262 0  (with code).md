##  First, the principle of the algorithm 

###  1. Overview of the principle 

  The SKF algorithm assumes that the elevation probability density distribution of natural ground points in the point cloud obeys a normal distribution. Non-ground points will make the elevation probability density distribution of points in the point cloud deviate from the normal distribution, showing a skewed distribution. The skewness represents the degree of deviation from the normal distribution. In order to make this distribution reach the state of normal distribution, it is necessary to remove non-ground points with higher elevations that interfere with the point cloud elevation probability density distribution from the point cloud data samples, so as to "correct" the skewness of the data to achieve equilibrium. For each correction, the point with the highest elevation is marked as a non-ground point, and the iteration is carried out until the skewness is approximately equal to 0, and the remaining points are ground points. Complete filtering to separate ground points and non-ground points. 

The steps of the algorithm are as follows: 

![avatar]( 44056b70b7ce47feaeebe0ddd13fa80a.png) 

###  2. References 

>  Feng Maolin. Building Contour Extraction from Airborne Lidar Point Cloud under Tree Occlusion [D]. Southwest Jiaotong University, 2017. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574596726
 ```  
##  III. Display of results 

![avatar]( 095f6e06eaab49c897029f8616a19b13.png) 

