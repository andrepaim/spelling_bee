# Spelling Bee Trainer

Welcome to the Spelling Bee Trainer! 

This is a very simple web app designed to help my son prepare for his school spelling competition. 

The Spelling Bee Trainer uses a list of words provided by the school.

You can access the web app directly [here](https://andrepaim.github.io/spelling_bee).

## Project Structure

The project is composed of the following main components:

- `index.html`: The main HTML/Javascript file that hosts the web app.
- `data.csv`: A CSV file containing the spelling words provided by the school, along with their Portuguese translations and usage in a sentence.
- `notebooks/img2text.ipnb`: A Jupyter notebook used to generate the images for the hint dialog based on the sentences.

## Dependencies Installation

This project uses Poetry for dependency management. If you haven't installed Poetry yet, you can do so by following the instructions on the [official Poetry website](https://python-poetry.org/docs/#installation).

Once you have Poetry installed, you can install the project dependencies by navigating to the project directory in your terminal and running the following command:

```bash
poetry install
```

This is only necessary for generating the images.
