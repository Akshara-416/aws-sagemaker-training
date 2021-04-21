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

  Below is the output of local execution of the python script
   
  <p>
  <img src="images/local_execution.PNG" width="500">
  </p>

## EC2 Instance Security Group 

  In order to access the flask-app via the EC2-public URL Security groups have to be configured 

  - Inbound Rules 
  <p>
  <img src="images/inbound.PNG" width="500">
  </p>

## Accessing the EC2-deployed flask-app via the EC2-public URL at the port 8085
  
  <p>
  <img src="images/ec2_deployed_url.PNG" width="500">
  </p>

## Cost Allocation Tags
  
  Tags are attached to resources during creation for effective AWS resource management.
  To view tags in the Billing reports they have to be activated first for cost allocation:
  
  <p>
  <img src="images/cost_allocation_tags.PNG" width="700">
  </p>

## Billing Report

   The Billing Report can be viewed filtering on specific tags. 
   Here **aws-training** is the tag created and **assignment-1** is the value
   
   <p>
  <img src="images/Billing _Report.PNG" width="700">
  </p>


## Billing Configuration

   - Billing can be configured to recieve alerts on free-tier usage
   
   <p>
  <img src="images/cost_management.PNG" width="800">
  </p>

   - Also the reports can be configured to be stored in S3 bucket
   
   <p>
  <img src="images/Billing_preferences.PNG" width="800">
  </p>
   
   
 

   
