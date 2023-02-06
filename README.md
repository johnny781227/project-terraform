# project-terraform
Using terraform to create aws-instances andmaking sure that after applying terraform plan the public ip of the instances are exported to a file called host-inventory .Then create an ansible script that uses the host-inventory file to install apache and displays a simple HTML page that displays content to clearly identify on all the EC2 instances
