# Color-Identification-in-Images
Colors in the images are identified here.

Library used : OpenCV
Tool : Jupyter notebook

When the image file is read with the OpenCV function imread(), the order of colors is BGR (blue, green, red). 
It is then converted to RGB.
Next RGB converted to HEX,it takes input in the form of values for Red, Green and Blue ranging from 0 to 255 and then converts those values to a hexadecimal string that can be used to specify color.
Then all the colors are identified from the image and plotted in the form of piechart.
