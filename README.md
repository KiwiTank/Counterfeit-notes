# Counterfeit note identification using k-means
This was a project I completed from the University of London to identify counterfeit notes using k-means using the data supplied in *Banknote_authentication_dataset.csv*. This file contains v1 and v2 values derived from preprocessed computer vision evaluation of the notes, but importantly does not contain any labels, all of which are stored in *Banknote_original_data.csv*.
### Bank Note Authentication project.ipynb
The unlabeled data is first evaluated statistically, and then used to train the k-means clustering model using *k=2*. The results are compared with the original labelled data, giving a rather modest 65% accuracy. Not bad for only two variables. 
