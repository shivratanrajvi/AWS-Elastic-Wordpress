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
- [Step 1]
- [Step 2]
- [Step 3]
- [Step 4]
- [Step 5]
- [Step 6]
- [Step 7]

# Install VPC

- Click to Install [VPC](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/quickcreate?templateURL=https://learn-cantrill-labs.s3.amazonaws.com/aws-elastic-wordpress-evolution/A4LVPC.yaml&stackName=A4LVPC)

# Important Diagram to Understand
- Will Update Soon.....
