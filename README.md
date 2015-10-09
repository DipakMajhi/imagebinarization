# imagebinarization
Performs binarization of images efficiently.

Process:

Just enter the path in :

imFolder = '  ';  
e.g :  imFolder = 'G:\image processing\Text Extracted Folder\New folder\old train data';
and run the code in MATLAB, it will give the binarized in the same folder itself, so make sure you make a back up of the images for safety.

It is a bit more efficient then conventional Otsu's Binarization method that is commonly used for binarization 
because it make blockproc function , that scans though the image in a blocksize that could be varied in the code 
depending upon user need.
