# DATA BACKUP AND RESTORING USING RPA
## Team Number: 24 
Team Members <li>K.Piraivendhan(15CSA44) - Retrieving process, Creating and backup from the Orchestrator process.</li> <li>N.Revathi (15CSA49) - Mail Automation</li> <li>R.Sreerag (15CSA57) - Storing the data files in the Orchestrator process</li> 

## ABSTRACT
Data backup is the process of backing up the data, refers to copying the data into an archive file of computer data so it may be used to restore the original after a data loss event. Backups have two distinct purposes. The primary purpose is to recover data after its loss, it can be data deletion or corruption. Data loss can be a common experience of computer users while transferring the data. The secondary purpose of backups is to recover data from an earlier time, according to a user-defined data retention policy, typically configured within a backup application for how long copies of data are required.These processes can be fully automated with the RPA solutions by providing them with the required credentials, source and destination details for the whole task to be automated.

## MODULE SPLITUP
<ul>

## Module 1: Mail automation
   <li>The input file is received from the mail.</li>
   <li>The file gets downloaded and saved in the respective folder, and if the respective folder is not available it will automatically        creates the folder and save in it.</li>
   
## Module 2: Backup process
   <li>The data from the multiple number of files are being read and stored in a separate excel file.</li>
   <li>Then that excel file gets stored in the Orchestrator queue for backup.</li>
   
## Module 3: Restoring process
   <li>Then we backup the files from Orchestrator.</li> 
   <li>Then using the decision flow it checks for the file, if the file is not found it will return as "file not found" or else it will          return the backup file and it will store it in a separate excel file. </li>
   
## Module 4: Orchestrator connection
   <li>The bot gets connected to the Orchestrator using the generated machine key and Orchestrator URL.</li>
   <li>The backup process is done on daily basis.</li>
   <li>The restoring process is done while triggering the bot.</li></ul>
 
## PROPOSED SYSTEM
In our proposed system, the data from the different sources are collected on a daily basis through mail. The bot will be trained to the process of extraction of data based on condition. The process will be idle until the admin triggers the bot using orchestrator. After the triggering factor, the files from the different sources are collected as a master file. The backup process is done for the master file.
After the backup process, the restoring process is executed.

## ADVANTAGES OF PROPOSED SYSTEM
<li>It can help scale resources and meet the need of growing business data.</li>
<li>Boost efficiency and effectiveness of the system.</li>

## FUTURE ENHANCEMENTS
<li>Cloud storage could be used.</li>
<li>High level security is enhanced.</li>

## PROJECT STATUS
<li>Project is completed(100%).</li>

