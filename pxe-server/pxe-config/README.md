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

Author Information
------------------

Zukias.
