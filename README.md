# satellite-ansible-roles

A series of Ansible Roles to import into Red Hat Satellite to make your life easier.

## How to use

1. Import the role to your Satellite host: https://access.redhat.com/documentation/en-us/red_hat_satellite/6.7/html/administering_red_hat_satellite/chap-red_hat_satellite-administering_red_hat_satellite-managing_ansible_roles#sect-Red_Hat_Satellite-Administering_Red_Hat_Satellite-Importing_Ansible_Roles
2. Import the variables: https://access.redhat.com/documentation/en-us/red_hat_satellite/6.7/html/administering_red_hat_satellite/chap-red_hat_satellite-administering_red_hat_satellite-managing_ansible_roles#sect-Red_Hat_Satellite-Administering_Red_Hat_Satellite-Importing_Ansible_Variables
3. Use on managed hosts
4. ??????
5. PROFIT!!!!!1

## How to Contribute

Contributions from the community are more than welcome, and are encouraged.  Building Ansible Roles to atomically handle specific tasks is an easy way to get started with automation, documentation, and open-source!

You don't need to be a programmer or YAML engineer to contribute - anything helps, from documentation improvements, discussions and suggestions in the Issues tracker, to helping organize actions and things.

The main branch is the ***master*** branch of course, and this repository uses feature branching otherwise to keep merged code organized.

For these steps, we'll assume that I'm using the ***examplePerson*** GitHub user and contributing a new role called ***set-ntp*** - switch with your own.

1. ***Fork*** this repository: https://github.com/kenmoini/satellite-ansible-roles/fork
2. ***Clone*** it down to your local workstation: `git clone https://github.com/examplePerson/satellite-ansible-roles`
3. Enter the directory: `cd satellite-ansible-roles`
4. Create and switch to a new ***branch***: `git branch -b set-ntp-role`
5. Create a new directory and enter it: `mkdir set-ntp && set-ntp`
6. Create your Ansible Role - feel free to use other Roles as an example and template for your own, just ensure you modify the `meta/main.yml` file to match your authoring information.  We request that all contributions be made under the MIT license to foster Open-Source.
7. **Add** your changes to the Git ledger: `git add .`
8. Provide your **commit message**: `git commit -m "added set-ntp role"`
9. ***Push*** your newly coded branch to your fork: `git push -u origin set-ntp`
10. On GitHub, create a ***Pull Request*** comparing your feature branch to the master branch of the primary repository.
11. Provide as much information about your contribution as possible - documentation of your role and pull request will speed the process.

If you have any issues contributing or any questions, please do not hesitate to say so in the ***Issues tracker***: https://github.com/kenmoini/satellite-ansible-roles/issues