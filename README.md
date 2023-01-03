# DDST
Repo for DDST 

To run:

download training and testing datasets from

train - https://drive.google.com/file/d/17p5l1Zy0PgfSplkTmf82J9K7XQZcTKXa/view

test - https://drive.google.com/file/d/1_qQN9I1p4-jaeJg4tpgMlZHBLg4GxBRV/view


### Set up  
1. Create a 'datasets' folder in project directory and add the .rpt files to datasets folder
2. Create an assets folder and copy contents from https://drive.google.com/drive/folders/15s_g50mBL-g5X0_WjKuqK8gv9uP9Yoxa?usp=share_link

project directory should look like:

/DDST

    - /datasets

        - DatiumTest.rpt 

        - DatiumTrain.rpt   
          
    - /assets  
        - columns_used.save  
        - encoder.save  
        - imputer.save  
        - model.save  
        - normalizer.save  

    - /experiments  
  
    - /scripts  
  
    - .gitignore  
      
    - README.md  


### Viewing experiment logs  
To view mlflow experiment logs, run the command "mlflow ui" and pass the URI of the "experiments" folder to the "--backend-store-uri" arg.  
Example:  
```console
mlflow ui --backend-store-uri file:///Users/rusernyeoh/projects/datium_data_science_test/DDST/experiments
```