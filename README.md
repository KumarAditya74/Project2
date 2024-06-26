## Deployed Link : https://project2-zfab.onrender.com/

## End to End Project

### Step 1: Create a new environment

```
conda create -p venv python==3.10

conda activate venv/
```
### Step 2: Create a .gitignore file

```
create the file by right click and include the venv in it
```

### Step 3: Create a requirements.txt file 
```
pip install -r requirements.txt
```

### Step 4: Create a setup.py file 
```
This is to install the entire project as a package. Additionally, write a function to read the packages from requirements.txt
```

### Step5: Create a folder `src` 
```
Include exception, logger, and utils python files. Make this folder as a package by including __init__.py file. The scr folder will include another folder with name components will be created. Include __init__.py also 
```
#### Step 5.1 Create a folder `components`

```
Include data_ingestion, data_transformation, model trainer, and __init_.py. These components are to be interconnected in future. 
```
#### Step 5.2 Create a folder called `pipeline`
```
Create two python files training_pipeline and prediction_pipeline with __init__.py folder
``` 

### Step 6: Create a folder called `notebooks` 
```
Create a folder called data and include the dataset. Additionally, create a EDA.ipynb file to do the EDA analysis.
```
###  Step 7:   Install necessary packages using pip
###  Step 8: Inside components : make three files `data_ingestion` , `data_transformation` , `model_trainer`
```
            In each of these files, write import statements for the respective modules that you will be using. 
```
### Step 9: Inside pipeline, create `prediction_pipeline` and `train_pipeline`

### Step 10: Create `exception.py` for handling exceptions and `utils.py` for all the required utilities.

### Step 11: Integrate all the things using modular coding.

### Step 12: Create a template folder for creating the UI and  frontend part of application. 

### Step 13: Use a framework like `flask` for maintaining the app

### Step 14: Now run the app using `app.py`
