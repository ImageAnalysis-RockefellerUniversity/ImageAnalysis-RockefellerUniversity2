## Workshop
In this workshop, we will work through the following exercises:
1. Segmentation using global threshold, local threshold and Deep Learning (StarDist)
2. Cell tracking using StarDist and TrackMate
3. Denoising using Noise2Void
4. Bonus – 3D segmentation using StarDist and TrackMate

### Installing required plugins in Fiji
We will be adding the following three [updates sites](https://imagej.net/update-sites/following) in our Fiji to install all the required plugins for this workshop:   
- [CSBDeep](https://imagej.net/plugins/csbdeep)
- [StarDist](https://imagej.net/plugins/stardist)
- [TrackMate-StarDist](https://imagej.net/plugins/trackmate/trackmate-stardist)  
  
Step 1: Start Fiji.  
Step 2: Select Help > Update... from the menu bar.  
Step 3: Click on the button "Manage update sites".  
Step 4: Scroll down the list and tick the checkboxes for update sites: CSBDeep (shown below), StarDist and TrackMate-StarDist, then click the Close button.  
  ![CSBDeep update site](PNGs/CSBDeep_screenshot1.png)  

Step 5: Click on "Apply changes" to install the plugins.  
Step 6: Restart Fiji. StarDist plugin should now be available under <code>Plugins > StarDist > StarDist 2D</code>.  
        Noise2Void plugin should be visible under <code>Plugins › CSBDeep › N2V</code>.