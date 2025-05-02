#  expense ec2 module


**Inputs**

* ami_id(optional): String value. default value id devops-practice ami id.
* sg_id(mandatory): User must be supply sg id
* instance_type(optional): t3.micro is a default value. user can provide t3.small or t3.medium
* tags(optional): Default is empty user can provide tags in map structure

**output**
public_ip : public ip of the created instance
private_ip: private ip of the created instance