# Nic Vetter - 10/5/2023 - American Football - datafun-07-ml-predictive link: https://github.com/VetterNic/datafun-07-ml-predictive

# Objectives:
In this project, you'll see how we: 

1. provide the data.

2. ask lingress() for the slope & y intercept - it'll figure out the "best fit" straight line through the data (y = mx + b) Now we can ask:
for this x-value, what would be the y-value on that straight line? 


# Goals of Module 7 - regression

This module requires the skills learned in previous chapters. 

In this final module, I'll employ machine learning (ML). At a high-level, there are three general categories of ML: supervised, unsupervised, and reinforcement learning. I'll employ a type of supervised learning, simple linear regression, to train a model using all available data and use the resulting model (a best-fit straight line) to make predictions.

# Steps of the project

1. Task 1: Prepare repo
2. Task 2 and 3: Work through chapter 10 and 15. 
3. Task 4: Complete the project for these chapters showing my proficencies in the tools/techniques discussed in the chapters. 

# This read.me includes instructions with the exact commands to: 

## Create your virtual environment 
    - Open the terminal in VS Code. (View / Terminal)
    - Run the following command to create a virtual environment for this project:
    - python -m venv .venv
    - Verify that a new .venv folder was created. It may take a while for the command to complete.

🚀 Rocket Tip: When VS Code Python Extension offers to select the Environment, say Yes.

## Activate the Virtual Environment
Wait for the creation to finish, then activate the virtual environment:

    - For PowerShell: .venv\Scripts\Activate
    - For macOS/Linux: source .venv/bin/
🚀 Rocket Tip: Notice the terminal changes to reflect the active virtual environment.

## Install all required external dependencies.
Install additional project dependencies into the active virtual environment. The packages ipykernel and jupyterlab are required to run a notebook. The packages pandas, matplotlib, and seaborn are used to work with data and charts.

    - python -m pip install --upgrade pip ipykernel jupyterlab
    - python -m pip install --upgrade pandas matplotlib seaborn
    - python -m pip install --upgrade voila

Alternatively, you can install all the packages listed in the requirements.txt file.

    - python -m pip install --upgrade -r requirements.txt

Note: The --upgrade parameter gets the latest version of each package.




