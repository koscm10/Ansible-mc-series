#**Introduction to Ansible**
Ansible is a tool used for configuration like after you hve created the infrastructure its used to configure and install software. 
Ansible is configuration management tool 

- Ansible is an open-source configuration Management,
deployment and provisioning Automation tool maintained by Redhat (vendor).
- It is very, very simple to setup and yet powerful.
- Ansible will be helpful to perform:
    - Configuration Management
    - Application Deployment (absible can use playbook to deploy inside of k8s)
    - Task Automation
    - IT Orchestration

**How Ansible works**
  - Ansible works by connecting to remote nodes (hosts) and pushing out small programs, called “Ansible
    modules” to them.
  - The pushed programs/modules will be executed on remote server by Ansible over SSH and removes them
    when finished.
  - Unlike Puppet or Chef it doesn’t use an agent on the remote host, Instead Ansible uses SSH. It is agentless.Ansible uses a push mechanism that is initiated by your ansible controller (server w/ ansible installed)
  - (IQ- what other configuration managment tools are there A: puppet + chef)
  - It’s written in Python which needs to be installed on the remote host.
  - This means that you don’t have to setup a client server environment before using Ansible

**Benefits of using Ansible**
 - It is a free open -source Automation tool and simple to use.
 - Uses existing OpenSSH for connection
 - Agent-less – No need to install any agent on Ansible Clients/Nodes
 - Python/YAML based
 - Highly flexible and versatile in configuration management of systems.
 - Large number of ready to use modules for system management
 - Custom modules can be added if needed
