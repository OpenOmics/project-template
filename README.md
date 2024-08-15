<div align="center">
   
  <h1>IC-123 🔬</h1>
  
  **_Data and script for processing IC-123_**

</div>

# Overview

This repository contains data and scripts for analyzing IC-123. 

Any data accompanying this project can be stored in the `data/` directory, while any scripts used to process the data can be stored in the `scripts/` directory.

> [!NOTE]  
> _**By default**, any data or files added to the `data/` directory are ignored by git due to our `.gitignore`, so you can store large files or data here without worrying about them being uploaded to Github._ If you would to upload a small data file (<5MB) to Github, you can stage the file using force, `-f`, option to the `git add`:  
> ```bash
> # Stage file for commit
> git add -f data/counts.tsv
> # Commit the file to history
> git commit -m "Adding small counts matrix"
> ```

<!--
Please add some more information about the project here. This can be copied directly from the project description. Also please update any references to IC-123 to the correct project identifer. For example: NCBR-123, NHLBI-123, NIAMS-123, etc. 

The easiest way to do this is with sed or find/replace in your text editor. Please feel free to also delete or keep any in this file. This is just a template to get you started, and you can modify it as needed. At the end of the day, this is your project and you can structure it however you like!

```bash
# On biowulf/helix,
# Example sed commnad on linux,
# this can be run on Biowulf
sed -i 's/IC-123/NCBR-123/g' README.md

# On local laptop,
# Example sed on macOSX,
# this can be run on your local machine
sed -i '' 's/IC-123/NCBR-123/g' README.md
```
-->

## Installation

To install the repository locally, you can use the following command:

```bash
# Clone the github repository
# and change your working directory
git clone https://github.com/OpenOmics/IC-123.git
cd IC-123/
```

## Setup your environment

To setup your environment and download any missing packages, you can use the following command:

```bash
# Install any missing or 
# required python packages
# in a virtual environment
python -m venv .venv
source .venv/bin/activate
pip install -U pip
pip install -r requirements.txt

# Install any missing R packages
./packages.R
```

<!--
## Reproduce the analyses

This is where you can add any steps to reproduce the analyses. For example, you can add the following command to run the script:

```bash
# Add any steps here to 
# reproduce the analyses
./scripts/deg.R -i data/counts.tsv -s data/sample_sheet.tsv -o results/
./scripts/heatmap.py -i results/deg.tsv --fc 2 --fdr 0.05 -o results/figures/
```
-->
