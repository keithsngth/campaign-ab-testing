# Marketing Campaign A/B Testing

## Overview

Businesses often launch campaigns after modifying existing strategies, websites, or platforms to better target consumers, with the aim of increasing sales or other key metrics. To assess the effectiveness of these campaigns, A/B testing is commonly employed. This method involves comparing two versions to determine which whichever yields better results, enabling companies to make informed, data-driven decisions that support long-term growth.

At its core, an A/B test compares the means of two or more groups to identify which group has a higher or lower average outcome, depending on the context, using methods such as t-tests or ANOVA.

Here, we utilise basic statistical tests to investigate the application of A/B testing in marketing campaigns designed to enhance e-commerce through a website. Specifically, we will determine whether the launch of a new campaign has resulted in increased product views on the company website and, consequently, higher sales revenue.

## Getting Started
### Pre-requisites
First, install uv executing the command below in your terminal, if it isn’t already installed.
```bash
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex" # Windows
curl -LsSf https://astral.sh/uv/install.sh | sh # Mac
```

Then, to run scripts in this repo, intialise a new uv virtual environment (venv) or use an existing environment to install the required dependencies.
```bash
# Create uv environment
uv venv --python 3.11.8

# Activate uv venv
.venv\Scripts\Activate # Windows
source .venv/bin/activate # Mac
```

### Installing Requirements
```bash
# Install required libraries
uv pip install -r requirements.txt
```

## Authors
[Keith Sng](keith.sngth@gmail.com)
