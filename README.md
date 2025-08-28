# AI 395L Machine Learning

The purpose of this repo is to have an effective local environment that can be source controlled to complete and work on the homework assignments for AI 395L Machine Learning as part of UT's Masters of Aritificial Intelligence Program.

## Set up

1.To get set up, first install `uv`

<https://docs.astral.sh/uv/getting-started/installation/>

2. Run `uv python install` to install the required Python version (3.8)
3. Run `uv sync` to sync the project's dependencies
4. Run `uv run jupyter lab` or `uv run jupyter notebook` to launch your preferred jupyter experience.


## About the Jupyter Environments

The jupyter environment comes with the following dependencies established:

- Python 3.8
- Jupyter
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

If you need to add any additional packages, use the `uv add <package>`.

## References

- [UV Reference](https://docs.astral.sh/uv/getting-started/features/#python-versions)