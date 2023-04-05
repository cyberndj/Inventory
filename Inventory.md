[MSP]  
{Name, Contract#, $/Mo, Services Included, Notes}

[ISP]  
{Vendor, Download/Upload, $/Month, Account#, Circuit#, MSP-Managed, Notes}

[Cloud]  
{Role, Company, $/Month, MSP-Managed, Notes}  
Role=Web-Hosting, O365, Azure, AWS}  

[Networking]  
{Role, Vendor, Model, SW Version, Count, Support Contract, SN(s), MSP-Managed, MSP-Owned, Notes}  
Roles=Firewalls, Routers, Switches, Access Points, VPNs, Network Appliances (ie. Wireless Controllers)  

[Servers]  
{Role, Vendor, Model, OS, Count, Support Contract, SN(s), MSP-Managed, MSP-Owned, Notes}  
Roles=Physical, VM, Container (Docker/Kubernetes/LXC)  

[Storage]  
{Type, Vendor, Model, OS, Count, Support Contract, SN(s), MSP-Managed, MSP-Owned, RawAmount, Access-Method, Notes}  
Type=NAS, SAN, FC, FCoE, Direct-Attached  
Access-Method=NFS, CIFS/SAMBA, iSCSI, CEPH  

[Voice]  
{Type, Vendor, Model, Version, Count, Support Contract, SN(s), MSP-Managed, MSP-Owned, Notes}  
Type=PBX, Phone, ATA, Server

[PCs]  
{Type, Vendor, Model, OS, Count, Support Contract, SN(s), MSP-Managed, MSP-Owned, Notes}  
Type=Desktop, Laptop, VM  

[Printers]  
{Type, Vendor, Model, Count, Support Contract, SN(s), MSP-Managed, MSP-Owned, Notes}  
Type=Label, Paper, Receipt  

[Software]  
{Type, Vendor, Product, Version, Support Contract, License, On-Server(s), MSP-Managed, MSP-Owned, Notes}  

