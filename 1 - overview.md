# HOW TO HOST WORDPRESS ON AWS EC2

This Process has 7 steps, let's see how we can implement on AWS.

- Step 1 - Setup the environment and manually build wordpress  
- Step 2 - Automate the build using a Launch Template  
- Step 3 - Split out the DB into RDS and Update the LT 
- Step 4 - Split out the WP filesystem into EFS and Update the LT
- Step 5 - Enable elasticity via a ASG & ALB and fix wordpress (hardcoded WPHOME)
- Step 6 - Optional .. move to Aurora and DB HA  
- Step 7 - Cleanup 

# STEPS
- [Step 1](https://github.com/shivratanrajvi/AWS-Elastic-Wordpress/blob/main/STEP-1.md)
- [Step 2](https://github.com/shivratanrajvi/AWS-Elastic-Wordpress/blob/main/STEP-2.md)
- [Step 3](https://github.com/shivratanrajvi/AWS-Elastic-Wordpress/blob/main/STEP-3.md)
- [Step 4](https://github.com/shivratanrajvi/AWS-Elastic-Wordpress/blob/main/STEP-4.md)
- [Step 5](https://github.com/shivratanrajvi/AWS-Elastic-Wordpress/blob/main/STEP-5.md)
- [Step 6](https://github.com/shivratanrajvi/AWS-Elastic-Wordpress/blob/main/STEP-6.md)
- [Step 7](https://github.com/shivratanrajvi/AWS-Elastic-Wordpress/blob/main/STEP-7.md)

# Install VPC

- Click to Install [VPC](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/quickcreate?templateURL=https://learn-cantrill-labs.s3.amazonaws.com/aws-elastic-wordpress-evolution/A4LVPC.yaml&stackName=A4LVPC)

# Important Diagram to Understand
- Will Update Soon.....
