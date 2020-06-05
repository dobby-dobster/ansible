Contains ansible code to configure my (Mint) Ubuntu laptop with required packages, configuration etc. This includes installing Docker and some containers.

Contains setup are:
- Jenkins
- Portainer

**Usage**

Extra var is used as this playbook runs against localhost and python apt errors are otherwise seen.

> ansible-playbook local.yml -K -e ansible_python_interpreter=/usr/bin/python

or

> sh go.sh
