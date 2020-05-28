# max-collect-parser
Scripts to transform the 2019 Grants Management Readiness Assessment data collected in OMB Max Collect data into tidy datasets.

## Getting Started

### Prerequisites
First, you'll need Python 3.7. We recommend using `pyenv` to get this (as well as other versions of Python).

Then you'll need Jupyter Notebook. You can find directions on how to get that [here](https://jupyter.org/install). They recommend downloading Anaconda to get it, but we suggest using `pip` if you're already using `pyenv` to manage your python versions.

Then you'll want to clone this repo and `cd` in to it:

```bash
git clone https://github.com/GSA/ra-max-collect-parser.git
cd ra-max-collect-parser
```

We use `pipenv` for a virtual environment. You can find instructions on installing that [here](https://pipenv.readthedocs.io/en/latest/install/#installing-pipenv).

Once you've got `pipenv` installed, you can start up the virtual environment using:

```bash
pipenv install
```

Next, activate the Pipenv shell:

```bash
pipenv shell
```

>This will spawn a new shell subprocess, which can be deactivated by using `exit`.

One of the required packages you just installed is `ipykernel`. We use this to create a kernel that uses our virtual enivronment for the Jupyter Notebook:

```bash
ipython kernel install --user --name=ra-max-collect-parser
```

At this point, you can start jupyter with `jupyter notebook`. Then you can open a notebook and select the kernel (ra-max-collect-parser) that you just created.

## Contributing
Please read [CONTRIBUTING.md](https://github.com/GSA/ra-max-collect-parser/blob/master/.github/CONTRIBUTING.MD) for details on our code of conduct, and the process for submitting pull requests to us.

## License
This project is licensed under the Creative Commons Zero v1.0 Universal License - see the [LICENSE.md](https://github.com/GSA/ra-max-collect-parser/blob/master/.github/LICENSE) file for details.
