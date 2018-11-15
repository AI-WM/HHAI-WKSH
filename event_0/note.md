# Hyper-Heuristic A.I. Workshop

Note for Event 0 by [Contributors](#Contributors)

## Contents

- [Structured & Unstructured Data](#Structured-&-Unstructured-Data)
- [Variable Type](#Variable-type)
- [Random Forest](#Random-Forest)
- [No Free Lunch Theorem](#No-free-lunch-theorem)
- [Curse of Dimensionality](#Curse-of-Dimensionality)

## Structured & Unstructured Data

- Structured data
    - The data that have been orderly stored in relational database (e.g. MySQL, Oracle)
    - Pros:
        - only need small memory to store data
        - could inquire about the data easily and quickly
- Unstructured data
    - The data that haven’t been cleaned yet, which means the essence of data
    - Examples: the data in web pages, emails, images, video clips.
- Process:
    1. scrap the data (unstructured data) from web pages by web scraping
    2. clean the data and store the data (structured data) in relational database

## Variable Type

- continuous variable
    - A numeric number has an infinite number of possible values
    - Example: Blood Pressure, Height
- categorical variable
    - Take on one of a limited number of possible values
    - Example: Car Model, School

## Random Forest

- What is Random Forest?
    - A supervised machine learning model
    - Works for both classification and regression problems
    - Can predict with both structured and unstructured data
- What is the advantages of RF?
    - Do not need a separate validation set
        - Can use OOB score
    - Few statistical assumptions
        - Does not assume the data is normally distributed
        - Does not assume the relationship is linear
    - Requires very few pieces of feature engineering

## No Free Lunch Theorem

- What is NFL theorem?
    - There’s no single machine learning algorithm to rule all problems
- Does this theory apply?
    - We must consider the previous information in deciding which set of algorithms to train and test and then we select the best
    - If we rank each algorithm for each problem, RF is on top for most problems (Even it is not always the best)

## Curse of Dimensionality

- The more columns you have, it creates a space that is more and more empty
- The more dimensions you have, the more all of the points sit on the edge of that space. If you just have a single dimension where things are random, then they are spread out all over
- Each dimension you add, it becomes multiplicatively less likely that the point is not on the edge of at least one dimension, so in high dimensions, everything sits on the edge. What that means in theory is that the distance between points is much less meaningful
- Quantity of data we need to train models would grow exponentially by the increase of dimensionality
- When the dimensionality increases, the volume of space also increase, in the meanwhile; the data that spread in the space become sparse due to the rapid increase of space volume

## Contributors

*The list is sorted by last name, first name, and nickname.*

- [Haolin Hong](https://github.com/HHONG-WM)
- [Aaron Liu](https://www.linkedin.com/in/en-lung-liu-2000b510b/)
