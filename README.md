# Web Mapping with PyScript - October 18, 2023

[Presentation Slides](https://docs.google.com/presentation/d/121dD56Mb2qiANhA5GlP6MNLDFcrxLXxVDoXXnBh51nE/edit?usp=sharing)

### Data Sources

* [Washington State Hikes](https://github.com/yoshiohasegawa/wta-scraper)


### To run the code in the PyScript files

* Simply open them in a modern browser with an internet connection.


### Run code from pyscript.com

* https://cheaton.pyscriptapps.com/5-random-hikes-in-washington-state/latest/

### To run the code in the Jupyter Notebooks

* If you are familiar with [GitHub](http://www.github.com), fork (if you wish) and clone this repository. If not, download the repository and unzip to a working directory. Take note of where you put it!

* Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) for your operating system. Please choose the latest Python 3.x version.

* You should now have access to an Anaconda command prompt, open it like you would any program. Note that you should see `(base)` somewhere in your prompt. This means you're in the base Conda environment, which we will now change. 

Navigate to the directory containing environment.yml (included in the repo).

```bash
cd [location where the repo is saved]/webmapping_with_pyscript
```

* Create the Conda environment needed to run the notebooks. Note: it is called `geopandasenv`. **This could take anywhere from 10-30 minutes to finish.**

```bash
conda env create -f environment.yml
```

* Activate the environment.

```bash
source activate geopandasenv  # macOS and Linux
activate geopandasenv  # Windows.
```

* To open the Jupyter Notebooks included in this tutorial, in the Anaconda prompt navigated to the Notebook directory, type in:

```bash
jupyter notebook
```

This will open a browser where you can click and open each Notebook.

* To deactivate the geopandasenv environment, type the following in the Anaconda prompt:

```bash
source deactivate  # macOS and Linux
deactivate  # Windows.
```
