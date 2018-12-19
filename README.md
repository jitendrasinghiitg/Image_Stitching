# Image_Stitching
Tutorial on image stitching with minimum Graph cut and colour correction
this tutorial uses:
1. sift features as feature descriptors
2. Flann based maching
3. Ransac for homograpy matrix
4. After projection of new image on the anchor image ,we use Ransac for colour correction in HSV space
5. Minimum cost path ,to get best cut between wo images
 
