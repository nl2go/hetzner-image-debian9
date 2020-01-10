# hetzner OS image for debian 9 

A provisioner for a vagrant box in order to create an OS image for debian 9 that
can be used with the hetzner installimage tool.

## Notes

hetzner offers a standard image for debian 9. Unfortunately it does not include support
for the latest intel network adapters used dedicated hosts of PX series (and probably others).