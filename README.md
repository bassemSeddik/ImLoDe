# ImLoDe
Improved Local Decisions source code for the CAD-60 and CGC-2014 datasets
 CAD-60 into CGC-2014
Both CAD-60 (Cornell Action Dataset) and CGC-2014 (Chalearn Gesture Challenge dataset) have been widely used recently. In order to produce a common evaluation on both datasets, we present here a Matlab code allowing to transform the contents of the CAD-60 into the exact same format of CGC-2014.

https://drive.google.com/open?id=0B8j93wrL0gu5Zi1jcmxnTkZrZkU 

This code allows to:

    produce an extra information relative to the user-mask video streams  
    generate video streams out of the RGB and depth images
    compute the 2D positions for the skeletal data
    generate skeleton files in the same format of CGC-2014 using quaternion angles instead of rotation matrices
    generate the according labeling files


The produced output from CAD-60 has the following organization:

Notice that this is the same file presentation as in CGC-2014:

This way, you can for instance use the CGC-2014 python codes to obtain similar results, and of course, to have your algorithm working on both datasets.
