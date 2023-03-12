# CreateVCenterVMwithAnsible
Create a Virtual Machine in vCenter With Ansible

Replace in vras.yml the following with your own.
MyVcenterIpOrFQDN
MyDatacenterName
MyClusterName
MyVMDisplayName
MyDatastoreName
MYFolderName

in vcenter-creds.yml the vcenter login credentials will be stored, so it's best to encrypty the file.
ansible-vault create vcenter_creds.yml
