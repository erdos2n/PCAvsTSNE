# PCAvsTSNE
I compared PCA and TSNE in a sequential neural net to see which dimensionality reduction algorithm would produce better results.  


Without dimensionality reduction:
* evaluation score = 0.66
* PCA score        = 0.77
* TSNE score       = 0.70
---------------------------------

Looking at the **table below** there is already a baseline of predicting 65% zeros, so the real

question is whether or not this can predict a one (diabetic).  Further analysis needs to be done 

to answer this question and I plan on running a random forest classifier to see if it produces better

results.


   |  1   |  0  |  Total
    ------ ----- -------
y  |  268 | 500 |  768

%  |  35% |  65% | 100%

