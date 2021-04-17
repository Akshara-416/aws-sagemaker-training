# flask-list-folders

This code is used to list the folder structure and contents of S3 buckets using boto3

## Create the environment from .yml file

   - conda env create -f env.yml
   The environment consists of all the required dependencies installed

## Activate the environment created

   - conda activate flask-env
   
## Make sure to add your credentials in the file ~/.aws/credentials

   [default]
   
   aws_access_key_id = 'your_access_key'
   
   aws_secret_access_key = 'your_secret_key'

## How to run the script

   python flask-app.py 
   
## Output of the script

 ![image](https://user-images.githubusercontent.com/73812792/115014600-2cfb8780-9ed0-11eb-9f12-ce44dea6b76d.png)

## Accessing the EC2-deployed flask-app via the EC2-public URL at the port 5080
   
 ![image](https://user-images.githubusercontent.com/73812792/115104663-9c788200-9f77-11eb-88fc-09734bdea1b9.png)

   
