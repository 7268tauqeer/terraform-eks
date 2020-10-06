**Pre-Req:**
1- Configur below mentioned variables for CI/CD pipeline
*AWS_ACCESS_KEY_ID
AWS_DEFAULT_REGION
AWS_SECRET_ACCESS_KEY*

**Notes:**
1- Deployment stage need to executed manually
2- Update env/cluster.tf with subnet values where nodes from nodegroup need to be deployed
3- Update instance_types based on requirement

**Enhancement**
1- intigrate variables in tf code.
2- setup tfstate with s3 and dynamodb# terraform-eks
