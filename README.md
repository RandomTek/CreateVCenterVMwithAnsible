# CreateVCenterVMwithAnsible

Create a Virtual Machine in vCenter With Ansible

The createvm.yml playbook creates a new virtual machine named "myvm" with 4 CPUs, 4096 MB of memory, and a 10 GB thin-provisioned disk. It also attaches an ISO image located at "/path/to/myiso.iso" to the CD-ROM drive of the virtual machine.

You will need to replace the values of the variables in vars.yml file with the appropriate values for your environment. Once you run this playbook, Ansible will create the virtual machine in the remote vCenter and power it on.

In vras.yml replace the following with your own.
MyVcenterIpOrFQDN, MyDatacenterName, MyClusterName, MyVMDisplayName, MyDatastoreName, MYFolderName, MyVmMacAddress.

in vcenter-creds.yml the vcenter login credentials will be stored, so it's best to encrypty the file.
