# Easy-OU-TO-SCCM
Easy creat collection SCCM based on OU

![Alt Text](https://ivellath.sirv.com/SCCM-TO-OU.gif)

About : 
Easy-SCCM-TO-OU : Is a free tool for Microsoft users, developped by DAKHAMA MEHDI.
This tool help you to create collections based on organizational units in Active Directory, for deploy applications and packages for specific users and devices.
This tool permit to ease work and savec a lot of time.

# PREREQUISITE 

Install module Active-Directory (for server or RSAT for client post)
have the SCCM console installed on the post (Or import file configurationmanager.psd1)

# HOW TO USE 

Open the file .Exe with admin priviliege, if you have two module en red, (Module-AD and Check-PSD1) install it and refresh

to install MODULE-AD :

- On Windows Server
enter this command on powershell : Install-windowsfeature rsat-ad-powershell #(that will take 10 secondes)
