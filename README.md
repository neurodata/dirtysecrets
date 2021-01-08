# dirtysecrets
dirty secrets of data science


## 0 preliminaries

1. Data Science: The Three Cultures (https://docs.google.com/document/d/12XqXrTDH8jwFkmVb7vGB-KUDIfNmAtftPPtqaMr6DbE/edit?usp=sharing, and reference this: http://www.stat.columbia.edu/~gelman/research/published/gelman_breiman.pdf)
2. data -> data | data -> objects | objects -> understanding
3. graphs > images > vectors
4. hypothesis testing < classification < ranking < regression < density estimation < model selection
5. no free lunch & arbitrary slow convergence theorem
6. bias/variance trade-off
    4. the picture from DGL
    1. MSE
    2. for classification
    3. bias/complexity
6. the desiderata of learning methods (https://bitsandbrains.io/2018/09/24/modeling-desiderata.html)
7. would you look at it (datasaurus, same with graphs, also other gifs)?

## 1 hypothesis testing

1. statistical theory is fundamentally flawed (https://plato.stanford.edu/entries/statistics/)
    1. unresolved problems with classical stats
    2. unresolved problems with bayesian stats (http://www.stat.columbia.edu/~gelman/research/published/holes.pdf)
3. t-test are not what you want (MlqE figure)
4. p-values are fine (p-value paper)
5. pre-registration is good
8. hypothesis testing is estimating mutual information (https://bitsandbrains.io/2018/09/29/categories-of-testing.html)
13. your permutation test makes some assumptions


## 2 estimation

12. you didn't want the mean or variance anway (robust statistics, show generalization error for robust estimators of mean and covariance)
15. high-dimensional statistics is impossible and counterintuitive - you need to embed in a low dimensional space (implicitly or explicitly)
        1. curse of dimensionality
        2. grazing goat
        3. relative volume of sphere and cube
        4. therefore, when p>n, we implicitly or explicitly embed in low dimensions
16. we have no model of vision, audition, or anything but Euclidean
13. estimation vs prediction & necessary vs sufficient & global vs local (mike's paper)
12. all learning is sequential (ali's paper)

## 3 unsupervised learning

5. you didn't estimate the true number of clusters
        1. show histogram that could be 1 or 2 gaussians with different means
        2. show histogram that could be 1 or 2 gaussians with different variances
        3. george and foster paper intuition, with examples showing AIC/BIC/DIC all get different answers
        4. two truths
6. kmeans is secretly gaussian mixture modeling (jk-means paper)
9. you didn't do better than PCA (papadimitrious LSI, eckard young)
10. manifold learning is nonsense (urerf)
11. operating in the lower dimensional space isn't always better (On the Power of Likelihood Ratio Tests in Dimension-Restricted Submodels
)

## 4 supervised learning

6. sparse models don't work (leekasso vs lasso, and https://projecteuclid.org/euclid.aos/1509436830)
7. your deep net is not a universal function approximator, and even if it was, that's not what you wanted anyway (cybenko, hornik, consistency/generalization vs function estimation/interpolation)
16. we have no model of vision, audition, or anything but Euclidean
1. just use random forest (sporf)
1. partition and vote (mml)

## 5 existing stuff doesn't work (https://bitsandbrains.io/2019/11/21/new-method.html)

1. build compelling evidence that existing tools don't work well/easily
2. pseudocode your new plan carefully
3. build compelling evidence that your new thing does work in simulated settings where their thing doesn't work
3. build compelling evidence that your new thing does *not* work in simulated settings where their thing does work
4. build compelling evidence that your new thing is useful *scientifically*
5. FIRM guidelines (https://bitsandbrains.io/2018/10/21/numerical-packages.html)

## 6 communicating data science

1. how to write a paper (https://bitsandbrains.io/2019/02/10/how-to-write-a-paper.html)
1. how to make a figure (https://bitsandbrains.io/2018/09/08/figures.html)
1. how to write a paragraph (https://bitsandbrains.io/2018/10/14/paragraphs.html)
1. words/phrases to avoid (https://bitsandbrains.io/2018/10/14/words.html)
2. how to review a paper
1. how to write a grant (https://bitsandbrains.io/2018/10/14/structuring-a-grant.html)
1. how to make slides (https://bitsandbrains.io/2018/09/04/slides.html)
1. how to choose a project (https://bitsandbrains.io/2018/08/31/sig-and-feas.html)
1. how to get into grad school (https://bitsandbrains.io/2018/10/21/getting-into-grad-school.html)





