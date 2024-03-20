# Experimental
Base repository for basic experimental deep learning code and student projects

## Getting started
1. Clone this repository to a local directory:
```bash
git clone https://github.com/martindyrba/Experimental
cd Experimental
```
2. Create a conda environment with the given Python version, activate the new environment, and install the required packages listed in requirements.txt:
```bash
conda create -n tf2.15 python==3.11
conda activate tf2.15
pip install -r requirements.txt
```
3. Workaround for errors with current innvestigate==2.1.2 and tensorflow==2.14 is to manually upgrade tensorflow to 2.15:
```bash
pip install tensorflow[and-cuda]==2.15.1
```

4. Use Visual Studio Code to edit and run Jupyter notebook files (recommended). If you instead want to use plain Jupyter, make sure to install the 'nb_conda_kernel' package in your conda 'base' environment once: `pip install nb_conda_kernels`

5. In Visual Studio Code, you can initally proceed as follows:
  1. Go to the menu "File" -> "Open Folder...", and select the "Experimental" folder
  2. When you open a Jupyter notebook file for the first time, you have to specify in which Python environment the Kernel should be executed. 
Therefore, go to the top right corner and click on "Select Kernel". There, choose "tf2.15" from the list or click on "Select Another Kernel..." -> "Python Evironments..."
