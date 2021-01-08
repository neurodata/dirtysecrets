# dirtysecrets
dirty secrets of data science


## 0 preliminaries

1. Data Science: The Three Cultures (http://www.stat.columbia.edu/~gelman/research/published/gelman_breiman.pdf)
2. data -> data | data -> objects | objects -> understanding
3. graphs > images > vectors
4. hypothesis testing < classification < ranking < regression < density estimation < model selection
5. no free lunch doesn't mean that, but arbitrary slow convergence theorem does

## 1 hypothesis testing

1. statistical theory is fundamentally flawed (https://plato.stanford.edu/entries/statistics/)
    1. unresolved problems with classical stats
    2. unresolved problems with bayesian stats (http://www.stat.columbia.edu/~gelman/research/published/holes.pdf)
3. t-test are not what you want
4. p-values are fine
5. pre-registration is good
8. hypothesis testing is estimating mutual information
13. your permutation test makes some assumptions


## 2 estimation

12. you didn't want the mean or variance anway (robust statistics, show generalization error vs robust statistics)
15. high-dimensional statistics is impossible - you need to embed in a low dimensional space (implicitly or explicitly)
16. we have no model of vision, audition, or anything but Euclidean
13. estimation vs prediction & necessary vs sufficient & global vs local
12. all learning is sequential

## 3 unsupervised learning

5. you didn't estimate the true number of clusters
6. kmeans is secretly gaussian mixture modeling
9. you didn't do better than PCA
10. manifold learning is nonsense
11. operating in the lower dimensional space isn't always better

## 4 supervised learning

6. sparse models don't work
7. your deep net is not a universal function approximator, and even if it was, that's not what you wanted anyway
16. we have no model of vision, audition, or anything but Euclidean
1. just use random forest

## 5 existing stuff doesn't work (https://bitsandbrains.io/2019/11/21/new-method.html)

6. the desiderata of learning methods (https://bitsandbrains.io/2018/09/24/modeling-desiderata.html)
1. build compelling evidence that existing tools don't work well/easily
2. pseudocode your new plan carefully
3. build compelling evidence that your new thing does work in simulated settings where their thing doesn't work
3. build compelling evidence that your new thing does *not* work in simulated settings where their thing does work
4. build compelling evidence that your new thing is useful *scientifically*
5. FIRM guidelines (https://bitsandbrains.io/2018/10/21/numerical-packages.html)

## 6 communicating data science

1. how to write a paper
1. how to make a figure
1. how to write a paragraph
1. words/phrases to avoid
2. how to review a paper
1. how to make slides
1. how to choose a project





