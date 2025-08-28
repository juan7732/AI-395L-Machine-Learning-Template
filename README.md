# AI 395L Machine Learning

The purpose of this repo is to have an effective local environment that can be source controlled to complete and work on the homework assignments for AI 395L Machine Learning as part of UT's Masters of Aritificial Intelligence Program.

This repo was specifically set up to work best with Visual Studio Code, so usage outside of vscode might be possible, but mileage may vary.

## Set up

### Pre-requisites

Before getting set up, first install `uv`.

<https://docs.astral.sh/uv/getting-started/installation/>

### Running Locally

1. Run `uv python install` to install the required Python version (3.8)
2. Run `uv sync` to sync the project's dependencies
3. Run `uv run jupyter lab` or `uv run jupyter notebook` to launch your preferred jupyter experience.

## Recommended Usage

1. Create the homework folder under `./Homework` to track the homework for that week.

2. Launch your preferred jupyter experience.

## About the Jupyter Environments

The jupyter environment comes with the following dependencies established:

- Python 3.8
- Jupyter
- Scikit-learn
- NumPy
- pandas
- Matplotlib
- seaborn

If you need to add any additional packages, use the `uv add <package>`.

## References

If you are not familiar with how Jupyter works, I recommend this free course to get a basic understanding of Jupyter: <https://www.codecademy.com/learn/getting-started-off-platform-for-data-science>

- [UV](https://docs.astral.sh/uv/getting-started/features/#python-versions)
- [Jupyter](https://jupyter.org/)
- [NumPy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [seaborn](https://seaborn.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [scikit-learn](https://scikit-learn.org/stable/)