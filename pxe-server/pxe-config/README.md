PXE Server
=========

Install and configure a PXE server.

Requirements
------------

Please notifiy that this role will install and configure the DHCP service on your server.

Roles
------------

- pxe-dependencies : Install dependencies for PXE Server
- pxe-dhcp : Install and configure isc-dhcp-server 
- pxe-config : Configure PXE server with new configuration file and adding lines to some file needed to PXE working


Role Variables
--------------

Settable variable are in /pxe-server/pxe-dhcp/defaults/main.yml.

Variables in that file allow you to custom the basic dhcpd.conf file with your network parameter.

(Variables utilisation exemples) :

- dns_search: exemple.com
- dns_server: your dns server
- network_ip: 192.168.0.0
- network_netmask: 255.255.255.0
- range_min: 192.168.0.50
- range_max: 192.168.0.150
- network_gateway: 102.168.0.1

Author Information
------------------

Zukias.
