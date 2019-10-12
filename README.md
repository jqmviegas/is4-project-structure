# IS4 Project Structure

*A logical, reasonably standardized, but flexible project structure for doing and sharing work. (based on [Cookiecutter Data Science](https://www.markdownguide.org/basic-syntax/))*

This repository contains the base structure for research projects and theses. Please follow the folder structure presented as close as you can. As all projects have different requirements, you will probably have to change the structure a bit to fit your needs.

### Folder structure

The directory structure of your new project looks like this (please adjust the structure and its description to best fit your project): 

```
├── README.md          <- The top-level README for contributers of this project.
│
├── data
│   ├── raw            <- The original, immutable data dump.
│   ├── interim        <- Intermediate data that has been transformed.
│   └── processed      <- The final, canonical data sets for modeling.
│
├── docs               <- Documents
│   ├── reports        <- Generated analysis as HTML, PDF, LaTeX, DOCX etc.
│   ├── figures        <- Generated graphics and figures to be used in reporting
│   └── thesis         <- Thesis source files
│       └── templates  <- Thesis templates
│
├── references         <- Articles, books and other references used in your project. It is good practice to reference these materials in the comments of your code.
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering), the creator's initials, and a short `-` delimited description, e.g. `1.0-jqp-initial-data-exploration`.
│
├── requirements.txt   <- The file with instructions for reproducing the project environment (software). Indicates the version of  software you are using. If using Python, you can do `pip freeze > requirements.txt` to generate a list with the version of the different packages you use
│
└── code               <- Source code for use in this project.
    ├── data           <- Scripts to download, generate and process data
    │   └── make_dataset.py/m
    │   └── process_dataset.py/m
    │
    ├── algorithms     <- Functions to create models, run models, optization algorithms, etc.
    │
    ├── results        <- Scripts to apply the algorithms and obtain the results of your project
    │
    └── visualization  <- Scripts and functions for visualizations

```


### Readme file

This file, `README.md`, should be used to include all information on the files included in the project and how to make them work.

It makes use of Markdown, which is a markup language focused on readability. You can find information on the main syntax of Markdown in:

[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

[Markdown Basics Guide](https://markdown-guide.readthedocs.io/en/latest/basics.html)

[Daring Fireball Markdown Syntax Guide](https://daringfireball.net/projects/markdown/syntax)

Multiple text editors, such as Visual Studio Code, Sublime Text, Atom, Notepad++ have extensions that you can install to transform the Markdown file (.md) into a .pdf or .html.


### Using Git and GitHub

To make sure you don't lose your work, improve collaboration potencial and supervisor feedback, it is advised to copy this structure to a folder and create a Git repository from it.

If you have never used Git, you will have to follow the following steps:

1. Register on [GitHub](https://github.com)
2. Download and install [GitHub Desktop](https://desktop.github.com/)
3. Go to [IS4 Project Structure Repository](https://github.com/jqmviegas/is4-project-structure) and click on **Use this template**
4. Give a name to your repository and make sure you make it private
5. Open the GitHub Desktop software and login with your GitHub credentials
6. Go to: File -> Clone repository ...
7. Select your newly created GitHub repository and choose the directory you want to save it on
8. Clone!
9.  Work, commit and push changes everyday!

For additional information on using Git and GitHub:

- [Getting started with GitHub Desktop](https://help.github.com/en/desktop/getting-started-with-github-desktop)
- [An Introduction to Version Control Using GitHub Desktop](https://programminghistorian.org/en/lessons/getting-started-with-github-desktop)

### Contributers

jqmviegas (Joaquim L. Viegas): [joaquim.viegas@tecnico.ulisboa.pt](joaquim.viegas@tecnico.ulisboa.pt)