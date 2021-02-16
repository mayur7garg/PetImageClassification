# Pet Image Classification

### Image classification using CNN in tf.keras for Oxford IIIT Pet image dataset.

#### Dataset
The dataset for this project can be downloaded from any of the following links:
* [Visual Geometry Group - University of Oxford](https://www.robots.ox.ac.uk/~vgg/data/pets/)
* [Kaggle](https://www.kaggle.com/tanlikesmath/the-oxfordiiit-pet-dataset)

This dataset consists of 7390 images of pets spanning 37 classes with about 200 images per class. The images vary vastly in size, aspect ratio, pose, lightning, etc.

#### Project Requirements
The external libraries required for running _**Train.ipynb**_ are:
1. numpy
2. matplotlib
3. sklearn/scikit-learn
4. tensorflow (Version 2.3.0 preferred)
5. tqdm

**NOTE:** The model and tensorboard directories have been removed from the project due to GitHub's individual file size constraints. Kindly run _**Train.ipynb**_ to generate the model and the tensorboard logs.

After running _**Train.ipynb**_, use the command _**tensorboard --logdir tensorboard_logs/fit**_ using the command line from the project's root directory to open the TensorBoard GUI in your browser.

> Make sure to update the _**BASE_PATH**_ constant in _**Train.ipynb**_ to reflect the location where your dataset is stored.

> Developed by - Mayur Garg
