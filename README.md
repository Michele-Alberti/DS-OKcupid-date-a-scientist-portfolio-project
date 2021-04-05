# Codecademy Data Science Path: OkCupid - Date a Scientist Portfolio Project
This work is the machine learning portfolio project for *Codecademy Data Scientist path*.

The repository includes the following files:
- **date-a-scientist.ipynb:** *Jupyter Notebook with analysis description, code and models*
- **profiles.zip:** *zip archive containing a CSV file with data used by `date-a-scientist.ipynb`*
- **CC-DSpath39.yml:** *conda environment used for creating the Notebook (some package are not used by this Notebook because this is the environment I used for the whole Codecademy course)*

The CSV file used for this project is zipped because it is larger than *100 MB* when unzipped. Files over this threshold are not accepted in normal pushes to
[<img style="position: relative; bottom: 2px;" src=https://upload.wikimedia.org/wikipedia/commons/thumb/5/54/GitHub_Logo.png/800px-GitHub_Logo.png alt="GitHub" width="60"/>](https://docs.github.com/en/github/managing-large-files/conditions-for-large-files) (for this reason the unzipped file is listed in this repo's *.gitignore*).\
**Remember to unzip `profiles.zip` before running the `date-a-scientist.ipynb` notebook.**

[<img style="position: relative; bottom: 3px;" src="https://docs.conda.io/en/latest/_images/conda_logo.svg" alt="Conda" width="80"/>](https://docs.conda.io/en/latest/) is required for creating the development environment (it is suggested to install [Miniconda](https://docs.conda.io/en/latest/miniconda.html)).

From terminal navigate to the repository base directory.\
Use the command `conda env create -f CC-DSpath39.yml` in your terminal to create the environment named `CC-DSpath39`.\
Activate the environment with `conda activate CC-DSpath39` and then run `jupyter notebook`.
