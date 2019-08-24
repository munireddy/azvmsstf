The objective of this project is to creatre a VMSS with two(2) Ubuntu instances. Each of the instance is installed with docker. 
To use this code you need to follow the below instructions:
1. lon on to azure.com
2. Open Cloudshell
3. git clone this project 
4. cd azvmsstf
5. terrafrom init
6. terraform plan 
     In this step, it will ask you for the location where you want to create the VMSS instances. you may give 'eastus'
7. terraform apply 
     In this step, it will ask you for the location where you want to create the VMSS instances. you may give 'eastus'
     and confirmation 'yes'
8. vmss would by created when the previous command is completed.
9. goto VMSS instances and check if docker is installed or not.

-----------------------------Next enhancements to this could be 
Make changes to run this script outside of azure portal. Which needs the az login with service prinicipal and apply the 
the tf files written here


     
