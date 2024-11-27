# CMIP-Model-2024-Workshop
This repository comprises notebooks for the  Workshop related to the CMIP6 dataset. 

# Getting Started
The notebooks cover:

- accessing the cmip6 dataset from different data sources.
- plotting key variables from the cmip6 dataset.
- producing climate stripes from the accessed cmip6 dataset.

# Testing the code
You can run the code in these notebooks on your own machine without downloading any of the requirements using binder. Note - the code will be much slower on binder than on your own machine. 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/abhnil/MD_Workshop/main)




# Requirements
Clone this repository into your local directory.
```
git clone https://github.com/abhnil/MD_Workshop.git
cd MD_Workshop
```
Install and activate the virtual environment **cmip6env** to run the notebooks using Python 3.
```
python3 -m venv cmip6env
source cmip6env/bin/activate
```
Install the requirements.txt file 
```
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```

# Running Notebooks
```
cd notebooks
jupyter lab <notebook>
```





