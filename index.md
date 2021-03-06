## WHO AM I?
25 years old ,Second year Computer Science student at the Tel
Aviv University.
First year completed at the Open University of Israel as overseas student. 
Shraing some of projects here


### Introduction to Machine Learning

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for
Sharing notebook and theoretical ideas I came across at Introduction to Machine Learning course.
Any section including the relevant  PDF soultions, ![equation](https://latex.codecogs.com/svg.image?\text{\TeX})   and py files

## ![equation](https://latex.codecogs.com/svg.image?%5Cinline%20%5CLARGE%20%5Ctextbf%7BSection%201%7D)
(Warm-up)

![equation](https://latex.codecogs.com/svg.image?\textbf{Theory&space;Part}&space;)
\
  [1.1](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section1.0/section_1.pdf) Linear Algebra
  \
  [1.2](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section1.0/section_1.pdf) Calculus and Probability
  \
  [1.3](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section1.0/section_1.pdf) Optimal Classifiers and Decision Rules
  \
  [1.4](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section1.0/section_1.pdf)  Multivariate normal (or Gaussian) distribution


![equation](https://latex.codecogs.com/svg.image?\textbf{Programming&space;Part}&space;)
\
[Visualizing the Hoeffding bound.](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section1.0/plot1.png)
[k-NN algorithm.](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section1.0/KNN.py)

## [![equation](https://latex.codecogs.com/svg.image?%5Cinline%20%5CLARGE%20%5Ctextbf%7BSection%202%7D)](https://github.com/saarbk/Introduction-to-Machine-Learning/blob/main/EX2/Section_2.pdf)
![equation](https://latex.codecogs.com/svg.image?\textbf{Theory&space;Part}&space;)
\
[2.1](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section2.0/Section2.pdf) PAC learnability of ???2-balls around the origin
\
[2.2](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section2.0/Section2.pdf) PAC in Expectation
\
[2.3](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section2.0/Section2.pdf) Union Of Intervals 
\
[2.4](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section2.0/Section2.pdf) Prediction by polynomials
\
[2.5](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section2.0/Section2.pdf) Structural Risk Minimization

![equation](https://latex.codecogs.com/svg.image?\textbf{Programming&space;Part}&space;)

[Union Of Intervals.](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/EX2/union_of_intervals.py)
Study the hypothesis class of a finite
union of disjoint intervals, and the properties of the ERM algorithm for this class.
To review, let the sample space be ![equation](https://latex.codecogs.com/svg.image?X&space;=&space;[0,&space;1]) and assume we study a binary classification problem,i.e. ![equation](https://latex.codecogs.com/svg.image?Y&space;=&space;0,&space;1).
We will try to learn using an hypothesis class that consists of k disjoint intervals. 
define the corresponding hypothesis as  

   ![equation](https://latex.codecogs.com/svg.image?%5Cinline%20h_I(x)=%5Cbegin%7Bcases%7D1%20&%5Ctext%7Bif%20%7D%20x%5Cin%20%5Bl_1,u_1%5D%5Ccup%20%5Cdots%20%5Ccup%20%5Bl_k,u_k%5D%20%5C%5C1%20&%5Ctext%7Botherwise%7D%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%5Cend%7Bcases%7D)
## ![equation](https://latex.codecogs.com/svg.image?%5Cinline%20%5CLARGE%20%5Ctextbf%7BSection%203%7D)
![equation](https://latex.codecogs.com/svg.image?\textbf{Theory&space;Part}&space;)
\
[3.1](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section3.0/section3.pdf) Step-size Perceptron
\
[3.2](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section3.0/section3.pdf) Convex functions
\
[3.3](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section3.0/section3.pdf) GD with projection
\
[3.4](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section3.0/section3.pdf) Gradient Descent on Smooth Functions

![equation](https://latex.codecogs.com/svg.image?\textbf{Programming&space;Part}&space;)

[SGD for Hinge loss.](Section3.0/sgd.py)
In the file skeleton sgd.py there is an helper function. The function reads the examples labelled 0, 8 
and returns them with the labels ???1/+1. In case you are unable to
read the MNIST data with the provided script, you can download the file from [ Here](https://github.com/amplab/datasciencesp14/blob/master/lab7/mldata/mnist-original.mat). 

![equation](https://latex.codecogs.com/svg.image?\inline&space;\large&space;\bg{red}\ell(y)_{hinge}=\max&space;(0,1-\mathbf{x}_i&space;y_i))


[SGD for log-loss.](Section3.0/sgd.py)
In this exercise we will optimize the log loss defined
as follows:

![equation](https://latex.codecogs.com/svg.image?\ell_{log}(\mathbf{w},x,y)&space;=&space;\log(1&plus;e^{-y\mathbf{w}\cdot&space;x}))
## ![equation](https://latex.codecogs.com/svg.image?%5Cinline%20%5CLARGE%20%5Ctextbf%7BSection%204%7D)
![equation](https://latex.codecogs.com/svg.image?\textbf{Theory&space;Part}&space;)
\
[4.1](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section4.0/section_4.pdf) SVM with multiple classes
\
[4.2](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section4.0/section_4.pdf) Soft-SVM bound using hard-SVM
\
[4.3](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section4.0/section_4.pdf) Separability using polynomial kernel
\
[4.4](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section4.0/section_4.pdf) Expressivity of ReLU networks
\
[4.5](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section4.0/section_4.pdf) Implementing boolean functions using ReLU networks. 

![equation](https://latex.codecogs.com/svg.image?\textbf{Programming&space;Part}&space;)

[SVM](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section4.0/svm.py)
Exploring different polynomial kernel degrees for
SVM. We will use an existing implementation of SVM, the SVC class from `sklearn.svm.`


[Neural Networks](https://github.com/saarbk/Introduction-to-Machine-Learning/tree/master/Section4.0/svm.py)
we will implement the back-propagation
algorithm for training a neural network. We will work with the MNIST data set that consists
of 60000 28x28 gray scale images with values of 0 to 1.
Define the log-loss on a single example

![equation](https://latex.codecogs.com/svg.image?%5Cinline%20%5Cell_%7B(%5Cmathbf%7Bx,y%7D)%7D(W)=-%5Cmathbf%7By%7D%5Clog%5Cmathbf%7Bz%7D_L(%5Cmathbf%7Bx;%5Cmathcal%7BW%7D%7D))

And the loss we want to minimize is

![equation](https://latex.codecogs.com/svg.image?%5Cinline%20%5Cell(%5Cmathcal%7BW%7D)=%5Cfrac%7B1%7D%7Bn%7D%5Csum_%7Bi=1%7D%5E%7Bn%7D%5Cell%20(%5Cmathbf%7Bx%7D_i,%5Cmathbf%7By%7D_i)(%5Cmathcal%7BW%7D)=%5Cfrac%7B1%7D%7Bn%7D%5Csum_%7Bi=1%7D%5E%7Bn%7D-%5Cmathbf%7By%7D_i%5Cast%20%5Clog%20%5Cmathbf%7Bz%7D_L(%5Cmathbf%7Bx%7D_i;%5Cmathcal%7BW%7D))
## K means
The K-means algorithm is a popular clustering method for finding a partition of N 
unlabeled observations into K distinct clusters, where K is a parameter of the method.
we willimplement this algorithm in both Python and C. 

Given a set of ![equation](https://latex.codecogs.com/svg.image?\mathbb{N}) datapoints such that ![equation](https://latex.codecogs.com/svg.image?x_1,x_2\dots&space;x_n&space;\in&space;\mathbb{R}^d). the goal is to group the data into ![equation](https://latex.codecogs.com/svg.image?k\in&space;\mathbb{N}) clusters,
each datapoint is assigned to exactly one cluster and the number of clusters ![equation](https://latex.codecogs.com/svg.image?k) is such that ![equation](https://latex.codecogs.com/svg.image?1<k<n).
We will denote the group of clusters by ![equation](https://latex.codecogs.com/svg.image?S_1,&space;S_2,&space;\dots&space;,&space;S_k), each cluster ![equation](https://latex.codecogs.com/svg.image?S_j)  is represented by it???s centroid
which is the mean ![equation](https://latex.codecogs.com/svg.image?\mu_j&space;\in&space;\mathbb{R}^d) of the cluster???s members.
```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
### Computational Models
### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/saarbk/saarbk.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we???ll help you sort it out.
