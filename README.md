# Networking
*All the commands/cheatsheets related to networking(cisco)*

## Obtaining Hardware Information of a network Adpater 

`Get-NetAdapterHardwareInfo `

## Obtaining the IP version of a network adapter
```
(Get-NetIPInterface) | Select-Object InterfaceAlias,AddressFamily

; Get-NetIPInterface: It gets an IP interface that includes IPv4 and IPv6 addresses, and the associated address configuration for the IP interfaces.
Select-Object: It selects specified properties of an object. Here, it is InterfaceAlias and AddressFamily. 
```
## Obtain information about Different IP versions
```
Get-NetIPV4Protocol
Get-NetIPV6Protocol
```
 
## Obtain information about Net Firewall profile
```
Get-NetFirewallProfile
```
## Info about current connection statistics of TCP 
```
Get-NetTCPConnection
```

## Info about current connection statistics of UDP
```
Get-NetUDPEndPoint
```

## Get the TCP settings 
```
Get-NetTCPSetting
```
## Get the UDP settings
```
Get-NetUDPSetting
```
## Get Information about the  TCP Ports
```
Get-NetTCPConnection
```
## Get Information about the UDP Ports
```
(Get-NetUDPEndPoint).LocalPort
```
## Get Information about DNS
```
Get-DnsClient
```
## Obtain ARP cache
```
Get-NetNeighbor
```
## Obtain the IP Route Information from the IP Routing Table
```
Get-NetRoute
```
## Listing the Status of the Interfaces in a Switch
```
Entering the <ip> address and <port> in putty ssh clinet and connection type .
When terminal windoes ids prompted, enter the en to enter into the command mode and shoe interfaces status .
```

