# AWS-EC2-Launch

### Launch an EC2 Instance

1) Service -> EC2
2) Create Instance -> Select "Amazon Linux 2 AMI (HVM), SSD Volume Type" -> t2.micro 
3) Configure Instance Details -> Default VPC
4) add tags : Name, EC2 launch
5) Configure Security Group -> choose the right one -> Launch

###### PuttyGen and Putty
1) Open PuttyGen -> Load -> put the path of the key -> Save Private Key
2) Open Putty -> Session -> Fill the box of IP adress 
3) Go to SSH -> Auth -> Give the right path of the right private PPK key -> Open
4) login as : ec2-user

###### AMI Linux
1) sudo yum update -y
