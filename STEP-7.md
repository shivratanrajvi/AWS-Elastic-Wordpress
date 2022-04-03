
# In this final stage of this lesson you are going to clean up the account and remove all resources created during this lesson.  

# Delete Load Balancer & Target Groups

First, got to the EC2 console and click on `Load Balancers` under `Load Balancing` 
Select the `A4LWORDPRESSALB`  click `Actions` and select `Delete` and then click `yes, Delete`  
Click `Target Groups`, select the target group you created earlier and click `Actions` and then `Delete`, then click `Yes, Delete`  

# Delete Auto Scaling Group

Click `Auto Scaling Groups` under `Auto Scaling`  
Select the `A4LWORDPRESSASG` you created earlier and click `Delete`, type `delete` and click `delete` to confirm.  
this will take a while because the EC2 instances will be terminated as part of this.  

# Delete the EFS File system

Click `Services` and type `EFS` then move to the EFS console.  
Select the `A4l-WORDPRESS-CONTENT` File system, and click `Delete`. Confirm by typing in the file system ID and then clicking `Confirm`  

# Delete RDS

Click on `Services`, type `RDS` and move to the RDS Console.  
Click `Databases`  
Select `a4lwordpress`, click `Actions` and `Delete`  
Uncheck `Create Final Snapshot`, check the `Acknowledge` box, type `delete me` and click `Delete`  
Select `a4lwordpress-aurora-reader2`, click `Actions` then `Delete`. Type `delete me` and click `Delete`  
Select `a4lwordpress-aurora-reader1`, click `Actions` then `Delete`. Type `delete me` and click `Delete`  
Select `a4lwordpress-aurora`, click `Actions` then `Delete`. unckeck `create final snapshot`, check the `Acknowledge` box, Type `delete me` and click `Delete`  

# Check Progress

Check that EFS and all EC2 instances, and ASG have finished deleting - hold here until they have both been removed.

# Delete Launch Template

Move to EC2 Console, click on `Launch Templates`  
Select the `Wordpress` Template, Click `Actions` and then `Delete Template`. Type `Delete` and Click `Delete`  

# Wait for RDS

Move to the RDS console, click on `Databases` & wait for all RDS instances to be removed before continuing.  

# RDS Snapshot

Click `Snapshots`  
Select the `a4lwordpressmigration` snapshot, click `Actions` `Delete Snapshot`, click `Delete` to confirm.  

# Cloud Formation

Move to the cloudformation console.  
Select the `A4LVPC` stack, click `Delete` and confirm by clicking on `Delete Stack`

# FINISH

Thats all the things ... thanks for reading :)
