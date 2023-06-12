# MatlabGUI-Particle-detect
## Overview

This code is developed in Matlab to detect red blood cells and cluster of red blood cells as particles in different sizes. User can decide what cluster sizes to be used in the anlaysis. The code will do image processing on the video that is uploaded then count and track particles in different clusters. The clusters then are color coded and output video is produced from each image. This GUI and code can be used anywhere for processing and tracking particles that have different sizes. 

Each detected particle is fit to an ellipse that encases the particle in question. The major and minor axis of the fitted ellipse, as well as the total area and
the orientation from the horizontal axis, are saved in a csv file format. The algorithm then takes the overall pixel area and scales the fitted ellipse appropriately to match the area. The fitted ellipse data is then used to present the ellipse size, the axis ratio (minor over major axis) and orientation of the individual aggregate. This creates a more accurate ellipsoid projection in two dimensions.

Keywords: Size distribution, Velocity distribution, Image processing, Red Blood Cell, Particle detection, Cell detection
