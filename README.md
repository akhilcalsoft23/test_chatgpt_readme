To use a role in an Ansible playbook, you simply need to list it in the roles section of the playbook. Ansible will then automatically load the role and execute its tasks.

For this module, There are 5 roles.
1. <a name="input_intel_optimized_mysql_server_ico_by_densify"> intel_optimized_mysql_server</a> 

**Playbook**:- An Ansible playbook is a YAML file that describes the tasks, are composed of a series of plays, which are groups of tasks that are executed in a specific order. Each play defines a set of tasks that should be executed on a specific group of hosts.
         Playbooks can also include variables, which can be used to store data that is used by the tasks. This makes it easy to reuse playbooks for different environments and configurations.
         for this module. 
For this module, There are 6 playbooks, Where
1. Playbook **intel_aws_mysql.yml** - Used to create an Amazon RDS Intel optimized instance for MySQL, it uses Terraform module **terraform-intel-aws-mysql** and being called by Ansible module community.general.terraform
2. Playbook **intel_optimized_mysql_server.yml** - 
3. Playbook **intel-optimized-mysql-ico-by-densify.yml** - It executes role called [intel\_optimized\_mysql\_server\_ico\_by\_densify](#input_intel_optimized_mysql_server_ico_by_densify)
5. Playbook **intel_optimized_mysql_server_vpc_creation.yml** - 
6. Playbook **intel_optimized_mysql_server.yml** - 
