# pure-ansible-livestream
This livestream event is showcasing the development of Ansible playbooks to use in automation of Pure Flash Arrays. In this excercise we build up from using ansible to gather information from the arrays, to building a self-service function to snap, replicate, and restore a volume.

## Environment
![Image of Lab Environment](images/diagram.png)
The use case involves initating a snapshot in siteA, replicating that snapshot to siteB, restoring that snapshot to a volume on the Pure Flash Array in Site B. 