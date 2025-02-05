# Linear-Independence-and-Span-Check

# Overview

This repository contains Python sscripts to solve problems related to linear algebra, specifically verifying linear independence, spanning sets, and determining bases in R^3.

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
