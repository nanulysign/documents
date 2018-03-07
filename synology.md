## QuickConnect ##
QuickConnect allows client applications to connect to your Synology NAS via the Internet without the hassle of setting up port forwarding rules. QuickConnect can also work with Synology-developed packages, such as Audio Station, Video Station, Download Station, Surveillance Station, Photo Station, File Station, Note Station, CMS, Cloud Station, and mobile applications.

To enable QuickConnect:
Go to Control Panel > QuickConnect > General.
Check Enable QuickConnect.
Enter your existing Synology Account information or register a new account.
Specify a new QuickConnect ID. Make sure it is easy to remember, so you will be able to access your Synology NAS anytime.
Click Apply.
Note:
A custom QuickConnect ID can include letters, numbers, and hyphens ("-"), and must start with a letter.

To enhance QuickConnect connectivity:
Your Synology NAS offers advanced options to make the QuickConnect access more adaptable to different network environments.

Go to Control Panel > QuickConnect > Advanced.
Select the options below to suit your needs:
Enable QuickConnect relay service: Your QuickConnect connection will be relayed via Synology Relay Server when direct QuickConnect access to the Synology NAS is not possible under the current network environment.
Automatically create port forwarding rules: When your Synology NAS is under a UPnP-enabled router, the router will be informed to create port forwarding rules for QuickConnect.
Click Apply.
Note:
Relayed QuickConnect connection may be slow due to longer network latency.
When the router is allowed to create port forwarding rules for QuickConnect, the Synology NAS may be exposed to security risk.
To enable/disable QuickConnect for specific applications/services:
Go to Control Panel > QuickConnect > Advanced.
Select the applications/services you want to enable QuickConnect for.
Click Apply.
Note:
For better QuickConnect performance, it is recommended that you go to Control Panel > External Access > Router Configuration to configure port forwarding for each service:

DSM: 5000 (HTTP); 5001 (HTTPS)
Photo Station: 80 (HTTP); 443 (HTTPS)
Cloud Station：6690
Troubleshooting
If you see the Network error occurred message, this means the QuickConnect service has stopped due to network errors. Please check the following:

Your Synology NAS is connected to an active network (at Control Panel > Network > Network Interface).
The DNS server and default gateway settings are properly configured (at Control Panel > Network > General).
Make sure the Synology NAS can access the Internet using the following destination ports: 80, 443, 8888.
When the network errors are fixed, the QuickConnect service should resume automatically within a few minutes.

