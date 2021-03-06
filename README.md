# ImLoDe
Improved Local Decisions source code for transformting the CAD-60 contents into CGC-2014 file formatting:

Both CAD-60 (Cornell Action Dataset) and CGC-2014 (Chalearn Gesture Challenge dataset) have been widely used recently. In order to produce a common evaluation on both datasets, we present here a Matlab code allowing to transform the contents of the CAD-60 into the exact same format of CGC-2014.

https://drive.google.com/open?id=0B8j93wrL0gu5Zi1jcmxnTkZrZkU 

This code allows to:

    produce an extra information relative to the user-mask video streams  
    generate video streams out of the RGB and depth images
    compute the 2D positions for the skeletal data
    generate skeleton files in the same format of CGC-2014 using quaternion angles instead of rotation matrices
    generate the according labeling files


The produced output from CAD-60 has the same file presentation as in CGC-2014. One can for instance use the CGC-2014 python codes to make its algorithm work on both datasets.
