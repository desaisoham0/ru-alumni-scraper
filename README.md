# Project Setup Guide

## Instructions

### Step 1: Fork and Clone

1. Fork this repository. 
2. Clone your forked repository to your codespace or local machine:

```bash
git clone <your_forked_repo_url>
cd <your_repo_name>
```

### Step 2: Set Up Environment
1. Make sure you have Docker installed.


### Step 3: Install Dependencies
1. Run this command to install dependencies:
```bash
pip install -r requirements.txt
```

### Step 4: Generate CSV
1. Run the Python script to generate the CSV file if not generated:

```bash
python generateCSV.py
```

### Step 5: Execute Main Script

1. Run the main development script:

```bash
python py_ml_development.py
```

2. This script searches LinkedIn profiles and saves results to `linkedin_titles.csv`.

## Files Overview

1. `generateCSV.py`: Generates CSV data for processing.
2. `py_ml_development.py`: Main script for LinkedIn scraping.
3. `.devcontainer`: Docker setup for Chrome browser usage.

## Output

1. Results will be saved to:
* `names_with_university.csv`
* `linkedin_titles.csv`