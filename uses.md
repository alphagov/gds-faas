[Back to README...](README.md)

# Uses at GDS

1. **CloudSecurityWatch**
 - Cyber Security Team
 - Frontend web app using [Chalice](https://github.com/aws/chalice)
 - https://github.com/alphagov/csw-backend
 
2. **Cyber CloudWatch Fluentd to Splunk HEC**
 - Cyber Security Team
 - Backend function to stream data out of CloudWatch
 - https://github.com/alphagov/cyber-cloudwatch-fluentd-to-hec 
 
3. **TechOps Q1 2019 Firebreak project**
 - Cyber Security Team
 - Frontend app utilising Flask and [Serverless WSGI](https://github.com/logandk/serverless-wsgi)
 - [PyJWT](https://pyjwt.readthedocs.io/en/latest/) to handle JWT from the ALB (ELBv2) with built-in authentication
 - Deployment using Concourse/Terraform
 - https://github.com/alphagov/firebreak-q1-faas
 
4. **Verify Event Record Service**
- GOV.UK Verify
- Used to record audit events consumed from a SQS into a PG RDS database
- https://github.com/alphagov/verify-event-recorder-service

5. **Rails Lambda Spike**
- GOV.UK Verify
- A spike into running a Ruby on Rails lambda
- https://github.com/alphagov/rails-lambda-spike

6. **Registers CloudFront Lambdas**
- GOV.UK Registers
- Used to track API usage in Google Analytics
- Lambda@Edge on CloudFront Viewer Requests writes to CloudWatch Logs
- Lambda to consume aformentioned logs and send events to Google Analytics
- Log Anonymiser anonymises CloudFront logs for GDPR compliance and long term analysis.
- Lambda@Edge and associated Lambda to trigger a CloudFront Invalidation Request when a POST request is made
- https://github.com/openregister/deployment/tree/master/aws/lambda