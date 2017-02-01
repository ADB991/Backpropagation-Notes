# Backpropagation-Notes
Wrote while studying Udacity's [Nanodegree Foundation in Deep Learning](https://www.udacity.com/course/deep-learning-nanodegree-foundation--nd101)

Inspired by [this video](https://www.youtube.com/watch?v=GlcnxUlrtek) and the careful approach of Andrew Ng in his [coursera course on ML](https://www.coursera.org/learn/machine-learning) (although he does not go into this much detail).

Although backpropagation is confusing, at its core, it is just careful application of partial differentiation and the chain rule. Writing these notes made me really understand it, hopefully it helps others too! I added a bit about partial derivatives, which is meant as a map for those who are just learning about them or just rusty, like me.

TOC

### 1 First things first: Partial Derivatives
We are going to swiftly go through the required notions to understand backpropagation. If you know this stuff, go to the next bit. I’ll try to keep the notation quite close to what we use in a computer code, which mostly implies remembering of the number of columns and not bother with domains, mappings and other neat mathematical notions.
#### 1.1 One or two variables
#### 1.2 Many variables and gradients
#### 1.3 The Chain Rule and Matrices
#### 1.4 The Kronecker delta

### 2 Backpropagation
I’m gonna go through the derivation of the formula for calculating the gradients in a setting that is most similar to Project 1, but with a notation that can be easily generalised to other network architectures.
#### 2.1 Set Up
#### 2.2 Feedforward
#### 2.3 Cost Function
#### 2.4 Backpropagation
