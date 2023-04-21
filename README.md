## Complete Provisioning with Ansible

This project is a continuation of our previous project where we utilized Ansible for VPC setup. In this project, we will be setting up the a java web application stack on the VPC we previously configured. Our goal is to lift and shift the stack, meaning we will be automatically setting up a bunch of EC2 instances and provisioning the project full stalk stack services, such as MySQL, Memcached, RabbitMQ, Tomcat, and more, by utilizing Ansible.

## Project Overview

We have an operations team responsible for managing all the operating systems in our infrastructure, including cloud and virtual machine setup. This team receives regular requests for provisioning or making changes to the infrastructure. As we are living in a time of agility, where everything needs to be done quickly, we have a lot of disposable environments, such as pre-production environments that are frequently disposable. These requests often involve setting up a complex infrastructure with many moving parts, including different services, networks, security, and high availability.

Setting up the entire stack is complex and time-consuming work, especially when done manually. Repeating the same process multiple times and making regular changes is difficult to track, and there is a higher chance of making mistakes with human intervention, which can lead to costly downtime.

To address these issues, we need to automate the entire process of infrastructure configuration management. An automation framework or tool can manage all infrastructure configurations automatically, which reduces the chance of human error and centralizes all changes. By having the infrastructure managed as code, we can version control it, making it repeatable and reusable across projects.


## Project Goals 

The goal of this project is to set up the V profile application stack automatically, without any human intervention. By utilizing Ansible, we will automate the process of setting up a complex infrastructure with many moving parts, including different services, networks, security, and high availability.

The key benefits of this approach include reducing the chance of human error, centralizing all changes, and making the infrastructure manageable as code, which is repeatable and reusable across projects.



## Project Tasks

- Configure EC2 instances on VPC
- Provision V profile stack services, such as MySQL, Memcached, RabbitMQ, Tomcat, and more
- Automate the entire process of infrastructure configuration management utilizing Ansible
- Make infrastructure manageable as code for repeatable and reusable across projects



## Conclusion

Automating the infrastructure configuration management process is essential in today's time of agility. This project aims to utilize Ansible to set up a complex infrastructure with many moving parts, including different services, networks, security, and high availability. By doing so, we can reduce the chance of human error, centralize all changes, and make the infrastructure manageable as code, which is repeatable and reusable across projects.




