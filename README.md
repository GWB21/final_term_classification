# final_term_classification

This project shows the classification of the Olivetti dataset through classification algorithm.
___________________________________________________________________________________________________________________________________________

Olivetti dataset contains a "set of face images" taken between April 1992 and April 1994 at AT&T Laboratories Cambridge.

There are ten different images of each of 40 distinct subjects. For some
    subjects, the images were taken at different times, varying the lighting,
    facial expressions (open / closed eyes, smiling / not smiling) and facial
    details (glasses / no glasses). All the images were taken against a dark
    homogeneous background with the subjects in an upright, frontal position 
    (with tolerance for some side movement).

**Data Set Characteristics:**

    =================   =====================
    Classes                                40
    Samples total                         400
    Dimensionality                       4096
    Features            real, between 0 and 1
    =================   =====================
    
If you want for more information about Olivetti dataset, go to this website https://scikit-learn.org/0.19/datasets/olivetti_faces.html
    
______________________________________________________________________________________________________________________________________________

I chose Logistic Regression for classification algorithm.
Because Logistic regression is efficient and does not require a huge amount of computational resources.
It's easy to interpret and doesn't require extended input capabilities. It's easy to normalize, and it gives a well-adjusted predicted probability.
_______________________________________________________________________________________________________________________________________________

First I chose 'liblinear' instead of 'lbfgs'.
Because liblinear is much better algorithm for small data than default solver 'lbfgs'.
  
Second I defined 'C = 20'.
The larger the value of C, the less normalization and the higher the possibility of overfitting.
I tried several times to get most accurate model, and the optimum value of C was larger than 15.
  
Thrid I defined 'random_state = 0' to prevent accuracy fluctuation.






