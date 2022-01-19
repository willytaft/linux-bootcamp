# Lab 3: Manage Azure disks with the Azure CLI

1. Default Azure disks  ✔
2. Azure data disks  ✔
3. VM disk types  ✔
4. Launch Azure Cloud Shell  ✔
5. Create and attach disks  ✔
6. Prepare data disks  ✔
7. Take a disk snapshot  ✔

### Notes:
 quickstart guide below has great step-by-step guide for completing the tasks. This also includes further instruction on how to restore a vm from a disk that was created via the snapshot. 

az disk create \
   --resource-group myResourceGroupDisk \
   --name mySnapshotDisk \
   --source osDisk-backup
   
Quickstart: Manage Azure disks
* https://docs.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-manage-disks

Quickstart for Bash in Azure Cloud Shell
* https://docs.microsoft.com/en-us/azure/cloud-shell/quickstart 

