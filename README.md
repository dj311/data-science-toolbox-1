# Data Science Toolbox: Assignment 1

## Research
A summmary/working document of research can be found in [./research.md](./research.md).

## Python Setup
Requires a working Python 3 installation (tested with 3.6.5). Given that, the following steps will setup a virtual environment with all the right bits:
  1. Create a new virtual env:`python3 -m venv python-env` (use `./python-env` since it's included in `.gitignore`).
  2. Activate it in your current shell: `source ./python-env/bin/activate`.
  3. Install the dependencies: `python3 -m pip install -r requirements.txt`.
  4. Activate `nbstripout` to automatically strip output from jupyter notebooks when committing: `nbstripout --install`.


## Data Sources and Licensing
The following files were sourced from Mike Sconzo at [SecRepo](https://secrepo.com) under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/):
  - [./resources/Zeus.csv](./resources/Zeus.csv)
  - [./resources/OPCleaver.csv](./resources/OPCleaver.csv)
  - [./resources/VirusShare.csv](./resources/VirusShare.csv)
