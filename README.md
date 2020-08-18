# Analysis-of-3D-facial-data
Dissection of a 3D triangulated point cloud

This r function is to dissect a 3D image or a 3D triangulated point cloud along a user-specified path on the surface of an object (functioning as a scissor). The outcome consists of complete triangulated pieces where the path is a part of their edges. The use of it needs the call of other functions in the package "face3d" which is lead by Professor Adrian Bowman (["face3d" package page](https://www.google.com)).
Note that the development of this function is at an early stage and only works for specific circumstance.

"Dissected part 1" and "Dissected part 2" are the screenshots of the dissection of "A 3D image of lip with path". The user-specified path is shown as a series of black dots which are identified from the red dots (landmarks manually placed on the image). 
