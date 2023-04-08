# Installing_Nexus3_using_Ansible

##Ansible


Ansible is an open-source, cross-platform tool for resource provisioning automation that DevOps professionals

##Nexus 

![1_2b4k1_SmKkNRgqZV-NMFQg](https://user-images.githubusercontent.com/122731503/230691133-883885a9-e5fa-417c-9165-87c05c11cd50.png)

Nexus by Sonatype is a repository manager that organizes, stores and distributes artifacts needed for development. With Nexus, developers can completely control access to, and deployment of, every artifact in an organization from a single location, making it easier to distribute software

##Prerequisite

1- Installing Ansible to the master server , You can see the guide from Here (https://docs.ansible.com/ansible/latest/installation_guide/installation_distros.html)

2- Making SSH connection to the client server which nexus will be installed on

##Installation

Just go to the file path and run the following Command :)

**ansible-playbook -i inventory project.yml**

The last Task to check if Nexus is responding, If u got 200 Ok that means its running successfuly :)

![image](https://user-images.githubusercontent.com/122731503/230696035-34341f0d-bce1-44de-b094-7687276a6f52.png)

To access the nexus dashboard, visit http://:8081. You will be able to see the nexus homepage as shown below.

![image](https://user-images.githubusercontent.com/122731503/230696126-42644132-433a-4671-988e-ce20178c656b.png)







