# Two-view DLT homography estimation

From two views of the same subject with overlapping features calculate the homography matrix such that we can stitch the two images onto each other. Using SIFT extract matching points from the two images. Use RANSAC to find the best homography matrix. The best homography matrix is found by checking the percentage of inliers of the computed homography matrix for four corresponding points. 


Completed at ANU in COMP4528 Computer Vision.
