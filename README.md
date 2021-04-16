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
   
