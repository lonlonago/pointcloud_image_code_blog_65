##  First, the main function 

###  1. Read the mesh 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574588834
 ```  
  The function call reads the mesh based on the filename extension. 

  Compared to point cloud data structures, meshes have triangles that define a three-dimensional surface. By default, Open3D attempts to infer the file type by filename extension. The following mesh file types are supported: 

ReadTriangleMeshFromGLTF() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574588834
 ```  
ReadTriangleMeshFromOBJ() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574588834
 ```  
ReadTriangleMeshFromOFF() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574588834
 ```  
ReadTriangleMeshFromPLY() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574588834
 ```  
###  2. Save the mesh 

WriteTriangleMesh() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574588834
 ```  
  Save the mesh to a local folder. The function calls the write function based on the extension filename. If the write function supports binary encoding and compression, the latter two arguments will be used. Otherwise they will be ignored. Currently, only the .obj format supports uv coordinates (triangle_uvs) and textures. 

WriteTriangleMeshToGLTF() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574588834
 ```  
WriteTriangleMeshToOBJ() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574588834
 ```  
WriteTriangleMeshToOFF() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574588834
 ```  
WriteTriangleMeshToPLY() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574588834
 ```  
WriteTriangleMeshToSTL() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574588834
 ```  
###  3. Display mesh 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574588834
 ```  
   Visualize point clouds. Use the mouse/trackpad to view geometric shapes from different angles. Press the H key to print out a complete list of keyboard commands for the GUI. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574588834
 ```  
##  III. Display of results 

![avatar]( fa4bd6d285514dbcade8ff91ae794319.png) 



--------------------------------------------------------------------------------

##  First, the main function 

###  1. Read the point cloud 

Reload method 1 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
Overload mode 2 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
  Read the point cloud from the file. When the user does not fill in the extension of the point cloud, it will be automatically decoded; if the extension is filled in, it will try to decode the file according to the extension. 

1. ReadPointCloud is used to read point cloud data. By default, Open3D attempts to infer the file type by file extension. The following point cloud file types are supported: 

ReadPointCloudFromPCD() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
ReadPointCloudFromPLY() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
ReadPointCloudFromPTS() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
ReadPointCloudFromXYZ() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
ReadPointCloudFromXYZN() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
ReadPointCloudFromXYZRGB() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
###  2. Save the point cloud 

WritePointCloud() 

Reload method 1 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
Overload mode 2 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
  Save the point cloud to a local folder. 

WritePointCloudToPCD() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
WritePointCloudToPLY() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
WritePointCloudToPTS() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
WritePointCloudToXYZ() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
WritePointCloudToXYZN() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
WritePointCloudToXYZRGB() 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
###  3. Display point cloud 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
   Visualize point clouds. Use the mouse/trackpad to view geometric shapes from different angles. Press the H key to print out a complete list of keyboard commands for the GUI. 

##  Code implementation (including reading the TXT format) 

###  1. Read common point clouds 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
###  2. Read the point cloud in txt format 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
##  III. Display of results 

![avatar]( a62c50afa6af49fb9be50995036cba4b.png) 

##  Visualize two point clouds 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
![avatar]( 8bfeb24a985d4937aca3b2106ed3157c.png) 

##  Fifth, give some clouds color 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
##  Display the color of the point cloud itself 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
![avatar]( 29158c5286964369878bd78ebbd19ab5.png) 

##  Conversion between pcd and txt 

###  1、.pcd转xyz.txt 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
###  2、xyz.txt转.pcd 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579859
 ```  
![avatar]( a8061e31ffab4cc9826ecb0d1c83f904.png) 



--------------------------------------------------------------------------------

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



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

  If a point has more than one point within a certain distance threshold area, it is considered to have duplicate points. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574547028
 ```  
##  III. Display of results 

![avatar]( 9091dfc1a6654a29831b398e35457c4d.png) 



--------------------------------------------------------------------------------

##  First, uniform sampling 

  Open3D includes the ability to extract point clouds from triangular meshes. The easiest way is to sample_points_uniformly extract points uniformly from a 3D surface based on the triangular area. Parameters number_of_points define the number of points sampled from the triangular surface. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515378
 ```  
