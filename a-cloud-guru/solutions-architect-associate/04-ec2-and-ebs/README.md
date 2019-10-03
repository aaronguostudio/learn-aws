# EC2 Pricing Models
- On demand
- Reserved
  - Standard Reserved intances
    - up to 75% off
    - can't change type
  - Convertible Reserved instances
    - up to 45% off
    - can't change type
  - Schedule Reserved
    - schedule based on timing
- Spot
- Dedicated Hosts

# Connect to EC2
- chmod 400 thekey.pem
- ssh ec2-user@ip -i thekey.pem
- A chrome extension Secure Shell App is handy for ssh to server from browser
- ssh-keygen -y -f thekey.pem > thekey.pub
  - remove extension .pem
- yum install -y
- yum install httpd -y
- service httpd start
- chkconfig on

# Exam for EC2
- When first launch, can't encrypt the root, can setup it later. Additional volume are OK to encrypt when the first time launch
  - can use a third party tool (such as bit locker etc) to encrypt the root volume, or do this when creating AMI's in the AWS console or using the API
- Default all inbound traffic is blocked
- All outbound traffic is allowed
- Termination Protection is turned off by default
- mulitiple security groups are OK
- Changing security group will take effect immediately
- security groups are stateful
  - inbound will auto add a outbound
  - can't block an individual port
- in PVC, network access controll lists is stateless, create a inbound will also need an outbound rule
  - can block an individual port / no deny rules

# EBS
- Types
  - General Purpose (SSD)
    - most work loads
    - gp2
    - 1gb - 16 tb
  - Provisioned IOPS (SSD)
    -
  - Throughout Optimised Hard Disk Drive
  - Cold Hard Disk Drive
  - Magnetic

<!-- https://acloud.guru/course/aws-certified-solutions-architect-associate/learn/ec2/ebs-101/watch?backUrl=~2Fcourses -->
