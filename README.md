# splunk_standalone_ec2
An AWS CloudFormation template to launch a single Splunk Enterprise (v8.0.0) instance on EC2.

To deploy a single Splunk Enterprise instance on EC2 (Amazon Linux AMI) automatically using CloudFormation, use the template splunk_standalone_ec2.json to create a stack by entering the stack name and parameter values. Once stack creation is complete you can view the Splunk URL in the Outputs tab.  The Splunk admin password will be set to "changeme", update the template to set a different admin password.

Splunk will be installed with a trial license that is valid for 60 days after launch. After the trial expires, your deployment will default to Splunk Free.

>Note: This template will launch resources without you being charged if you are under free tier. However, you will incur charges if you have some resources running aleady or exceed the free tier usage limits. Please use caution while deploying this template if you don't want to be billed. 
