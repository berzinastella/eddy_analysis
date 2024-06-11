# eddy_analysis
Examples of how to run eddy identification and visualisation with py-eddy-tracker on model data. 

ICON eerie runs used in the examples.

These are my personal notebooks to show some examples, I'll try to upload the nice final notebooks on the EERIE github.



## About the py-eddy-tracke environment

It is a pain to set up a py-eddy-tracker environment that works but it might be worth it.

What worked for me to create a working environment on levante server:

```
conda create -n py39 python=3.9.1
conda activate py39
pip install numpy==1.22.4
pip install netcdf4==1.5.8
pip install matplotlib==3.7.1
pip install scipy opencv-python pyyaml pint polygon3
pip install pyEddyTracker
![image](https://github.com/berzinastella/eddy_analysis/assets/75606575/af93316b-180b-40a1-9b73-06d59edf3715)

```


