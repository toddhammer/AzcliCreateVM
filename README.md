# AzcliCreateVM

I created this to crank our VM that I often create from day to day. 
If you need something special, you'll need to go to the Marketplace.

This script will help you quickly create a VM from one of 4 publishers: 
MicrosoftWindowsServer
SUSE
Canonical
RedHat

3 of these 4 also select an offer based on the publisher: 
    1) imagePublisher="MicrosoftWindowsServer"; imageOffer="WindowsServer"; break;;
    2) imagePublisher="SUSE"; break;;
    3) imagePublisher="RedHat"; imageOffer="RHEL"; break;;
    4) imagePublisher="Canonical"; imageOffer="UbuntuServer"; break;;
    
The best way to use this is run it from Cloudshell. 

This will ask you for the following: 
resource group
VM Name
VM admin username
VM admin password

Then it creates a VM sized at Standard_DS2 and a 128Gb OS disk. 
 
 If you don't like these defaults, you can change the script. 