##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515378
 ```  
##  III. Display of results 

![avatar]( cdf0494d410a47199c01e7713a81fa5b.png) 



--------------------------------------------------------------------------------

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



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###   1. Overview of the principle 

  The Ball Rotation Algorithm (BPA) is a method of surface reconstruction related to alpha-shapes. Intuitively, imagine a three-dimensional sphere with a given radius and we place it on a point cloud. If it hits any 3 points (and it doesn't fall out of those 3 points), it creates a triangle. The algorithm then starts rotating from the edge of the existing triangle, creating another triangle every time it reaches 3 points and the ball doesn't fall out. 

###   2. Function analysis 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574537350
 ```  
  Implemented the ball rotation algorithm proposed by F. Bernardini et al. (F. Bernardini et al., "The ball-pivoting algorithm for surface reconstruction", 1999. "). The implementation is also based on the algorithm outlined in Digne 2014 in" An Analysis and Implementation of a Parallel Ball Pivoting Algorithm ", 2014." Surface reconstruction is done by rolling a ball of a given radius on a point cloud, creating a triangle every time the ball touches three points. 

###   3. References 

>  [1] Bernardini F , Mittleman J . The ball-pivoting algorithm for surface reconstruction[J]. Visualization & Computer Graphics IEEE Transactions on, 1999, 5(4):349-359. [2] Ball pivoting 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574537350
 ```  
##  III. Display of results 

![avatar]( 5f5b2a2a2b5b47b3aef055b165bf672e.png) 



--------------------------------------------------------------------------------

##  First, statistical filtering 

###   1. Main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574584415
 ```  
###   2. Algorithm source code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574584415
 ```  
##  Code implementation 

###   1. Version 1 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574584415
 ```  
###   2. Version 2 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574584415
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574584415
 ```  
![avatar]( ae2a31d584d1418991a570dff0f97d15.png) 

##  IV. Python code 

Open3D statistical filter 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574572043
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574572043
 ```  
##  IV. Relevant links 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Three-point fixed surface 

  To determine the plane equation for three points in three-dimensional space, the key is to find a normal vector of the plane. To do this, the normal vector of the plane is perpendicular to these two vectors, so:  

###  2. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574597569
 ```  
  This function calculates the coefficients of a plane equation using three points, and returns an invalid plane (0, 0, 0, 0) if the three points are collinear. 

###  2. Algorithm source code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574597569
 ```  
##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574597569
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574597569
 ```  


--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Overview of the principle 

>  The original English paper has a very detailed formula derivation process. Considering the age of the paper, it is difficult to download. Therefore, here is a screenshot of the derivation process in the paper. 

![avatar]( 058b9d5ee7e446868a8fc4be0f17c841.png) 

###  2. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515195
 ```  
This function returns the transformation matrix between two sets of points. 

###  3. Algorithm source code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515195
 ```  
###  4. References 

>  [1] Umeyama S. Least-squares estimation of transformation parameters between two point patterns[J]. IEEE Transactions on Pattern Analysis & Machine Intelligence, 1991, 13(04): 376-380. 

##  Code implementation 

###  1. Detailed process 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515195
 ```  
###  2. Call the function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515195
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574515195
 ```  
##  IV. Relevant links 



--------------------------------------------------------------------------------

##  First, uniform sampling 

###   1. Main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574580958
 ```  
###   2. Algorithm source code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574580958
 ```  
##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574580958
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574580958
 ```  
![avatar]( fdca2e976f17450b865c3dcda0708380.png) 

##  IV. Python code 

Open3D Uniform Downsampling 



--------------------------------------------------------------------------------

##  I. Overview 

![avatar]( a9e9cff7b2c9472b8f3f826dd484465b.png) 

   Open3D does not implement the function of drawing planes, so write your own code to achieve it. The effect is as follows:  

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957451477
 ```  
##  III. Display of results 

![avatar]( 3ad6ccdf418647b6a676ab5c49f6880f.png) 



--------------------------------------------------------------------------------

##  1. Draw the arrow 

main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
![avatar]( be9def752d9d4a1cbc80b19e539f7f8b.png) 

 result display  

##  2. Draw the sphere 

main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
![avatar]( ad5571143bd448e7ba2f21b53a87c0f8.png) 

 result display  

##  3. Draw the plane 

##  4. Draw the cylinder 

main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
![avatar]( 60d150693d474c38abd1671f62d8e6e1.png) 

 result display  

##  5. Draw cones 

main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
![avatar]( 150f3321e88c477bb184fbd418d87f2b.png) 

 result display  

##  6. Draw the circle 

main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
![avatar]( 9d67c12396ac4284b5579ce64e012638.png) 

 result display  

##  7. Draw tetrahedrons 

main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
![avatar]( 49686506baf54f97ac9b71bf53b90877.png) 

 result display  

##  8. Draw cubes 

main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
![avatar]( 7a1e0776c9f944f2817e45ad559d3288.png) 

 result display  

##  9. Draw the octahedron 

main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
![avatar]( 4b08beeed6264f389f70b709f7de3385.png) 

 result display  

##  10. Draw the icosahedron 

main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
![avatar]( 3c11f79fc6004557bcea57d7d467731d.png) 

 result display  

##  11. Draw the Mobius Ring 

main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
![avatar]( 8498ff2f7a114e8c8dd12057203627ae.png) 

 result display  

##  12. Draw the coordinate system 

main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574573069
 ```  
![avatar]( d7cde7f81cdc4893bcab600abc8d942c.png) 

 result display  



--------------------------------------------------------------------------------

##  I. Overview 

![avatar]( db329ec9c683492098958c0a4f7490f4.gif) 

   When I get a new point cloud dataset, I want to quickly see the shape characteristics of the point clouds in the dataset. However, for a dataset with thousands of point clouds, dragging the point clouds into the software to view them one by one is obviously extremely inefficient. Therefore, the code implements the file path and file format of a given point cloud dataset, and automatically visualizes each point cloud in a folder dynamically in batches.  

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574543720
 ```  
##  III. Display of results 

![avatar]( 0735d1e8d1584c90ba984c6e8f0ab33b.gif) 



--------------------------------------------------------------------------------

##  Voxel downsampling 

###   1. Main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579915
 ```  
###   2. Algorithm source code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579915
 ```  
##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579915
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579915
 ```  
![avatar]( 99040d96af0d40509e321b2900bc69d5.png) 

##  IV. Python code 

Open3D Voxel Downsampling 



--------------------------------------------------------------------------------

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



--------------------------------------------------------------------------------

In Open3D, the commonly used methods for building point cloud models are: 8. 3D reconstruction 

##  Function analysis 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574516132
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574516132
 ```  
##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574516132
 ```  
##  III. Display of results 

![avatar]( 0d6c80b4255644c1bb8d52f6ca1ccdb4.png) 



--------------------------------------------------------------------------------

##  Download Open3D-0.15.2 

![avatar]( 16b1ef6136a5427fba0589344ffd94ae.png) 

 Download URL: http://www.open3d.org/docs/release/#Download the version of interest and extract it to the local folder. 1. I downloaded the X86_64 Release version, and the decompression path is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574553026
 ```  
2. Add the bin folder to the environment variables:  

##  Compile 

##  1. Create a new file 

![avatar]( 7b848e39fcb042e296d636d9b0b21f05.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574553026
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574553026
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574553026
 ```  
##  2. Cmake settings 

1. Add the file path 

![avatar]( 6e52288c0b3e425a94c041bd632117df.png) 

![avatar]( 338b2187880f4e549c508cc529218494.png) 

 2. Add Open3D local path   

3. Configure 

![avatar]( 5144d8138f38485f878f5f35253fe5d2.png) 

![avatar]( 9604965956fc4cf8b53c1770c4641489.png) 

 4. Generate  

![avatar]( 36824126e3af4d71aafbdaaaaa37b851.png) 

 5. Open Project  

##  III. VS2019 distribution library 

![avatar]( c9210fdcad544e17b8a56a64ba9de990.png) 

 ![avatar]( 20432db942114fcbb569527b00a48d9e.png) 

 1. Solution Configuration - Release 2. Set Startup Items  

##  IV. Display of results 

![avatar]( abd68d7845ad4a988e2f6b0c1b7876b2.png) 



--------------------------------------------------------------------------------

##  First, the basis for realization 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574552579
 ```  
##  III. Display of results 

![avatar]( 831fc35b2b194b248b1d1735fc360e32.png) 



--------------------------------------------------------------------------------

