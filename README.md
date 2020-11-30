# mneTest
## MNE-Python

```sh
$ conda --version && python --version
conda 4.9.2
Python 3.8.5 :: Anaconda, Inc.
$  which python
/home/user/anaconda3/bin/python
 $ which pip
/home/user/anaconda3/bin/pip
```

## LINUX 
```
$ curl --remote-name https://raw.githubusercontent.com/mne-tools/mne-python/master/environment.yml
$ conda env update --file environment.yml
```

#### To activate this environment, use

#####  $  ```conda activate mne```

#### To deactivate an active environment, use

#####   $ ```conda deactivate```


## WINDOWS
Download the environment [file](https://raw.githubusercontent.com/mne-tools/mne-python/master/environment.yml)

Open an Anaconda command prompt

Run ```conda install --name base nb_conda_kernels```

cd to the directory where you downloaded the file

Run ``` 
conda env update --file environment.yml```
