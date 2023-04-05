# students

I downloaded a dataset on high school students taking math classes in Portugal from here:
P. Cortez and A. Silva. Using Data Mining to Predict Secondary School Student Performance. In A. Brito and J. Teixeira Eds., Proceedings of 5th FUture BUsiness TEChnology Conference (FUBUTEC 2008) pp. 5-12, Porto, Portugal, April, 2008, EUROSIS, ISBN 978-9077381-39-7.

I "tidied" it and then took some liberties with the dataset to make it a little more conducive to teaching the tidyverse. In particular, I wanted there to be continuous-type numeric variables to explore what ggplot2 can do with those types, so I took grade1, grade2, and final_grade and made them out of a 100-point scale instead of Portugal's 1-20, and then I added some random noise with rnorm(sd = 1).
