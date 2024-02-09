# aws-notes
aws-notes

AWS

# EC2

## Amazon Linux
ssh -i dpp.pem ec2-user@34.201.245.118

Becoming root: “sudo su -sh”

## Ubuntu

ssh -i pras-vivo-key-2.pem ubuntu@52.202.26.181


ssh -i dpp.pem ubuntu@52.202.26.181

Becoming root: “sudo su -“


scp -i /Users/mitchellkimbell/desktop/devops-files dpp.pem ubuntu@52.90.8.209:/opt/


ssh user-fqdn@LinuxBastion-fqdn -L 2222:52.90.8.209:22
