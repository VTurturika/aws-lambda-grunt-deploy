# aws-lambda-grunt-deploy
Simple example of deploying AWS Lambda function using [Grunt.JS](http://gruntjs.com/)

## How to use?
- Create AWS Lambda function using AWS Management Console (learn [here](http://docs.aws.amazon.com/lambda/latest/dg/getting-started.html)) 
- Clone the repository:
```
git clone git@github.com:VTurturika/aws-lambda-grunt-deploy.git
```
- Install dependencies packages:
```
npm install
```
- Edit your AWS Lambfa function in index.js. For more information learn [here](http://docs.aws.amazon.com/lambda/latest/dg/welcome.html).
- Specify your local test events in events.json (for ```grunt lambda_invoke```).
- Edit your AWS_ACCESS_KEY_ID, AWS_ACCESS_KEY_ID and your lambda function ARN in credentials.env
- Set up your environment variables:
```
source credentials.env
```
- Deploy your function:
```
grunt deploy
```




