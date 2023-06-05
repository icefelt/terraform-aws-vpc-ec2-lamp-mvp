# terraform-aws-vpc-ec2-lamp
terraform-aws-vpc-ec2-lamp

This code creates a VPC with a single subnet, an Internet Gateway, and a Security Group The Scurity Group allows incoming traffic on ports 22, 80, and 443 and outgoing on all ports and protocols. This code also creates an EC2 instance in the subnet, using a user data script to install Apache, MySQL, and PHP. 

Note: This code installs in us-west-2 for testing. 

To connect with SSH
ssh -i ~/tomcat-test.pem ec2-user@<inster_IP_here>