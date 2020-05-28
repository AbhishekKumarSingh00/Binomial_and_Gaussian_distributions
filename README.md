## Prerequisites
- Python 3.7+
- matplotlib package
- numpy package
- pandas package

## dist_prob_binomial_gaussian

This python package helps you to calculate Binomial and Gaussian distribution

My python package link 
https://pypi.org/project/dist-prob-binomial-gaussian/
It is upload in pypi.org website

It also print Graph (Histogram, Bar Chart, Line Plot) as per given data.


- [It can be calculated as :-](#how-to-calculate)

- [Files in package](#files)

- [Installation](#installation)

## How To Calculate

1. You can calulate by providing mean and standard deviation to object. Example:-  gaussian = Gaussian(25, 2)
2. By giving file_name in which data is present. Example:- gaussian.read_data_file('numbers.txt')

## Files

It has Binomialdistribution.py, Gaussiandistribution.py, Generaldistibution.py  major classes

Binomialdistribution.py and Gaussiandistribution.py are derived class of Generaldistibution.py

Example :-

from dist_prob_binomial_gaussian import Gaussian       //For Gaussian distribution

from dist_prob_binomial_gaussian import Binomial       //For Binomial distribution

dist_prob_binomial_gaussian --> this the file in which all three classes are present

## Installation

open cmd......

pip install dist_prob_binomial_gaussian

Through this statement package will install.

## THANKS FOR INSTALLING dist_prob_binomial_gaussian
