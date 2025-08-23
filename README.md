# Jupyter Notebook Open Data Analyses
This repository contains analyses of various open data sources that I found interesting to analyze using Jupyter Notebooks.

---

These analyses have been developed in a local environment using Microsoft plugins for Jupyter Notebook and Python in Visual Studio Code. To work with them, simply meet the following requirements:

- Have Python 3 installed on your computer

- Initialize a virtual Python environment for your work environment

``` bash
# macOS / Linux
# You may need to run 'sudo apt-get install python3-venv' first on Debian-based OSs
python3 -m venv .venv
# Windows
python -m venv .venv
```

- Activate the virtual environment and install dependencies

``` bash
# macOS / Linux
source .venv/bin/activate
# For Windows with CMD.
.\venv\Scripts\activate.bat
# For Windows with Power shell.
.\venv\Scripts\activate.ps1
 #For Windows with Unix like shells for example Git Bash CLI.
 source venv/Scripts/activate

# Install dependencies
pip install -r requirements.txt
```

- Deactivate the virtual environment when finished
``` bash
# macOS / Linux
deactivate
# Windows
scripts\deactivate
```