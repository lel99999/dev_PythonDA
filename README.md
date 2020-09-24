# dev_PythonDA
Python DA with Pandas, Numpy and Matplotlib

#### DA
Data Extraction -> Data Preparation -> Data Exploration & Visualization -> Predictive Modeling -> Model Validation -> Deploy<br/>


#### Predictive Modeling
Classification Models:  Results obtained by model type is categorical<br/>

Regression Models:  Results obtained by model type is numeric<br/>

Clustering Models:  Results obtained by model type is descriptive<br/>

##### Enable the Python collection before the virutal environment

Example for venv:<br/>

```
$ scl enable rh-python36 bash
$ python3.6 -m venv myproject1
$ source myproject1/bin/activate
```

When reactivating later in a new shell:<br/>

```
$ scl enable rh-python36 bash
$ source myproject1/bin/activate
```

Example for virtualenv:<br/>

```
$ scl enable rh-python36 bash
$ python3.6 -m virtualenv myproject1
$ source myproject1/bin/activate
```

When reactivating later in a new shell:<br/>

```
$ scl enable rh-python36 bash
$ source myproject1/bin/activate
```

##### Install Python Packages

- rh-python36-numpy
- rh-python36-scipy
- rh-python36-python-tools
- rh-python-six


##### Save or Freeze Requirements

List all packages and save to requirements file<br/>
```
$pip list
$pip freeze > /<path>/requirements.txt
```

This will create a list containing all the packages in current environment, and their versions.<br/>

To recreate the same environment and install same packages:<br/>
`$pip3 install -r /<path>/requirements.txt`<br/>

