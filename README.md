# ScanPy Setup and Tutorial

## Prerequisites

- [Python](https://www.python.org/downloads/) or Anaconda
- Download the zip file of this repository and extract it to a folder.
- Code Editor (VS Code, Sublime Text, Atom, etc.). Download VS Code [here](https://code.visualstudio.com/download)
  
## Setup

- Open the folder in the code editor you downloaded.
- Open the terminal in the code editor.
- Paste the commands below in the terminal.
  
```
conda create env
conda activate env
```
or
```
python -m venv env
env/scripts/activate (windows)
source env/bin/activate (mac)
```
Then,

`pip install -r requirements.txt`

Then open `pbmc3k.ipynb` notebook and run the cells.