## Initailize the conda in your Termnial
```pwsh
    conda init
```
Then restart your Terminal (if it didn't work, try restart your computer!)
## Create a conda's environment
```pwsh
    conda create --name your_environment_name python=3.8
```
With 3.8 is the prefix of your specific version of python virtual environment.

## Check exists environments
```pwsh
    conda env list
```
## Activate the existed environment
```pwsh
    conda activate your_env_name
```

## Install a list of dependancies stored in a TXT file
VD: reqs.txt
```text
    numpy
    PILLOW
    opencv-python
    opencv-contrib-python
    opencv-python-headless
```
Using `pip`:
```text
    pip install -r reqs.txt
```
