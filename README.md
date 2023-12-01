# Kaggle
Kaggle competition

## how to use:

1. download this repo into your local machine (this will create a folder named `Kaggle` in your working directory):

   ```
   git clone git@github.com:NxNiki/Kaggle.git
   ```
   
2. set up conda environment (this is essential for code reproducibility):
   it's recommended to use the project name as your environment name.
   
   ```
   conda create --name SpaceshipTitanic python=3.9
   conda activate SpaceshipTitanic
   ```

3. go to the folder and create your folder for a specific project:
   use poetry to manage Python libraries (this makes it easy for others to keep a track of the Python libraries used in your project):
   
   ```
   # install poetry if you don't have it (will take a few minutes...):
   curl -sSL https://install.python-poetry.org | python -
   cd Kaggle
   # create project: it's recommended to use the project name as your environment name.
   poetry new SpaceshipTitanic
   cd SpaceshipTitanic
   ```
   
4. Open the file named pyproject.toml and add your libraries:

   ```
   [tool.poetry]
   name = "spaceshiptitanic"
   version = "0.1.0"
   description = ""
   authors = ["NxNiki <michaelniki1988@gmail.com>"]
   readme = "README.md"
   
   [tool.poetry.dependencies]
   python = "^3.9"
   pandas = "^1.0"
   numpy = "^1.2"
   scikit-learn = "^1.3"

   [tool.poetry.dev-dependencies]
   jupyter = "^1.0.0"
   
   
   [build-system]
   requires = ["poetry-core"]
   build-backend = "poetry.core.masonry.API"


   # update dependencies every time you change pyproject.toml:
   poetry update
   ```



 
