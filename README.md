# eddy_analysis
Examples of how to run eddy identification and visualisation with py-eddy-tracker on model data. 

ICON EERIE runs used in the examples.

These are my personal notebooks to show some examples, I'll try to upload the nice final notebooks on the EERIE github.



## About the py-eddy-tracke environment

It is a pain to set up a py-eddy-tracker environment that works but it might be worth it.

What worked for me to create a working environment on levante server:

```
conda create -n py39 python=3.9.1
conda activate py39
pip install numpy==1.22.4 #might be overwritten later
pip install netcdf4==1.5.8 #might be overwritten later
pip install matplotlib==3.7.1 #REALLY IMPORTANT
pip install scipy opencv-python pyyaml pint polygon3
pip install pyEddyTracker
```

Then you create a kernel for it

```
source activate py39
pip install ipykernel
python -m ipykernel install --user --name py39 --display-name "py39"
```


To run eddy identification with an intake library (as in EERIE project) you need to use the updated py-eddy-tracer version developed by Aaron Wienkers during the first EERIE hackathon (Nov 2023). Link to the py-eddy-tracker updated version and how to use it - https://github.com/eerie-project/EERIE_hackathon_2023/tree/main/RESULTS/pyeddytracker_xarray_dask_parallel.

For this you also need to install stuff for intake to work, so I do 

```
pip install intake
pip install aiohttp
pip install intake-xarray
pip install intake-esm
```





