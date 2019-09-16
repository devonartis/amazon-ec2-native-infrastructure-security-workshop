In order to avoid unnecessary ongoing expenses, make sure to clean up all the resources you created in this lab. 

1.  **Empty** and **Delete** your **cloudsecurity-demo-bucket-{myname}** bucket
2.  **Empty** and **Delete** your **cloudsecurity-ssmlogs-bucket-{myname}** bucket
    *  If you got this far
3.  Stop **Config** charges by going to **Settings** and clicking the **Turn off** button to disable the Configuration Recorder. 
4.  Empty and Delete your **Config Bucket**. If you selected the default, that will likely be named config-bucket-ACCTIDXXXXXX
5.  Delete your **CloudTrail Trail**
6.  Disable **GuardDuty**
7.  In **VPC**, go to the **NACLs** you created and **disassociate** them from any subnets.
8.  Now **Delete** the **NACLs**.
9.  In CloudFormation **Delete your Stack**
    *  Wait until this is complete
