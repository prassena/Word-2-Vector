# Word-2-Vector
Creating Word to Vector using DonorsChoose Dataset

In W2V each word is represented with the vector of d dimension.so here we are creating the vector for top 2000 words and we consider the window of 5.
we creat a co-occurrence matrix for top 2000 matrix with a window size of 5 then we do single vector decomposision(SVD) and detemine the size of vector by plotting cumsum of variance stored at each dimension.
We Vectorize the essay text and project titles using these word vectors. (while vectorizing, do ignore all the words which are not in top 2k words) and build model on top of it.
