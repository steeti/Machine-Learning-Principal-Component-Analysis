# Machine-Learning-Principal-Component-Analysis
# Introduction

Principal Components Analysis, (PCA), is a dimensionality reduction algorithm that can
be used to significantly speed up your unsupervised feature learning algorithm. For
example, when you train your model on a dataset such as images, some of our data
points may be meaningless in explaining our desired target variable. Therefore, we
prefer to drop them from our training.

# Part 1: Users to Movies

In this task, we work with a Users-to-Movies dataset from http://web.stanford.edu/class/cs246/slides/06-dim_red.pdf. 

Each row contains the scores provided by a user while each column has the scores given by different users
on the same movie. The first 4 users prefer Science Fiction and the others prefer
Romance. You will need to implement  PCA algorithm and calculate the features after PCA. 

# Part 2: Human Faces

In this task, we will need the "Labeled Faces in the Wild" dataset from https://scikit-learn.org/stable/datasets/index.html#labeled-faces-in-the-wild-dataset. 

The dataset contains images of faces. Each image is a 62x47 pixel array. The images are read into a matrix. The rows of the
matrix are the images (examples). The features (columns) are the pixels. Each
example is represented by a vector of real numbers of length 2914, listing the pixels
from left to right, row by row, from top to bottom.
