# Click Prediction
Predicting clicks and conversions

## Getting started
Clone the repo

```
git clone 
```

It is recommended to use virtual environment for python applications. Create your environment 

```
virtualenv -p python3 .venv
source .venv/bin/activate
```

To use this environment with the Jupyter notebook we need to create a kernel which will contain all the requirements.

```
pip install ipykernel
ipython kernel install --user --name=click-prediction
```

Then the requirements are installed the typical way:

```pip3 install -r  requirements.txt```

After the kernel is ready, it can be selected in your Jupyter notebook from the menu Kernel -> Change Kernel.

Start jupyter

```
jupyter notebook
```

Open the notebook `click_prediction.ipynb`. This notebook and the data `campaigns.csv` need to be in the same folder.
