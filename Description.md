## Genomic Data Clustering 
# Background 
The discover of DN, and the critical role it plays in information storage for all biological beings, was a seminal moment for the biological sciences. All the information that is needed for the functioning of a living cell is encodec in and ultimately derived from the DNA of that cell, and this holds true for all biological organism on the planet 

**DNA can be represented as a text sequence, with an alphabet that only has four letters - A - C - G and T.** The diversity of living organism and their complex properties is hidden in their genomic sequences. One of the most exiting problems in modern science is to understand the organization of living matter by reading genomic sequences.

One distinctive message in a genomic sequence is a piece of text, called a gene. Genes can be oriented in the sequence in either the forward or backward directions. In the highest organism the notion of a gene is more complex.

It was one of the many great discoveries of the th century, that biological information is encoded in genes by means of trples of letters. called codons in the biological leterature.

In this exercise, we will see that it is possible to verify the validity of the discovery of three-letter codons, simply by performing unsupervised learning on the genetic sequence 

# Problem Statement

The work starts with a fragment of the genomic sequence of the bacterium Caulobacter Crescentus. This sequence is given as a long text file (300 kb), and the task is to look at the file and ensure that the text uses the alphabet of four letters (A, C, G, and T) and that these letters are used without spaces. It is noticeable that, although the text seems to be random, it is well organized, but we cannot understand it without special tools. Statistical methods may help us do so. 

In this case study, we accept data from a genome and have the goal of identifying useful genes versus noise. Unfortunately, we don't know which sequences of genes are useful, so we have to use Unsupervised Learning to infer this. 

In the notebook we walk through the following series of steps:
- First, the data is imported adn prepared. Initially, the sequence, a single string, is split into non-overlapping substrings of length , and we may then count the combinations of the distinct 1,2,3 and 4-length sequences of base pairs that appear in each possible substring. 
- PCA is performed to try to identify the internal structure of the data
- Finally if PCA reveals some internal structure the we'ill apply clustering techniques to the dataset. 

We will see that it is possible to verify the validity of the discovery of three-letter codons, simply by performing unsupervised machine learning on the genetic sequences 
