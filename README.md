# Black_Friday
This is work is based on purchase data. The goal is to model customer behavior so that we can predict their purchase amount on a monthly basis.

### Setup
You will need the following python installation: <br>
- Python version = 3.5.4
- Pandas version = 0.20.3
- NumPy version = 1.13.1
- Matplotlib version = 2.0.2
- sci-kit learn version = 0.19.0
- SciPy version = 0.19.1

It is recomended to have Python 3 installed. Not sure if this code will break with Python 2.x

### Create a virtual environment (Optional but recommended)
It is common practice to keep your current Root Python environment clean and create a new environment for a new study/project.

#### Using Anaconda
If you have the Anaconda distribution of **Python 3** installed, then run the commands below in your OS console:

- `\usr> conda env create -f environment.yml`
- `\usr> source activate blackfriday`<br>
  or
- `\usr> activate blackfriday` on Windows

#### Using pip and virtualenv
- From your console:
    - `\usr> (sudo) pip install virtualenv`
    - `\usr> virtualenv -p python3 blackfriday`
    - `\usr> source blackfriday/bin/activate`
- `\usr> pip install -r requirements.txt`


### Jupyter Notebook users
If you want to use Jupyter, no need to add jupyter (core,client,...) to your newly created environment. You can simply add a new environment to your current Jupyter notebook as explained [here](https://stackoverflow.com/questions/39604271/conda-environments-not-showing-up-in-jupyter-notebook#44786736):<br>

`\usr> python -m ipykernel install --user --name blackfriday --display-name "What_you_see_in_jupyter"`

Once you start your Jupyter Notebook, look at your menu bar and under kernel->change kernel you will see all of your added environment including  "What_you_see_in_jupyter"
