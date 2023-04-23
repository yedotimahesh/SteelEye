# steelEye
https://github.com/steeleye/recruitment-ext/wiki/Python-Engineer-Assessment

# Configuration
S3 bucket name and the initial url to get xls file is parameterized in config.json.

# AWS Lambda
1. dict_creator.zip is ready to be deployed as a AWS Lambda function (dict_creator.lambda_handler).

# Running the script
1. To test the script, install all the dependencies in requirement.txt by executing the below command,
'pip install -r requirements.txt' 
2. Execute dict_creator.py.

# Results
1. The file downloaded from the given url will be saved in the root folder of the project in xlsx format.
3. The data from the downloaded file will be uploaded to S3 bucket as a json file.
2. The script returns url to the  json file uploaded to S3 bucket (If the return_url parameter is configu.red in config.py)


