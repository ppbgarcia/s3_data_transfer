Project intended to try the S3 object transfer, and some other tools.
The project was divided in the following steps:
- AWS configuration
- Terraform download and configuration
- Creation of the S3 bucket using Terraform
- Load of a .csv and simple cleaning
- Upload of a .csv to the bucket using python through boto3
- Setting up a glue crawler on the aws interface
- Running the crawler to transform the .csv into a table
- Accessing the table using python through Athena
