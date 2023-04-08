# Installing_Nexus3_using_Ansible

## Ansible

Ansible is an open-source, cross-platform tool for resource provisioning automation that DevOps professionals popularly use for continuous delivery of software code by taking advantage of an “infrastructure as code” approach

## Nexus 

![1_2b4k1_SmKkNRgqZV-NMFQg](https://user-images.githubusercontent.com/122731503/230691133-883885a9-e5fa-417c-9165-87c05c11cd50.png)

Nexus by Sonatype is a repository manager that organizes, stores and distributes artifacts needed for development. With Nexus, developers can completely control access to, and deployment of, every artifact in an organization from a single location, making it easier to distribute software

## Prerequisite

1- Installing Ansible on the master server , You can see how to install it from the guide [Click Here] (https://docs.ansible.com/ansible/latest/installation_guide/installation_distros.html)

2- Making SSH connection between the master server and the client server which nexus will be installed on

## Installation

Just go to the file path and run the following Command :)

![image](https://user-images.githubusercontent.com/122731503/230696328-2860d039-95e2-4e82-8ddf-d8bcbb828d00.png)

The last Task to check if Nexus is responding, If u got 200 Ok that means its running successfuly :)

![image](https://user-images.githubusercontent.com/122731503/230696035-34341f0d-bce1-44de-b094-7687276a6f52.png)

To access the nexus dashboard, visit http://:localhost:8081. You will be able to see the nexus homepage as shown below.

![image](https://user-images.githubusercontent.com/122731503/230696126-42644132-433a-4671-988e-ce20178c656b.png)







