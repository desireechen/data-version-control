# Data Version Control

This master branch is the forked repository based on the [Data Version Control With Python and DVC](https://realpython.com/python-data-version-control/) article in [Real Python](https://realpython.com/). I had referred to this article for my study of how Data Version Control (DVC) can be used to version both data and model.

I am using [Imagenette](https://github.com/fastai/imagenette) dataset from [fastai](https://www.fast.ai/).

In the various branches, I have conducted several experiments. 

Branch: first_experiment <br>
Experiment: SGD Classifier trained on 10 iterations <br>
Accuracy: 62% <br>

Branch: sgd_100_iterations <br>
Experiment: SGD Classifier trained on 100 iterations <br>
Accuracy: 76% <br>

Branch: sgd_pipeline <br>
Experiment: SGD Classifier trained on 100 iterations and ran as a DVC pipeline <br>
Accuracy: 76% (same as above, as I had defined a random_state) <br>

Branch: random_forest <br>
Experiment: Random Forest Classifier ran as a DVC pipeline <br>
Accuracy: 80% <br>

Please refer to the respective README under each branch for further details of the experiments.

TODO: Advantages of DVC pipeline
