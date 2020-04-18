# opencv-lambda-layer-python3
Created a lambda layer on AWS with serverless framework for Opencv library for image processing. 
# Note
 Since numpy is a sub-dependency of opencv, this layers contains numpy too. You can add a noDeploy tag in the manifest if any of your other libraries utilise numpy to save space.

# ARN
- arn:aws:lambda:us-east-1:939532784043:layer:opencv:2

# Install the plugin serverless-python-requirements through npm, yarn or sls
-  sls plugin install -n serverless-python-requirements

# Deploy 
- sls deploy
