# Datasets
RGB-D and Ambient Occlusion Datasets  

The [ScanNetDataset](https://github.com/ScanNet/ScanNet)ScanNet is an RGB-D video dataset containing 2.5 million views in more than 1500 scans, annotated with 3D camera poses, surface reconstructions, and instance-level semantic segmentations.

We complete the incomplete depth image and generate estimating normal image and boundary image from rgb image with this method. Our result NyuDataset contain 500k+ pair sample. It features:

  - rgb image.
  - Matching origin incomplete rawDepth image.
  - Matching complete depth image.
  - Matching estimating normal image from rgb image.
  - Matching estimating boundary image from rgb image.
  
 ## Warning: if you want to use this dataset, be sure to apply for the right to use it( fill out an [agreement](kaldir.vc.in.tum.de/scannet/ScanNet_TOS.pdf) to the ScanNet Terms of Use and send it to scannet@googlegroups.com).

