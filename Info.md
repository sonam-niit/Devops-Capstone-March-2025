# Application Flow

- create 3 buckets
    1. remote backend
    2. to upload frontend application
    3. to upload images

- 2 Lambda functions
    1. Generate presigned URL
    2. process uploaded file

- dynamoDB table 
    - store data which is uploaded

- everytime when you push this terraform.yml will execute so you can
- make changes from apply to destroy in last command to it will remove 
- resources created as these resources are not free to use.

