[![Shipping files](https://github.com/neuefische/ds-eda-project-template/actions/workflows/workflow-03.yml/badge.svg?branch=main&event=workflow_dispatch)](https://github.com/neuefische/ds-eda-project-template/actions/workflows/workflow-03.yml)
# ds-project-template

Template for creating ds simple projects

## Requirements

- pyenv
- python==3.11.3

## Setup

One of the first steps when starting any data science project is to create a virtual environment. For this project you have to create this environment from scratch yourself. However, you should be already familiar with the commands you will need to do so. The general workflow consists of... 

* setting the python version locally to 3.11.3
* creating a virtual environment using the `venv` module
* activating your newly created environment 
* upgrading `pip` (This step is not absolutely necessary, but will save you trouble when installing some packages.)
* installing the required packages via `pip`

*Note: We do have the `requirements.txt` in the repository but please try to first install packages by yourself.*

At the end, you want to make sure that people who are interested in your project can create an identical environment on their own computer in order to be able to run your code without running into errors. Therefore you can create a `requirements file` and add it to your repository. You can create such a file by running the following command: 

```bash
pip freeze > requirements.txt
```

*Note: In rare case such a requirements file created with `pip freeze` might not ensure that another (especially M1 chip) user can install and execute it properly. This can happen if libraries need to be compiled (e.g. SciPy). Then it also depends on environment variables and the actual system libraries.*


--- 
## In Case of Failure
If you fail to do the setup by yourself, then please revisit the previous repositories where you have done the setup and follow those steps.

## EDA_Jennifer Analysis
This jupiter notebook describes how data are plotted to analyse below hypothesis for the requirements matching Jennifer Montgomery who wants to buy house with below requirements:
High budget, wants to show off, timing within a month, waterfront, renovated, high grades, resell within 1 year

## Below Hypothesis table formulated
✓ HYPOTHESIS 1: Grade & Condition Premium
  - High grade (10-13) + Good condition (4-5) = Highest prices
  - Broader market availability
  - Jennifer can find luxury properties anywhere in the county

✓ HYPOTHESIS 2: Size + Grade = Premium
  - Large homes (3000+ sqft) with high grades command premium prices
  - Spacious + High Quality = Luxury Appeal
  - Perfect for someone who wants to "show off"
  - Attracts wealthy buyers in resale market

✓ HYPOTHESIS 3: Luxury Package (Multi-Factor)
  - Combining Grade 10+, Condition 4+, Size 3000+ = True Luxury Segment
  - Premium Luxury properties available
  - Average Price: $?
  - These are the HOTTEST resale items for wealthy buyers

JENNIFER'S BEST STRATEGY:
Target Tier 2 Premium Luxury properties:
  • Grade: 11+
  • Condition: 4+ (Good/Excellent)
  • Size: 3000+ sqft (spacious, impressive)
  • Price: $M
  • Properties available: 
  
These properties have STRONG RESALE potential and appeal to luxury buyers

