### Workshop Exercise 1: Segmentation
[Download TIF file](seminar_workkshop/images/HT29_nuclei.tif)  
Human HT29 colon cancer cells,  Image from [Broad Bioimage Benchmark Collection](https://bbbc.broadinstitute.org/BBBC008) 
  
#### Global segmentation  
Open above image by dragging it into the Fiji window and run Threshold command: <code>Image > Adjust > Threshold...</code>  
Choose different thresholding methods (such as Default, Huang, Otsu etc.) from the drop down list and check how well they perform on your image.  
Once satisfied with a particular method or by manually selecting the lower and upper threshold values (using sliders), click on the Apply button to generate a thresholded image.  

**Note**: All thresholding methods (such as Default, Huang, Otsu etc.) can be tested at once by using <code>Image > Adjust > Auto Threshold</code>  
  
#### Local segmentation  
Select your original image and run the command: <code>Image > Adjust > Auto Local Threshold</code>.  
Run with "Try all" methods to check which one gives the best result. For this image, the best segmentation is achieved with the <code>Phansalkar</code> method.  

#### Deep Learning based segmentation using [StarDist](https://imagej.net/plugins/stardist)  
Select your original image and run the command: <code>Plugins › StarDist › StarDist 2D</code>  
  In the follow up menu, choose Model: <code>Versatile (fluorescent nuclei)</code> and click on the <code>Set optimized thresholds</code> button at the bottom. Keep other settings as deafult. Click OK.  
A segmentation label image will be generated with the nuclei ROIs added to the ROI Manager.  