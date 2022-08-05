# Veeam

Veeam Software is a privately held US-based information technology company owned by Insight Partners that develops backup, disaster recovery and modern data protection software for virtual, physical and multi-cloud infrastructures. 

## VeeamZIP

VeeamZIP is similar to a full VM backup. The VeeamZIP job always produces a full backup file (VBK) that acts as an independent restore point. You can store the backup file in a backup repository, in a local folder on the backup server or in a network share.

## Creating VeeamZIP Backups

* In the Veeam Backup & Replication console, open the Inventory view and select Nutanix AHV at the inventory pane.
* At the working area, select the required VM or VMs (press and hold CTRL to select several VMs) right-click and select VeeamZIP.
* Select the repository where the VeeamZIP backup will be stored. You can select any repository added to Veeam Backup & Replication infrastructure or choose to store the VeeamZIP backup on a local or shared folder.
* Click OK and wait for the VeeamZIP job to finish.

## Quick Migration (VMware)

Quick Migration lets you migrate live VMs between hosts or datastores without requiring clusters, shared storage or advanced functionality that is not available in lower-level hypervisor editions. Quick Migration works well even in environments with slow or high latency connections that prevent VMware vMotion and Hyper-V Live Migration from working!



##  TYPES OF BACKUP

Each backup program has its own approach in executing the backup, but there are four common backup types implemented and generally used in most of these programs: full backup, differential backup, incremental backup and mirror backup.

## Things I want to know more about
What is the difference between backup and replication?
