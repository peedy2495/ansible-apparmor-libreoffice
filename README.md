# ansible-apparmor-libreoffice - correct apparmor profile

This ansible role is for modifiying the libreoffice apparmor policy.

Modifications:
- access to the socket for Assistive Technology Service Provider Interface (AT-SPI)
- access to foreign files on removable storage (/media/*) 

related to: Ubuntu 22.04 LTS