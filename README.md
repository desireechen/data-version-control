# Data Version Control

This master branch is the forked repository based on the [Data Version Control With Python and DVC](https://realpython.com/python-data-version-control/) article in [Real Python](https://realpython.com/). I had referred to this article for my study of how Data Version Control (DVC) can be used to version both data and model.

I am using [Imagenette](https://github.com/fastai/imagenette) dataset from [fastai](https://www.fast.ai/).

In the various branches, I have conducted several experiments. 

Branch: first_experiment
Experiment: SGD Classifier trained on 10 iterations
Accuracy: 66%

Branch: sgd_100_iterations
Experiment: SGD Classifier trained on 100 iterations
Accuracy: 76%

Branch: sgd_pipeline
Experiment: SGD Classifier trained on 100 iterations and ran as a DVC pipeline
TODO: Advantages of DVC pipeline
Accuracy: 79% (There is randomness in the training, hence the accuracy differs from the above experiment)

Branch: random_forest
Experiment: Random Forest Classifier ran as a DVC pipeline
Accuracy: 81%

Please refer to the respective README under each branch for further details of the experiments.
