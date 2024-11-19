

# Linear Regression Example - README.md

## Prerequisites

### 1. Python Installation
Ensure Python is installed on your Mac. If not:
- Visit [Python's official website](https://www.python.org/downloads/)
- Download the latest version for macOS
- Run the installer and follow the prompts

To verify installation, open Terminal and run:
```bash
python --version
```

### 2. Package Manager (pip)
Pip should come with Python installation. Verify with:
```bash
pip --version
```

If not installed:
```bash
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python get-pip.py
```

### 3. Required Packages
Install all necessary packages using Terminal:
```bash
pip install jupyter numpy pandas matplotlib scikit-learn
```

## Installation Verification
Run these commands in Terminal to verify installations:
```bash
python -c "import numpy; print(numpy.__version__)"
python -c "import pandas; print(pandas.__version__)"
python -c "import matplotlib; print(matplotlib.__version__)"
python -c "import sklearn; print(sklearn.__version__)"
```

## Project Setup

1. Create a project directory:
```bash
mkdir machine-learning-with-python
cd machine-learning-with-python
```

2. Launch Jupyter Notebook or VSCode:

### Jupyter Notebook:
```bash
jupyter notebook
```
### VSCode:

* Install Python extension
* Open the project directory in VSCode
* Install Jupyter extension

3. Open the `*.ipynb` files in Jupyter Notebook or VSCode to view the code and results.
## Additional Resources

- [Jupyter Notebook Documentation](https://jupyter.org/documentation)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
