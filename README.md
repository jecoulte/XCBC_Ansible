Simple playbooks to make XCBC easier

Ansible handles post-Rocks installation configuration.

Currently working:

 -- install the XSEDE yum repo for future updates (maybe a bad idea!)

 -- Configure basic Torque queue
 
Currently NOT Working:

 -- YUM module fails in Rocks

 -- Current yum\* playbooks have ugly workarounds (yum2) or failure examples