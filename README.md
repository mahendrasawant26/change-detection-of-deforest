# Change Detection in Multi-temporal Satellite Images  
In this job, I collaborated with <a href="https://github.com/mahendrasawant26">Mahendra Sawant</a>  

## Table of contents
1. [Overview](#Overview)
2. [Requirements](#Requirements)
3. [How to detect change?](#How)


<a name="Overview"/>  

## Overview
In this project, we built a machine learning model to detect changes in multi-temporal satellite images.  
It uses Principal Component Analysis (PCA) and K-means clustering techniques over difference image.  

<a name="Requirements"/>

## Requirements
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • OpenCV (version 4.2.1).  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • Python (version 3.6.9).  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • Scikit-learn ML Library.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • The directory `images` contains multi-temporal images developed from the LANDSAT images available in the United States Geological Survey (USGS) <a href="https://remotesensing.usgs.gov/gallery/image_collections?cat=all">website</a>. You can find some of multi-temporal image pairs in `images` directory.  


<a name="How"/>

## How to detect change? 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • Go to `scripts` directory and Run `python DetectChange.py -io <FIRST_IMAGE> -it <SECOND_IMAGE> -o <OUTPUT_DIRECTORY>` to detect change in two multi-temporal satellite images.  
**NB**: The output directory should end with '/'.   
The script will generate a difference image named `difference` and a `ChangeMap` image.   
Other images are generated depending on morphological transformations.





# Output

Training and experimentation on datasets
The change detection model will be trained both on the large-scale datasets such as U.S.
Landsat Analysis Ready Data (ARD), Sentinel-2 and Eurostat and dataset that will be
populated based on Indian context as part of this project.

![image](https://github.com/mahendrasawant26/change-detection-of-deforest/assets/110108264/282ff203-a1ca-493b-b6bc-e93c773e08e2)

![image](https://github.com/mahendrasawant26/change-detection-of-deforest/assets/110108264/7dd781bc-f7b4-4fda-b687-a66fcc16aa1d)


# UML Diagram
![image](https://github.com/mahendrasawant26/change-detection-of-deforest/assets/110108264/4fc4a0c8-6f08-411c-b7b9-69cbb436f856)


# Change Detection
![image](https://github.com/mahendrasawant26/change-detection-of-deforest/assets/110108264/cc3a3c02-3bb7-4af4-a838-061867823733)

![image](https://github.com/mahendrasawant26/change-detection-of-deforest/assets/110108264/e56a29eb-11d1-4d89-a6ee-5d41ca42a33d)




