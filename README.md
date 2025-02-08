# Linear-Independence-and-Span-Check

# Overview

This repository contains Python scripts to solve problems related to linear algebra, specifically verifying linear independence, spanning sets, and determining bases in R^3.

# Problem Statement

![Screenshot 2025-02-04 172652](https://github.com/user-attachments/assets/63285ee2-a8fb-4e6f-be39-d8a8aec83b1a)

1. <ins> Checking Linear Independence and Span for {v1,v2,v3}:

    1. Determine if the set {v1,v2,v3} is linearly independent.
  
    2. Verify if {v1,v2,v3} spans R^3.

2. <ins> Checking if {b1,b2,b3} is a Basis for R^3:

    1. Verify if {b1,b2,b3} forms a basis by checking rank and independence.

# Methodology

The calculations are performed using Python and the NumPy library.

1. <ins> Linear Independence Check</ins>

   1. Compute the determinants of the matrix formed by the vectors as columns.
  
   2. If the determinant is non-zero, then the vectors are independent.
  
2. <ins> Span Check </ins>

   1. Compute the rank of the matrix formed by the vectors.
  
   2. If the rank equals the dimension, then the vector spans R^3.
  
3. <ins> Basis Verification </ins>

   1. A set of vectors is a basis if they are linearly independent and spans the vector space.
  
   2. This is confirmed by checking if the rank is 3.

# Results

1. <ins> For {v1,v2,v3}</ins>

    1. Determinant is 6, meaning the set is linearly independent.
  
    2. Rank is 3, meaning the set spans R^3.
  
    3. The set forms a basis for R^3.
  
2. <ins> For {b1,b2,b3}</ins>

    1. Rank is 2, meaning the set is not independent and does not span R^3.
  
    2. The set does not form a basis for R^3.
