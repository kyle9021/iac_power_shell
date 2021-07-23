# PCEE IaC Powershell Script

For Windows Users - Confirmed working on July 23rd 2021. Please confirm your download is after this date. 

I wrote this tool for the IT community who are actively working with IaC files and who have access to an instance of Prisma Cloud Enterprise. This avoids the need to install docker, manage python libraries, or even use the terminal (after install). Simple implementations, without the risk of additional libraries or software. There are no dependencies for this script other than powershell. 

## Notes

You may need to run this with local admin level permissions. (Right click script and choose run as admin)

## Purpose

It will scan IaC project directories or directories which contain IaC files and provide you with a summary of the vulnerabilities contained within those files. It will also create an entry for the scan in the Prisma Cloud Enterprise Edition Console under Inventory > DevOps


## Instructions
Copy the script and/or download it. 

If you copy the script from the raw code. Ensure you save it with `.ps1` extension

Double-click your script and enter the information as you are prompted in the powershell window that will pop-up. 

Optionally you may want to assign the variables so you don't need to enter that information every time you run it. If you decide to go this route, ensure you take appropriate steps to secure this script. 


