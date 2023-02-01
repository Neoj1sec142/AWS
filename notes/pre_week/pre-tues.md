# Terraform with AWS:
- What is terraform
![what is?](./assets/tr1.png)
![agnostic](./assets/tr2.png)
- What is it used for?
![use cases](./assets/tr3.png)
- What will learning it do for me?
![help-me?](./assets/tr4.png)
- how does it work?
- it usees the .tf files as config files to provision the infrastructure in stated cloud prviders for you and records state of provisions
![how](./assets/tr5.png)

- Installing Terraform in Cloudshell
```s
sudo yum install -y yum-utils

sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/AmazonLinux/hashicorp.repo

sudo yum -y install terraform
```

- upload main.tf to cloudshell
![Terraform Notes](./assets/tr6.png)      
![Terraform Notes](./assets/tr7.png)      
![Terraform Notes](./assets/tr8.png)      
terraform destroy (destroys infrastructure if no files are contained)