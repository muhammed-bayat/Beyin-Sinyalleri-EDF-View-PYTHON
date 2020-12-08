##MNE COLAB

first ->  ``` !pip install mne```

 ``` from google.colab import drive  ```
 
```google drive files import```
 
 
```drive.mount('/gdrive')```

```cd /gdrive/MyDrive/Colab\ Notebooks/sinyaller/beyza.edf```


```fname="beyza.edf"```


```raw=mne.io.read_raw_edf(fname)```


```dir(raw)```




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



### If you see an error like:

```  Traceback (most recent call last):
  File "<string>", line 1, in <module>
ModuleNotFoundError: No module named 'mne' ```  
``` 
This suggests that your environment containing MNE-Python is not active. If you followed the setup for 3D plotting/source analysis (i.e., you installed to a new mne environment instead of the base environment) try running conda activate mne first, and try again. If this works, you might want to set your terminal to automatically activate the mne environment each time you open a terminal:  

 ```  echo conda activate mne >> ~/.bashrc    # for bash shells``` 

 ``` echo conda activate mne >> ~/.zprofile  # for zsh shells``` 
## Contributors ✨

 
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://www.xraph.com"><img src="http://0.gravatar.com/avatar/1f6fa769cc76deaeb7f76b39ee1a310a" width="100px;" alt="Muhammed Bayat"/><br /><sub><b>Muhammed Bayat</b></sub></a><br /><a href="https://github.com/muhammed-bayat" title="Code">💻</a> 
  >
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

 Contributions of any kind welcome!
