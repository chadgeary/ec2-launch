# Reference
Launches <n> AWS EC2 instances

# Note
 - Several variables are required, e.g.:
```
instance_type: t3a.nano
group_id: sg-xxxx
vpc_subnet_id: subnet-xxxx
key_name: centos-key-name
image: ami-0f2b4fc905b0bd1f1 # CentOS 7 latest as of Sept 2019
instance_name: somename1 # Tag: Name
```
 - Runs from localhost
