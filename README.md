[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/e--wBz4e)


## Environment setup

Python version

This project was developed using Python 3.14.0.

## Virtual environment

To keep the environment clean and avoid dependency issues, it is recommended to use a virtual environment.

First, create the virtual environment:

`python -m venv venv`

Then activate it:

On macOS / Linux:
`source venv/bin/activate`

When the environment is active, you should see (venv) in the terminal.

## Install dependencies

All required libraries are listed in the file requirements.txt.

After activating the virtual environment, install them with:

`pip install -r requirements.txt`

## Running the notebooks

The project is mainly organized around Jupyter notebooks.

To run them correctly:

Activate the virtual environment:
`source venv/bin/activate`

Start Jupyter:
`jupyter notebook`

Open the notebooks inside the notebooks folder.

Make sure the selected kernel uses the Python interpreter from the virtual environment.

## Project structure

The project is organized as follows:

final-project-arianafm/   
├── data/   
│   ├── raw/            Original input data   
│   └── cleansed/       Cleaned and processed data   
│   
├── notebooks/          Jupyter notebooks for data preparation,   
│                       modeling, and evaluation   
│   
├── src/   
│   └── metrics.py      Helper functions for evaluation, provided by the course instructors   
│   
├── requirements.txt    List of required Python libraries   
├── README.md           Project description and instructions   
└── .gitignore          Git ignore rules   

The raw data folder contains the original files.   
The cleansed folder contains the processed versions used in the experiments.    
   
Note: The `data` folder was not submitted; its structure is included in the README for informational purposes only, to indicate how it should be organized.

