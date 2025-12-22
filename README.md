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

The project consists of several Jupyter notebooks for data preparation, modeling, and evaluation, together with a small src module containing evaluation metrics provided by the course instructors. Dependencies and usage instructions are documented in the requirements.txt file and the README.md.

Two notebooks are dedicated to data preparation, mainly focusing on data cleaning (`data_prep.ipynb` and `data_prep_2.ipynb`). The hybrid recommendation approaches are implemented in the `A-B-C-D.ipynb` notebook, while reranking is handled separately in the `A-B-E.ipynb` notebook, as this step is more computationally expensive. The data is organized into raw and cleansed versions, but the data directory itself is not included in the submission.

