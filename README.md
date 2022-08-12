# Triton-NeuroTech-Project-Workshop
## Download Python or Pip
If python not found, download: https://www.python.org/downloads/ <br>
If command pip not found error, start with `python -m ensurepip --upgrade`

## Download required packages

Follow the instructions to download Brainda: https://github.com/TBC-TJU/brainda.git <br>
Follow the instructions to download Meegkit: https://github.com/nbara/python-meegkit  <br>
Download jupyterlab, virtual environment by running `pip install -r requirements.txt`  <br>
Upload ipykernel to jupyterlab by running `pip install ipykernel` then `python -m ipykernel install --user --name=myenv3`

[Video walk through of all installation steps](https://drive.google.com/file/d/1maarUU_fnSiMahSnMYm_gXv6s2a3W26G/view)
## Resources
To uninstall unwanted ipykernel, run `jupyter kernelspec uninstall unwanted-kernel`