# ECG_classification

The goal is to implement an algorithm that is able to classify ECG waveforms into ve classes of Arrhythmia by taking into account only rhythmic features. 
In order to solve such a task, we will have to extract a precise feature vector and train a classier on the MIT-BIH dataset.

When we deal with machine learning/deep learning algorithms, the rst action is to load, analyze, and preprocess the dataset. 
Typically, such models are built within python scripts, and datasets are downloaded locally. Often, datasets are organized in .csv les freeing us from the burden of downloading GBs
of .wav les. For our ECG classication process, we will consider the MIT-BIH dataset.

Typically, the 80% of the dataset is used for training, while the 20% for testing the model. In our
case, data are already divided into two subsets as we have two distinct les. We will not use the whole
dataset for training our classier because this can easily occupy the whole RAM at disposal to Jupyter
Notebook. Due to this reason, the performance of our classier will probably not be the best possible
but still sucient for the scope of this assignment.
