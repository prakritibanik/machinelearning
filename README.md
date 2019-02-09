# 100 Days of Machine Learning
Various machine learning related codes for my 100 days of machine learning project.

The installations needed for all the upcoming projects. This I learnt from my Udacity Self Driving Car course. 

Learn editing markdown file [here](https://guides.github.com/features/mastering-markdown/)

## Preparing system for projects

1. Install [miniconda](https://conda.io/en/master/miniconda.html)
2. Create a new `conda` [environment](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)
3. [Activate the environment](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#activating-an-environment) before staring your work

You can also create a `conda env ml_100` by copying the environment.yml from this repo and running

```
conda env create -f environment.yml
```

This will install all necessary packages. To see a list of all of your environments

```
conda env list
```

After  installing cleanup downloaded files using

```
conda clean -tp
```

To activate `ml_100`

```
source activate ml_100
```

To deactivate an `env`

```
source deactivate
```

To delete an `env`

```
conda env remove -n ml_100
```

Hopefully all went well. So after activating the env start the Jupyter notebook in the background

```
jupyter notebook&
```

It will open the ipynb notebook in the browser. You are all set to start coding.

### Week 1 (not neccessarily in order)
1. Deep Learning by Udacity
2. [Computer Vision Class by Devi Parikh](https://samyak-268.github.io/F18CS4476/)
3. Computer Vision by Udacity

Good Reads:
1. [Hyperparameters and model validation](https://jakevdp.github.io/PythonDataScienceHandbook/05.03-hyperparameters-and-model-validation.html)
2. [Receptive field arithmetic for CNN](https://medium.com/mlreview/a-guide-to-receptive-field-arithmetic-for-convolutional-neural-networks-e0f514068807)
3. [How to handle imbalanced classification problem](https://www.analyticsvidhya.com/blog/2017/03/imbalanced-classification-problem/) and [this](https://machinelearningmastery.com/tactics-to-combat-imbalanced-classes-in-your-machine-learning-dataset/)
4. [Interesting questions for Data Science](https://www.hergertarian.com/rocking-data-science-interviews)
