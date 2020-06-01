# katello-agent-role

Ansible Role to import into Red Hat Satellite which will auto-configure the Katello/Satellite agent on newly provisioned hosts created from Satellite

## How to use

1. Import the role to your Satellite host: https://access.redhat.com/documentation/en-us/red_hat_satellite/6.7/html/administering_red_hat_satellite/chap-red_hat_satellite-administering_red_hat_satellite-managing_ansible_roles#sect-Red_Hat_Satellite-Administering_Red_Hat_Satellite-Importing_Ansible_Roles
2. Import the variables: https://access.redhat.com/documentation/en-us/red_hat_satellite/6.7/html/administering_red_hat_satellite/chap-red_hat_satellite-administering_red_hat_satellite-managing_ansible_roles#sect-Red_Hat_Satellite-Administering_Red_Hat_Satellite-Importing_Ansible_Variables
3. Use on managed hosts
4. ??????
5. PROFIT!!!!!1

## Pre-defined Variables and Defaults

```
satellite_url: "https://satellite.satellite.labs"
satellite_org_name: "Kemo Labs"
satellite_activation_key: "kemoKey"

satellite_link: "{{ satellite_url }}/pub/katello-ca-consumer-latest.noarch.rpm"
```