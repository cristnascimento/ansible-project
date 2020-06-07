# Considerations

1. EC2 kubectl - must be on the same VPC as the hosted zone
1. Private Hosted Zone: it is not possible include subdomain (dev.crist.br) information on domain (crist.br)
1. Master t2.micro does not work
1. It is not possible to set custom IAM Role to nodes and keep the IAM Role default for the master. Change both.
1. Add policies or change IAM Roles using yaml file created with kops. Then create the cluster.

# References

Simple Playbook nginx install and run
https://www.youtube.com/watch?v=BeYUQaFS-vg

Ansible + Jenkins + AWS
https://www.youtube.com/watch?v=nE4b9mW2ym0

Simple Tutorial

https://www.youtube.com/watch?v=1id6ERvfozo

Ansible + Jenkins + Kubernetes

https://www.youtube.com/watch?v=gVjLDwcA6sQ

Terraform and Ansible together

https://www.youtube.com/watch?v=AsPIKWF1y_M
