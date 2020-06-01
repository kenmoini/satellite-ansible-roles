# enable-rhsm-repo

Ansible Role to enable repositories on Red Hat Enterprise Linux (RHEL) systems via Red Hat Subscription Manager

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

repository_name: ["rhel-{{ ansible_distribution_major_version }}-server-rpms"]
```

## Parameter Examples in Satellite

Set as a type of Array.

### Basic 
`["rhel-{{ ansible_distribution_major_version }}-server-rpms", "rhel-{{ ansible_distribution_major_version }}-server-satellite-tools-6.7-rpms", "rhel-{{ ansible_distribution_major_version }}-server-insights-3-rpms"]`

### Complete
`["rhel-{{ ansible_distribution_major_version }}-server-rpms", "rhel-{{ ansible_distribution_major_version }}-server-extras-rpms", "rhel-{{ ansible_distribution_major_version }}-server-optional-rpms", "rhel-{{ ansible_distribution_major_version }}-server-insights-3-rpms", "rhel-{{ ansible_distribution_major_version }}-server-satellite-tools-6.7-rpms"]`