Introduction
=====

.. _scope:

Scope and Objective
------------

With the ITS-FMS interface, a set of C-ITS use cases, based on the use cases defined by the Talking Traffic project, are being linked to logistics IT-systems (such as Fleet Management Systems), with a specific focus towards logistics operators. 
The set of use cases involve:
*   Smart traffic jam warnings;
*   Road hazard warnings;
*   Early warning messages from emergency and rescue services;
*   Information provision from traffic signals (iVRI)
*   Priority allocation at traffic signals;
*   Provisioning of information from variable message signs above the road;
*   ...

This set of applications is characterized by low-latency services that make use of cellular communication services. 
They are called ITS (intelligent transport systems) services within this context and form the scope of what is specified in this document.
Currently, on the Connected Transport Corridors, several of these ITS services are already provided in-truck via a 4G wireless data connection via stand-alone smartphone apps, which communicate the route and position of the truck directly to a cloud service provider. 
This ITS-FMS interface description is aimed at the same kind of information services, however, using the already built-in on-board units (OBUs, fleet management systems) in the trucks.  


Target group of this document
----------------
This document is intended for logistics IT-suppliers wanting to integrate Intelligent Transport Systems-services, as served by ITS Cloud Service Providers, in their own software solutions. 

Fleet Management System to ITS Cloud Service Provider integration architecture – high level overview
----------------
In the diagram below, a high-level architecture can be found between the ITS Cloud Service Providers and FMS-providers:
.. figure:: ArchitectureCSP-FMS.png
   :alt: Architecture of CSP

Figure 1: High Level architecture of CSP and FMS ecosystem – the ITS-FMS interface is situated between Cloud Service Provider and the Fleet Management System as information providers (indicated by a red dashed circle)
