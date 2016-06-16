# GenericBeanstalkWithRDS_CFNTemplate
This generic CFN Template will create Beanstalk + RDS by collecting information from users. You can either use this template through AWS Cloudformation from the console or through AWS Service Catalog.


With attached CFN we can perform the following:

1) Launch EBS stack along with RDS

      a) As of now this CFN launches only MySQL RDS. Need to make changes so that users can pick the Engine type.
      
2) We can select ELB’s to be in public or private subnets

3) We can select EC2’s to be in public or private subnets

4) It will always launch RDS in DB subnets

      a) As of now it assigns only one security group. Need to make changes so that we can list the SG’s for users to select.
      
5) Gives an option to Assign public IP or not.

6) Add’s configs in the Beanstalk env.
