# dvc-test
Working through the data version control (dvc) tutorial.

## Setup (with Python)
### Set up and install DVC
1. Create new virtual environment to install and test dvc.
```
conda create --prefix ./dvc_env python=3.8
```
2. Activate the new environment
```
conda actiavte ./dvc_env
```
3. Install dvc as a python library
```
conda install -c conda-forge dvc
```
4. Initialize DVC repository
```
dvc init
``` 
5. Commit the ```.dvc``` folder and its contents to Git.

```
git add .
git commit -m "Initialize DVC"
```

### Data Versioning
