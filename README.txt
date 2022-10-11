
Reference - 
Bar-Kochba, E., Toyjanova, J., Andrews, E., Kim, K.-S. & Franck, C. A Fast Iterative Digital Volume Correlation Algorithm for Large Deformations. Exp. Mech. 55, 261-274 (2015). Doi:10.1007/s11340-014-9874-2.



Extract the zip files. To run the traction code - 

1) Copy the 'before_deconv.tif' and 'after_deconv.tif' images to '..\Matlab Code\Example\'
2) Run MATLAB and add following directories to path - 
	- '..\Matlab Code'
	- '..\Matlab Code\Example\'
	- '..\Matlab Code\Supplemental MFiles\'
2) Open and run '...\Matlab Code\Example\Read_Tiff.m' - this should create 2 files 'vol00.mat' and 'vol01.mat'. 
3) Open '...\Matlab Code\Example\exampleRunFile.m' and input the final stiffness and possion ratio as material properties of the hydrogel (line#79)  
4) Run '...\Matlab Code\Example\exampleRunFile.m'