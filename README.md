

Built on X-DeepLearning, XRec aims to provides industrial recommendation solutions with elegant design and implementation.

## Package Overview
| **xrec** | an Python library for recommender system |
| --- | --- |
| **xrec.commands** | functionality for a CLI and web service |
| **xrec.data** | a data processing module for loading and encoding datasets for representation |
| **xrec.models** | a collection of state-of-the-art models |
| **xrec.modules** | a collection of PyTorch modules for use with recommender system |
| **xrec.nn** | tensor utility functions, such as initializers and activation functions |
| **xrec.service** | a web server to that can serve demos for your models |
| **xrec.training** | functionality for training models |


## Installation

xrec requires Python 3.7.1 or later. The preferred way to install xrec is via `pip`.  Just run `pip install xrec` in your Python environment and you're good to go!

If you need pointers on setting up an appropriate Python environment or would like to install xrec using a different method, see below.

Windows is currently not officially supported, although we try to fix issues when they are easily addressed.

### Installing via pip

#### Setting up a virtual environment

[Conda](https://conda.io/) can be used set up a virtual environment with the
version of Python required for xrec.  If you already have a Python 3.7 or 3.7
environment you want to use, you can skip to the 'installing via pip' section.

1.  [Download and install Conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html).

2.  Create a Conda environment with Python 3.7

    ```bash
    conda create -n xrec python=3.7
    ```

3.  Activate the Conda environment. You will need to activate the Conda environment in each terminal in which you want to use xrec.

    ```bash
    source activate xrec
    ```

#### Installing the library and dependencies

Installing the library and dependencies is simple using `pip`.

   ```bash
   pip install xrec
   ```

That's it! You're now ready to build and train xrec models.
xrec installs a script when you install the python package, meaning you can run xrec commands just by typing `xrec` into a terminal.

You can now test your installation with `xrec test-install`.

_`pip` currently installs Pytorch for CUDA 9 only (or no GPU). If you require an older version,
please visit https://pytorch.org/ and install the relevant pytorch binary._

## Features

- Pythonic
- Easy to use
- State-of-the-art


## Models

Please refer to the documents

### User Behavior Data from Taobao

| Model | MAP | nDCG@k | Precision@k | Recall@k | RMSE | MAE | R<sup>2</sup> | Auc | Explained Variance | 
| --- | --- | --- | --- | --- | --- | --- | --- | --- |--- | 
| TDM |   |   |   |   |  |    |   | 0.800158 |   | 





## Issues
Everyone is welcome to file issues with either feature requests, bug reports, or general questions. As a small team with only one person, we may ask for contributions if a prompt fix doesn't fit into our roadmap. We allow users a two week window to follow up on questions, after which we will close issues. They can be re-opened if there is further discussion.

## Contributions
If you would like to contribute a larger feature, we recommend first creating an issue with a proposed design for discussion. This will prevent you from spending significant time on an implementation which has a technical limitation someone could have pointed out early on. Small contributions can be made directly in a pull request.

Pull requests (PRs) must have one approving review and no requested changes before they are merged. 

## Licence
Apache 2.0 

