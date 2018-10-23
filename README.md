# SteppedThreshold-singlechannel
This macro takes a folder (with subfolders) of single channel ROI images of various sizes and quantifies the puncta per micron^2, area, and intensity at a range of thresholds (from 0-160 in steps of 3). The goal for this macro was to help determine the ideal threshold for small images with dense puncta and variable background intensity.

The inputs needed are the images and the areas of the ROI (purely for internal calculation of puncta per area, the raw # of puncta will be output if there is no area entered). The outputs are a sheet with the numbers for puncta per area, area, and intensity for each image, separated by condition and listed by threshold; a stacked image representing the masks of the ROI at each threshold; and the zip file for the ROI at each threshold (that can probably be taken out in future versions as it has not been spectacularly useful to retain as a file thus far).

