# CMPG325-2026-053

## Computer Networks Project

### Client
Mothusi Bed & Breakfast (Potchefstroom)

### Client ID
CL-053

### Project ID
CMPG325-2026-053

### Industry
Hospitality

### Addressing Block
192.168.31.0/24

### Assigned Networking Challenge
Static Routing (multi-router path control)

### Design Constraint
After-hours cleaning and security contractors need limited wireless access.

### Change Request
CR13 – Public self-service kiosk at reception with Internet-only access.
## Phase 2 – Client Implementation Review

 Working Packet Tracer network implementation
 Assigned challenge: Static Routing
 Contractor wireless network implemented
  Public self-service kiosk implemented and isolated
  Static routing configured between routers
  Network connectivity testing completed
  Testing evidence uploaded

### Testing Evidence

 Kiosk → Internet Server: 4/4 successful
 Kiosk → Admin PC: 100% blocked
 Kiosk → Staff PC: 100% blocked
 Admin PC → Staff PC: 4/4 successful
 Contractor Laptop → Contractor Gateway: 4/4 successful
#  Phase 3

## Project Overview

This repository documents the design, implementation, configuration and testing of the proposed network for Mothusi Bed & Breakfast using Cisco Packet Tracer.

## Project Objectives

- Design a network using the `192.168.31.0/24` address block.
- Configure three interconnected routers.
- Implement static routing between network subnets.
- Separate administration, staff, contractor Wi-Fi and public kiosk networks.
- Apply access control lists (ACLs) to restrict specified traffic.
- Test connectivity, routing and network access restrictions.
- Provide evidence of the implementation and technical decisions.

## Network Design

The design includes separate subnets for administration, staff, contractor Wi-Fi and the public self-service kiosk. Three routers connect the network segments and a simulated server network.

The logical topology, physical topology, client requirements and IP addressing plan form part of the design evidence.

## Phase 3 Technical Challenge

The main technical challenge is implementing and verifying static routing across three interconnected routers. ACLs are also used to restrict contractor and kiosk access to specified internal subnets.

## Testing and Verification

Testing includes:

- Administration-to-staff connectivity.
- Contractor connectivity to its gateway.
- Contractor access restrictions to administration and staff.
- Public kiosk restrictions to specified internal subnets.
- Connectivity to the simulated server.

Detailed results and screenshots will be provided in the testing evidence and technical report. Initial ping timeouts are distinguished from repeat-test results.

## Portfolio Deliverables

This repository will contain:

1. Client requirements and network design.
2. IP addressing plan and topology diagrams.
3. Cisco Packet Tracer simulation file.
4. Router configuration, static routing and ACL evidence.
5. Connectivity and security testing screenshots.
6. Final Phase 3 technical report.
7. Presentation slides and video demonstration details.

## Submission Checklist

- [ ] Network design evidence
- [ ] Final Packet Tracer file
- [ ] Static routing and ACL configuration evidence
- [ ] Connectivity and access-control test screenshots
- [ ] Final technical report
- [ ] Presentation slides
- [ ] Video demonstration or accessible video link

## Conclusion

This portfolio records the network design and implementation work for Mothusi Bed & Breakfast. The final submission should include the simulation, supporting technical documentation and evidence needed to evaluate the network functionality and security controls.
## Milestone 1
This repository contains the Client Requirements, Physical Topology, Logical Topology and IP Addressing Plan for the proposed network.
