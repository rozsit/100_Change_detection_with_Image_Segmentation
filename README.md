Change Detection with Instance Segmentation (GeoAI + SAM ViT-H)
This project performs change detection between two geospatial raster images (GeoTIFF) using instance segmentation with the GeoAI library and the Segment Anything Model (SAM, ViT-H variant).
The workflow includes preprocessing, change detection, statistical analysis, and visualizations.

📌 Features
Automatic spatial alignment – crops both images to their overlapping geographic extent.

Change detection – detects changes between two time periods using SAM ViT-H.

Probability and binary masks – generates probability maps and binary change masks.

Instance segmentation – identifies individual changed objects with attributes (IoU, stability, area).

Comprehensive reporting – produces detailed visual and statistical reports.

Visualization overlay – displays detected changes as transparent overlays on the newer image.
