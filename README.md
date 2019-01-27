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
source activate
```

To deactivate an `env`

```
source deactivate ml_100
```

To delete an `env`

```
conda env remove -n ml_100
```

Hopefully all went well. So after activating the env start the Jupyter notebook

```
jupyter notebook
```

It will open the ipynb notebook in the browser. You are all set to start coding.