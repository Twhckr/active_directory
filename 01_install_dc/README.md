# 01 Installing the Domain Controller


1. Use 'sconfig' to:
    - Change the hostname
    - Change the IP address to static
    - Change the DNS server to the local DC

2. Install the Active Directory Windows Feature

'''shell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools