# Contip Network Segmentation and Access Control Lab

## Project Overview

This project demonstrates the design and implementation of a segmented enterprise network using Cisco Packet Tracer.

The network consists of three departments:

- IT
- HR
- Sales

Each department operates on a separate subnet, while centralized DHCP and DNS services are hosted within the IT network.

The project uses extended Access Control Lists (ACLs), DHCP relay, DNS, subnetting, and inter-network routing to control communication between departments.

## Case Study

Contip is a fictional organization with three departments: IT, HR, and Sales.

The company requires each department to operate on a separate network while sharing centralized infrastructure services such as DHCP and DNS.

The initial business requirement was to restrict HR from accessing IT resources while allowing Sales to communicate with the IT department. HR still needed access to essential services such as DHCP and DNS.

After implementing the original requirement, a second security scenario was introduced to demonstrate a stronger least-privilege approach.
### Scenario 1 - Original Business Requirement

- HR is restricted from accessing IT resources.
- HR is allowed to use the centralized DHCP and DNS services.
- Sales is allowed to communicate with the IT network.

### Scenario 2 - Enhanced Network Segmentation

- HR is restricted from accessing IT resources.
- Sales is also restricted from accessing IT resources.
- Both HR and Sales retain access to approved DHCP and DNS services.

This second scenario demonstrates how ACLs can be modified to enforce tighter network segmentation without disrupting essential infrastructure services.
