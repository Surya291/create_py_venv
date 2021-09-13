# create_py_venv
Set of instructions to create a venv while starting a new project everytime.

## Create Virtual Environment for Python 

Step 01 : You can verify that Python 3 is installed on your system by running
```
$ python3 -V
```

Step 02 :  Starting from Python 3.6, the recommended way to create a virtual environment is to use the venv module. Let's install the python3-venv package that provides the venv module . 

```
$ sudo apt install python3-venv
```

Step 03 : Switch to the directory where you would like to store your Python 3 virtual environments. Within the directory run the following command to create your new virtual environment

```
$ python3 -m venv my-project-env
```
The command above creates a directory called my-project-env, which contains a copy of the Python binary, the Pip package manager, the standard Python library and other supporting files.

Step04 :  To activate the venv , need to run the activate script .
```
$ source my-project-env/bin/activate
```

Step05 : To Deactivate 
```
(venv) $ deactivate
```

