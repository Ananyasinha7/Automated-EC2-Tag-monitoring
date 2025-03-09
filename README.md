# Automated-EC2-Tag-monitoring
Utilizing the AWS SNS service along with AWS EventBridge and AWS Lambda for detecting missing tags in the ec2 instances and informing the users about the same via email.

AWS EventBridge- Triggers periodically to check EC2 instances
AWS Lambda function- Gets invoked by the EventBridge event to check if the instances have the required tag or the value is missing
AWS SNS- Sends the email when such instances are detected

