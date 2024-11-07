##INFT1205 – Data Communications and Networking II Capstone Project - Winter 2024

## Course: 202441.13909-INFT-1205-18 - Data Comm and Networking 2

**Durham College, Winter 2024 Semester**

### Course Description
This course is the second of three courses that are aligned to prepare the student towards the objectives of the Cisco Certified Network Associate (CCNA) accreditation. This course advances the learners' knowledge of the operation of routers and switches in small networks. It will also introduce the student to wireless local area networks (WLANs) and network security concepts. By the end of this course, the learner will be able to configure advanced functionality in routers and switches. They will also be able to perform basic troubleshooting of these components. Using security best practices, they will be able to troubleshoot and resolve common protocol issues in both IPv4 and IPv6 networks.

### Course Learning Outcomes
Students receiving credit for this course will have reliably demonstrated their ability to:
1. Implement, manage, maintain and troubleshoot VLANs, trunking and configure inter-VLAN routing on Layer 3 devices.
2. Explain how Layer 2 switches forward data and how STP enables redundancy in a Layer 2 network.
3. Configure, manage, maintain and troubleshoot link aggregation in a switched network and explain how FHRPs provide default gateway services in a redundant network.
4. Implement DHCPv4 and DHCPv6 to operate across multiple LANs.
5. Explain how WLANs enable network connectivity. Implement a WLAN using a wireless router and a WLC.
6. Configure and troubleshoot static and default routes for IPv4 and IPv6.
7. Explain how routers use information in packets to make forwarding decisions.
8. Explain how vulnerabilities compromise LAN security. Configure devices using security best practices to mitigate LAN attacks.

### Essential Employability Skill Outcomes (ESSO)
This course will contribute to the achievement of the following Essential Employability Skills:
- Communicate clearly, concisely, and correctly in the written, spoken, and visual form that fulfills the purpose and meets the needs of the audience.
- Respond to written, spoken, or visual messages in a manner that ensures effective communication.
- Execute mathematical operations accurately.
- Apply a systematic approach to solve problems.
- Use a variety of thinking skills to anticipate and solve problems.
- Locate, select, organize, and document information using appropriate technology and information systems.
- Analyze, evaluate, and apply relevant information from a variety of sources.
- Show respect for the diverse opinions, values, belief systems, and contributions of others.
- Interact with others in groups or teams in ways that contribute to effective working relationships and the achievement of goals.
- Manage the use of time and other resources to complete projects.
- Take responsibility for one's own actions, decisions, and consequences.

## Capstone Project Overview
In this project activity, you will demonstrate your ability to:
- Design and implement an IPv4 VLSM addressing scheme that fulfills the requirements.
- Use VLAN segmentation and inter-vlan routing.
- Implement Ether-channel to increase the bandwidth.
- Configure and verify static route.
- Implement DHCPv4.
- Secure the LAN using switchport security.
- Design network infrastructure based on the requirements and document in detail.
- Implement an operational network based on your network design.
- Explain your implementation and demonstrate its operation.
- Produce documentation of your testing and network configuration for use by others to maintain and expand the network.

## Project Requirements
- Replace `xxx` in the suggested IP addresses with the last 2 digits of a student ID of one of your teammates.
- Utilize the physical equipment provided in rooms H-218 and H-166B. You may need to employ multiple pods to meet the requirements. Do not use Packet Tracer.
- Use POD PC or your personal laptops connected via network cables to test and verify your implementation.
- Create topology using Visio or an equivalent tool. Ensure appropriate icons/devices/media type are used in your topology diagram.

## Project Design, Addressing, and Implementation
Teckky Inc., a company specializing in detecting and mitigating fraud in digital commerce, operates within a two-level building situated in Oshawa (Building 1). Due to their successful endeavors in assisting eCommerce stakeholders across Canada, the organization is now expanding and acquiring an additional building (Building 2) adjacent to their primary site. 

### Design Criteria
- **Network Addressing:** The organization uses the private IP address space of 172.30.xxx.0/23 for IPv4 addressing. This private IP assignment will be distributed across all LAN segments using VLSM.
- **Departments and Hosts:**
  - **Building 1:**
    - IT: 122 hosts
    - Customer Support: 55 hosts
    - Sales and Marketing: 50 hosts
  - **Building 2:**
    - Management: 30 hosts
    - HR & Accounting: 52 hosts
    - System Admins: 60 hosts
    - Purchasing: 50 hosts
    - Legal: 20 hosts

### Implementation
- **VLAN Segmentation:** VLANs will be used to segment different departments.
- **Ether-Channel:** Implement ether-channel to increase bandwidth between buildings.
- **Static Routing:** Configure static routes and floating static routes for redundancy.
- **DHCPv4:** Implement DHCPv4 for dynamic addressing in the IT department (Building 1) and HR & Accounting department (Building 2).
- **Network Security:** Configure switchport security, encrypted passwords, restrict console and VTY access, allow only SSHv2 connections, disable AUX port access, and configure a banner warning.

### Network Verification
1. Validate connectivity between all networks and ISP.
2. Validate static routing functionality using appropriate routing tables and ping outputs.
3. Document and verify VLAN Segmentation and Inter-VLAN routing.
4. Document and verify DHCPv4 configuration.
5. Document and verify EtherChannel.

## How to Use This Repository
This repository contains all the files and documentation for the capstone project. Each component of the project is in its respective directory with all necessary files. Below is a brief guide on how to navigate through the repository:

- Clone the repository to your local machine using the following command:
  ```bash
  git clone <repository-url>
  ```
- Navigate to the specific project component directory to view the files.
- Follow the instructions provided in each directory to understand the implementation and configuration details.
