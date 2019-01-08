# zerodownsw-update
Update files for ZeroDown Software
***********************************************
*    ZeroDown Software Update Utility
*
***********************************************

2018-12-30

This update package contains <*> files

update.sh	update script to update from version 8.05 and prior
zds-usr.tar	update pacakge for ZeroDown Software
zds-etc.tar	update package for ZeroDown Software system files

***********************************************
*      Instructions
***********************************************

1.)	Download the update utility

zdsupdate.tar 

2.)	Unpack the compressed update utility scripts and files

tar xvf zdsupdate.tar

3.)	Run the update sxript from an elevated user

sudo ./update.sh

4.)	Restart the services

sudo zds-ui restart
sudo zerodown restart
