[MSP]
{Name, Contract#, $/Mo, Services Included}

[ISP]
{Vendor, Download/Upload, $/Month, Account#, Circuit#, MSP-Managed}

[Networking]
{Role, Vendor, Model, SW Version, Count, Support Contract, SN(s), MSP-Managed, MSP-Owned}
Roles=Firewalls, Routers, Switches, Access Points, VPNs, Network Appliances (ie. Wireless Controllers)

[Servers]
{Role, Vendor, Model, OS, Count, Support Contract, SN(s), MSP-Managed, MSP-Owned}
Roles=Physical, VM, Container (Docker/Kubernetes/LXC)

[Storage]
{Type, Vendor, Model, OS, Count, Support Contract, SN(s), MSP-Managed, MSP-Owned, RawAmount, Access-Method}
Type=NAS, SAN, FC, FCoE, Direct-Attached
Access-Method=NFS, CIFS/SAMBA, iSCSI, CEPH 

[PCs]
{Type, Vendor, Model, OS, Count, Support Contract, SN(s), MSP-Managed, MSP-Owned}
Type=Desktop, Laptop, VM

[Software]
{Type, Vendor, Product, Version, Support Contract, License, On-Server(s), MSP-Managed, MSP-Owned}
