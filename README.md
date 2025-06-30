# 10 TeV Wakefield Collider Design Study Website

This repository contains the documentation website for the 10 TeV Wakefield Collider Design Study, built using MkDocs with the Material theme.

## Local Development Setup

### Install Conda (if not already installed)

If you don't have Conda installed, you can download it from the [official website](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

### Create and Activate the Conda Environment

```bash
# Create the environment from the environment.yml file
conda env create -f environment.yml

# Activate the environment
conda activate 10tev-docs
```
Note that you have to create the file 'environment.yml' and copy it from [here]([url](https://github.com/10TeV-wakefield-collider/10TeV-wakefield-collider.github.io/blob/main/environment.yml)) first.

### Clone this repository to your local computer

```bash
git clone https://github.com/10TeV-wakefield-collider/10TeV-wakefield-collider.github.io.git
```

### Run the Development Server

```bash
# Start the MkDocs development server
cd 10TeV-wakefield-collider.github.io
mkdocs serve
```

Once the server is running, open your web browser and navigate to:
```
http://127.0.0.1:8000
```

The site will automatically reload whenever you make changes to the documentation.

## Adding Content

1. Add new markdown files to the `docs/` directory
2. Update the navigation in `mkdocs.yml` to include the new pages
3. The site will automatically update when you save changes
