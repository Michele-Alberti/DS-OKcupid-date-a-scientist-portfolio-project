# Codecademy Data Science Path: OkCupid - Date a Scientist Portfolio Project
This work is the machine learning portfolio project for *Codecademy Data Scientist path*.

### Files

The repository includes the following files:
- **date-a-scientist.ipynb:** *Jupyter Notebook with analysis description, code and models*
- **profiles.zip:** *zip archive containing a CSV file with data used by `date-a-scientist.ipynb`*
- **CC-DSpath39.yml:** *conda environment used for creating the Notebook (some package are not used by this Notebook because this is the environment I used for the whole Codecademy course)*

### Dataset

The CSV file used for this project is zipped because it is larger than *100 MB* when unzipped. Files over this threshold are not accepted in normal pushes to
[<img style="position: relative; bottom: 2px;" src=https://upload.wikimedia.org/wikipedia/commons/thumb/5/54/GitHub_Logo.png/800px-GitHub_Logo.png alt="GitHub" width="60"/>](https://docs.github.com/en/github/managing-large-files/conditions-for-large-files) (for this reason the unzipped file is listed in this repo's *.gitignore*).\
**Remember to unzip `profiles.zip` before running the `date-a-scientist.ipynb` notebook.**

### Install Conda

[<img style="position: relative; bottom: 3px;" src="https://docs.conda.io/en/latest/_images/conda_logo.svg" alt="Conda" width="80"/>](https://docs.conda.io/en/latest/) is required for creating the development environment (it is suggested to install [Miniconda](https://docs.conda.io/en/latest/miniconda.html)).

From terminal navigate to the repository base directory.\
Use the following command in your terminal to create an environment named `CC-DSpath39`.
```
conda env create -f CC-DSpath39.yml
```

### Install Spacy Model
The `date-a-scientist.ipynb` notebook uses *Spacy* for natural language processing.\
*Spacy's* models are not pre-installed, they have to be downloaded.\
We are interested in `en_core_web_sm`, a small model for NPL.\
Open the terminal and activate `CC-DSpath39`, the new environment.
```
conda activate CC-DSpath39
```
Then run the following command to install `en_core_web_sm`:
```
python -m spacy download en_core_web_s
```
Finally you can open `jupyiter notebook`
```
jupyter notebook
```
and load `date-a-scientist.ipynb` from the graphic interface.
