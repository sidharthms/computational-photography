The source code (in Seam Carving.ipynb) can also be viewed at https://github.com/sidharthms/computational-photography/blob/master/HW3/Seam%20Carving.ipynb

Q2:
The energy image looks the way it does since we define the parts of the image with high gradient to have high energy. As a result regions of the image containing edges have high energy making edges look white in the image.
The cumulative minimum energy image was computed by accumulating energies from the left, that's why the image is darker on the left and brighter on the right where the cumulative min energies are the highest. We also notice higher cumulative mini energies in regions with a lot of high level texture such as the bottom region where there are a lot of tables and people.

Q3:
These are optimal seams because they go minimally over regions with high gradients such as boats. 
Hence removing those seams would not be very noticeable making them good for image resizing.

Q4:
Seam carving works well here because the image has small repetitive patterns which can be cleanly removed without drawing attention.

Q5:
Seam carving does not do well here because the image has large patterns in the image (tiles). Hence no part of the iamge can be removed without drawing attention.
