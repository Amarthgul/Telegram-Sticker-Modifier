# Resizing images for Dicsord emotes

By deafult, this script copies all `.jpg` and `.png` images, resizes them into `128x128` and stores the output images in a new folder. 

Discord stated that emotes uploaded must:

* Resolution smaller or equal to `128x128`
* File size smaller or equal to `256KB` 

Therotically a `128x128` image cannot exceeds `256KB`, so size is not considered in this script. 

# To use this

If you have Python and PIL installed, copy the file to the folder that contains the images you want to convert, then double click to run. 
A new folder called `OutputImages` will be created containing all the converted images.
