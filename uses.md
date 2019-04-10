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
