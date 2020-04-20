# AWS-DynamoDB
Querying and managing AWS DynamoDB using python

We have used Python and Boto 3, the AWS SDK for Python, for interacting with the DynamoDB APIs.

You can use AWS Free Tier Services to play around with AWS and everything it offers.

## What is DynamoDB?
It is a fully managed, fast and scalable NoSQL database solution that delivers reliable solution at any scale.

## Advantages of DynamoDB
- no limit on table size
- it replicates data in 3 AZs ensuring availability and redundancy.
- it is a fully cloud managed DB and supports both document and key-value store modules.

## FACTS

- It can handle more than 10 Trillion requests per day
- can support peaks of 20 millions requests per second

### STEPS:
Download required libraries : 
1) Download and unpack the module code by running the following command in the AWS Cloud9 terminal
'''
curl -sL https://s3.amazonaws.com/ddb-deep-dive/dynamodb.tar | tar -xv
'''

2) To install Boto 3, run the following command in the AWS Cloud9 terminal.
'''
sudo pip install boto3
'''
