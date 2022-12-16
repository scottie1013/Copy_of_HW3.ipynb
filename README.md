# Image classifying
The idea is to explore and overview a more realistic image dataset, named cifar100. It has 60_000 colorful images so looking at each of them is not a good idea. Instead we will use tSNE and kMeans and also look at nearest neighbours (in the Euclidean metric). 

Before, we played mostly with MNIST. It shows real data, but it is a heavily-preprocessed, idealized dataset. Now our goals are to:
- See how these methods fare when applied to more realistic images. 
- Observe what patterns are picked up in the images, and understand why that happens.
- Try to understand limitations of using the Euclidean distance to capture the dissimilarity between images  (so don't expect spectacular results!)

Mathematically, we will mostly work with (high-dimensional) vectors, norms, distances, sums, means.

There will be 3 main parts:
- Loading data, checking format etc.
- Exploratory data analysis with tSNE
- Clustering with kMeans (informed by the above part)

And an extra part where you can upload you image and see similar images.
