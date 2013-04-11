doppler
=======

An openstack monitoring service.

While there exist many application level monitoring services, this one is going to be designed for integration into an openstack IaaS cloud.

It's not clear weather (sic) or not this is the right direction to go, but I really wanted a project to learn the low-level openstack details.

## Current ideas:
* Run an agent next to the compute service that can monitor the hypervisor
 * Should be pluggable (i.e. user has dynamic control of what is monitored)
* Publish monitoring messages via own bus 
* Potentially store in swift 
