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
   use poetry to manage Python libraries (this makes it easy for others to install the Python library:
   
   ```
   # install poetry if you don't have it (will take a few minutes...):
   curl -sSL https://install.python-poetry.org | python -
   cd Kaggle
   # create project: it's recommended to use the project name as your environment name.
   poetry new SpaceshipTitanic
   cd SpaceshipTitanic
   ```



 
