# Discrete  Models and TCAV

On this folder, you'll an example where we use TCAV on discrete data. We will be using the sklearn
KDD99 dataset in order to determine if a feature is important to the model in detecting certain types
of attacks. This will:

- Create concept and target datasets from KDD99 and organize them in a TCAV readable structure.
- Create random folders to be used by TCAV for statistical significance testing.
- Train a simple feedforward model to classify different types of network attacks.
- Run TCAV on this model for the concepts and targets we selected.

## Installation

> pip install tcav

### Requirements

See requirements.txt for a list of python dependencies used in testing TCAV.
These will all be installed during pip installation of tcav.


## Running the code

We provide a notebook demonstrating all functionality. Please run

```
jupyter notebook
```
 and open kdd99_discrete_example.ipynb. 
 
## Requirements

-   tensorflow
-   numpy
-   Pillow
-   matplotlib
-   scikit-learn
-   scipy

## Common issues

- Ensure that your virtual environment has all the necessary packages installed
