VISTA: Vehicle Image Sensing for Traffic Automation


Create a new environment called vistagpuenv:
```conda create -n vistagpuenv python=3.8 numpy pandas ipykernel```

Activate the environment:
```conda activate vistagpuenv```

You can also install packages after new environment is created and activated.
```conda install -c ipykernel```

Once you open Jupyter Notebook, make sure `vistagpuenv` is selected as the kernel

Add your environment to Jupyter by creating a new kernel
```python -m ipykernel install --user --name=myenv```
OR
```ipython kernel install --user --name=vistagpuenv```


To uninstall a virtual env:
```jupyter-kernelspec uninstall vistaenv```

To return to the base environment:
```conda deactivate```


To use pip to install packages inside the virtual environment:
```conda create -n venv_name``` (already done)
```conda activate venv_name``` (already done) # venv_name in this case would be vistaenv
```conda install pip```
```/anaconda/envs/venv_name/bin/pip install package_name```
OR
```python -m pip install package_name```  # when your venv is activated, this will directly use the local copy of pip within the environment

If you ever need to terminate job in conda:
Fn + Ctrl + B (on laptop keyboard)
Ctrl + Break/Pause (on Full size keyboard)