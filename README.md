## ASSIGNMENT

1. Create s3 bucket from the cli. name for s3 bucket should be yourname_scalagos

To create S3 bucket from cli, i used windows OS to achieve this
- First i downloaded and run the AWS CLI MSI installer for Windows (64-bit), then i confirms that it has installed successfully by running the code "aws --version"
- Second i ran this command the create the bucket on us-east-1 region

   `aws s3api create-bucket \
    --bucket my-bucket \
    --region us-east-1`

2. Create Iam user. Attach a Policy to read S3 bucket AmazonS3ReadOnlyAccess. Create Access Keys for the User. Create a git repo and push your script to the repo with process screenshot, name user sca_lagos

- I Created Iam user, attach a policy (AmazonS3ReadOnlyAccess, and adminright). Next, i created an access key for the user. All these i did from AWS Console Management




