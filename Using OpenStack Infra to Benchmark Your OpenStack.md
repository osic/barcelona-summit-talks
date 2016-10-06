# Status: Draft - nothing concrete  
## Talk Details  
Tue 25  3:55pm-4:35pm  
Using OpenStack Infra to Benchmark Your OpenStack  
Ops Tools  
OpenStack Summit 2016 - Barcelona  
October 24-28  
Original Brainstorm - https://etherpad.openstack.org/p/infra-session-barcelona  

# Abstract  


# General Outline  
## Introduction - 5 minutes  

### Bios  
Issac - Intel  
Melvin - Rackspace  

### What is OSIC  
> The OpenStack Innovation Center (OSIC), a joint investment by Rackspace and Intel, aims to accelerate the enterprise adoption of OpenStack through continuous enhancements to the OpenStack platform to support increasingly robust workloads. In parallel, the Center seeks to foster open source principles, ensuring that efforts align with the goals of the OpenStack Foundation and that all work is contributed upstream.  

### Why OSIC
* Grow the number of OpenStack contributors  
* Increase upstream contributions to OpenStack  
* Enable community-wide OpenStack innovation at unmatched scale  

## Overview - 15 minutes
### Why Infra
* Workload generation  
    * 
* Why not Rally?  
* Why not Perfkit?
* What are benefits to you, we know the benefit to Infra?

### Workflow of Infra (not sure what this means entirely)
_we need more detail here, hoping to have Michal expand on this_  

### Reading and understanding project config  

If you did not want to setup infra yourself and run it yourself, what are some sensibile defaults to have in place?
* Networking  
* Hardware Specs  
* IP Addressing  
* Personnel  

### When should you contact infra team  
_what is the stop point where one would need to have infra come in should they have resources to offer_  

## What We Deployed - 5 minutes  
### Breakdown of environment  
* Cloud1  
  * Long standing  
  * Offers more resources  
  * Digests findings  
* Cloud8  
  * Development / Testing focused  
  * Not expected to be available for long  

_charts since infra has been deployed (should probably grab from cloud1)_  

## Issues and Remediations (Conclusion) - 10 minutes  
1. IPv6  
    * What was the issue  
    * How was issue determined to actually be an issue  
    * What steps were used to troubleshoot  
    * What was the remediation (permanent or not)  
2. raw vs qcow2  
    * What was the issue  
    * How was issue determined to actually be an issue  
    * What steps were used to troubleshoot  
    * What was the remediation (permanent or not)  
3. ceph (raw vs qcow2, journal size, etc)  
    * What was the issue  
    * How was issue determined to actually be an issue  
    * What steps were used to troubleshoot  
    * What was the remediation (permanent or not)  
4. probably more stuff here, check with Ala (general framing for each item)  
    * What was the issue  
    * How was issue determined to actually be an issue  
    * What steps were used to troubleshoot  
    * What was the remediation (permanent or not)  

## Credits  
* OpenStack Infra Team Members
  * Paul Belanger (pabelanger)
  * Jeremy Stanley (fungi)  
* OSIC
  * Isaac Gonzalez - Intel (izaakk)  
  * Melvin Hillsman - Rackspace (mrhillsman)  
  * Ala Raddaoui - Intel (raddaoui)  
  * Kevin Carter - Rackspace (cloudnull)  
  * James Denton - Rackspace (jamesdenton)  
  * Michal Jastrzebski - Intel (inc0)  
  * Dale Bracey - Rackspace (irtermite)  
  * Jonathan Almaleh - Rackspace (sup)  

## Q&A
_we will not have Michal available to provide a lot of the technical answers_
* Reach out via contact details provided here
