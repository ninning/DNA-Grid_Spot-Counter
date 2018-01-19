# DNA-Grid_Spot-Counter
These sets of scripts are meant to be used for analysis of DNA origami grids, 
typically after imaged with DNA PAINT super-resolution Imaging.

The full workflow will take a large .png image (~20k x 20k pixels) and do the following:

1. Identify all DNA grids and their positions within entire image
2. Identify number of imaged points per grid, typically anywhere from 3-12
3. Identify corner points (If needed)
4. Creates a heatmap of counted points across the image.

# Software Needed
MATLAB 2016b or later

Computer Vision Toolbox is also required
