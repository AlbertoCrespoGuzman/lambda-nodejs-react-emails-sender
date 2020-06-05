# Nodejs - Backend 

Basic Nodejs server which will request S3 to sign the url and will send the file to S3.

### Features

  - Validates email form
  - Get URL signed by S3
  - Sends the file with the form

### Installation

Create your own `.env` and add your S3 credentials (fill the list) :
AWSAccessKeyId=your_aws_key
AWSSecretKey=your_aws_secret_key
bucket=your_bucket_name
region=your_code_region(example:us-east-1)
from_email=your_sender_email

```sh
$ npm install
$ npm start
```
It works in `localhost:3001`



