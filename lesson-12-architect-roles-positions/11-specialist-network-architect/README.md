# Network Architect

> **Navigation**: [Back to Lesson Overview](../README.md) | [Previous: Infrastructure Architect](../10-specialist-infrastructure-architect/README.md) | [Next: Integration Architect](../12-specialist-integration-architect/README.md)

---

## 11.1 Role Overview

The **Network Architect** designs network infrastructure including topology, protocols, and connectivity solutions. They ensure reliable, secure, and performant network communication across enterprise environments, data centers, and cloud platforms.

```
┌─────────────────────────────────────────────────────────────────────────┐
│                      NETWORK ARCHITECT POSITION                          │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│                        BUSINESS REQUIREMENTS                             │
│     ┌──────────────┐  ┌──────────────┐  ┌──────────────┐                │
│     │ Connectivity │  │  Performance │  │   Security   │                │
│     │    Needs     │  │     SLAs     │  │ Requirements │                │
│     └──────┬───────┘  └──────┬───────┘  └──────┬───────┘                │
│            │                 │                 │                         │
│            └─────────────────┼─────────────────┘                         │
│                              │                                           │
│                              ▼                                           │
│  ┌──────────────────────────────────────────────────────────────────┐   │
│  │                    NETWORK ARCHITECT                             │   │
│  │                                                                  │   │
│  │   ┌─────────────────────────────────────────────────────────┐   │   │
│  │   │                  NETWORK DESIGN                          │   │   │
│  │   │                                                          │   │   │
│  │   │  ┌─────────┐  ┌─────────┐  ┌─────────┐  ┌─────────┐    │   │   │
│  │   │  │   LAN   │  │   WAN   │  │  Cloud  │  │   SD-   │    │   │   │
│  │   │  │ Design  │  │ Design  │  │ Network │  │   WAN   │    │   │   │
│  │   │  └─────────┘  └─────────┘  └─────────┘  └─────────┘    │   │   │
│  │   │                                                          │   │   │
│  │   │  ┌─────────┐  ┌─────────┐  ┌─────────┐  ┌─────────┐    │   │   │
│  │   │  │Firewall │  │  Load   │  │   DNS   │  │  VPN/   │    │   │   │
│  │   │  │ Design  │  │Balancing│  │  DHCP   │  │ Private │    │   │   │
│  │   │  └─────────┘  └─────────┘  └─────────┘  └─────────┘    │   │   │
│  │   │                                                          │   │   │
│  │   └─────────────────────────────────────────────────────────┘   │   │
│  │                                                                  │   │
│  └──────────────────────────────────────────────────────────────────┘   │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 13.2 Core Responsibilities

### Primary Responsibilities

| Responsibility | Description | Time Allocation |
|----------------|-------------|-----------------|
| **Network Design** | Design LAN, WAN, and cloud network topology | 30% |
| **Security Architecture** | Design network security controls | 20% |
| **Capacity Planning** | Plan bandwidth and growth | 15% |
| **Technology Evaluation** | Assess new networking technologies | 15% |
| **Troubleshooting** | Resolve complex network issues | 10% |
| **Standards & Documentation** | Define network standards | 10% |

### Network Architecture Domains

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    NETWORK ARCHITECTURE DOMAINS                          │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  LAN/CAMPUS                          WAN/CONNECTIVITY                    │
│  ├── Switching Architecture          ├── MPLS Networks                  │
│  ├── VLAN Design                     ├── SD-WAN                         │
│  ├── Spanning Tree                   ├── Internet Connectivity          │
│  ├── Layer 3 Routing                 ├── Direct Connect/ExpressRoute    │
│  └── Wireless (Wi-Fi 6/7)            └── VPN Tunnels                    │
│                                                                          │
│  DATACENTER NETWORK                  CLOUD NETWORKING                    │
│  ├── Spine-Leaf Architecture         ├── VPC/VNet Design                │
│  ├── Fabric Technologies             ├── Transit Gateway                │
│  ├── East-West Traffic               ├── Private Link                   │
│  ├── Overlay Networks                ├── Cloud Interconnect             │
│  └── Network Virtualization          └── Multi-Cloud Networking         │
│                                                                          │
│  SECURITY                            SERVICES                            │
│  ├── Firewall Architecture           ├── DNS Architecture               │
│  ├── Microsegmentation               ├── DHCP/IPAM                      │
│  ├── Zero Trust Network              ├── Load Balancing                 │
│  ├── DDoS Protection                 ├── Proxy/Content Filtering        │
│  └── Network Access Control          └── Network Monitoring             │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 13.3 Day-to-Day Activities

### Typical Week

```
┌─────────────────────────────────────────────────────────────────────────┐
│                   NETWORK ARCHITECT WEEKLY SCHEDULE                      │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  MONDAY                                                                  │
│  ├── 09:00  Network team standup                                       │
│  ├── 10:00  Capacity review meeting                                    │
│  ├── 14:00  Network design review (new office)                         │
│  └── 16:00  Vendor call (SD-WAN provider)                              │
│                                                                          │
│  TUESDAY                                                                 │
│  ├── 09:00  Security architecture review                               │
│  ├── 11:00  Cloud network design session                               │
│  ├── 14:00  Change advisory board                                      │
│  └── 16:00  Network documentation                                      │
│                                                                          │
│  WEDNESDAY                                                               │
│  ├── 09:00  Performance analysis review                                │
│  ├── 11:00  Application team consult (network requirements)            │
│  ├── 14:00  Datacenter network planning                                │
│  └── 16:00  Automation/scripting work                                  │
│                                                                          │
│  THURSDAY                                                                │
│  ├── 09:00  Incident review (network outages)                          │
│  ├── 11:00  Technology evaluation (new firewall)                       │
│  ├── 14:00  DR/BC network planning                                     │
│  └── 16:00  Standards documentation                                    │
│                                                                          │
│  FRIDAY                                                                  │
│  ├── 09:00  Weekly network review                                      │
│  ├── 11:00  Research: New technologies (SASE, etc.)                    │
│  ├── 14:00  Team mentoring                                             │
│  └── 16:00  Planning and roadmap updates                               │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 13.4 Required Skills

### Technical Skills

| Skill Category | Required Proficiency | Examples |
|----------------|---------------------|----------|
| **Routing Protocols** | Expert | BGP, OSPF, EIGRP, IS-IS |
| **Switching** | Expert | VLANs, STP, VxLAN |
| **Firewalls** | Advanced | Palo Alto, Fortinet, Cisco |
| **Cloud Networking** | Advanced | AWS VPC, Azure VNet, GCP |
| **Load Balancing** | Advanced | F5, NGINX, HAProxy, Cloud LB |
| **SD-WAN** | Intermediate | Cisco Viptela, VMware, Fortinet |
| **Wireless** | Intermediate | Wi-Fi 6/7, controllers |

### OSI Model Deep Understanding

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    OSI MODEL - NETWORK ARCHITECT VIEW                    │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  LAYER    NAME           TECHNOLOGIES           ARCHITECT CONCERNS       │
│  ─────────────────────────────────────────────────────────────────────  │
│                                                                          │
│    7     Application    HTTP, DNS, SMTP        App delivery, security   │
│                                                                          │
│    6     Presentation   SSL/TLS, encoding      Encryption, compression  │
│                                                                          │
│    5     Session        NetBIOS, RPC           Connection management    │
│                                                                          │
│    4     Transport      TCP, UDP               Load balancing, QoS      │
│                                                                          │
│    3     Network        IP, ICMP, BGP, OSPF    Routing, subnetting     │
│                                                                          │
│    2     Data Link      Ethernet, VLANs, STP   Switching, segmentation │
│                                                                          │
│    1     Physical       Fiber, copper, Wi-Fi   Cabling, wireless       │
│                                                                          │
│  Network Architects must understand issues at ALL layers                │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 13.5 Key Deliverables

### Primary Artifacts

| Deliverable | Purpose | Audience |
|-------------|---------|----------|
| **Network Architecture Document** | Overall network design | All stakeholders |
| **Network Diagrams** | Physical and logical topology | Operations, security |
| **IP Addressing Scheme** | Address allocation plan | Network team |
| **Security Zone Design** | Segmentation strategy | Security, compliance |
| **Capacity Plans** | Bandwidth projections | Management |
| **Network Standards** | Configuration guidelines | Network engineers |

### Network Topology Diagram Example

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    ENTERPRISE NETWORK TOPOLOGY                           │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│                              INTERNET                                    │
│                                 │                                        │
│                         ┌───────┴───────┐                               │
│                         │   Edge FW     │                               │
│                         │   (HA Pair)   │                               │
│                         └───────┬───────┘                               │
│                                 │                                        │
│                         ┌───────┴───────┐                               │
│                         │   DMZ Zone    │                               │
│                         │  (Web/Proxy)  │                               │
│                         └───────┬───────┘                               │
│                                 │                                        │
│                         ┌───────┴───────┐                               │
│                         │  Internal FW  │                               │
│                         │   (HA Pair)   │                               │
│                         └───────┬───────┘                               │
│                                 │                                        │
│  ┌──────────────────────────────┼──────────────────────────────────┐    │
│  │                       CORE LAYER                                 │    │
│  │         ┌─────────────┐           ┌─────────────┐               │    │
│  │         │   Core-1    │◄─────────▶│   Core-2    │               │    │
│  │         │  (Layer 3)  │           │  (Layer 3)  │               │    │
│  │         └──────┬──────┘           └──────┬──────┘               │    │
│  └────────────────┼─────────────────────────┼──────────────────────┘    │
│                   │                         │                            │
│  ┌────────────────┼─────────────────────────┼──────────────────────┐    │
│  │           DISTRIBUTION LAYER             │                       │    │
│  │  ┌────────────┐  ┌────────────┐  ┌────────────┐                 │    │
│  │  │   Dist-1   │  │   Dist-2   │  │   Dist-3   │                 │    │
│  │  └─────┬──────┘  └─────┬──────┘  └─────┬──────┘                 │    │
│  └────────┼───────────────┼───────────────┼────────────────────────┘    │
│           │               │               │                              │
│  ┌────────┼───────────────┼───────────────┼────────────────────────┐    │
│  │   ACCESS LAYER         │               │                         │    │
│  │  ┌─────┐ ┌─────┐  ┌─────┐ ┌─────┐  ┌─────┐ ┌─────┐              │    │
│  │  │Acc-1│ │Acc-2│  │Acc-3│ │Acc-4│  │Acc-5│ │Acc-6│              │    │
│  │  └─────┘ └─────┘  └─────┘ └─────┘  └─────┘ └─────┘              │    │
│  └──────────────────────────────────────────────────────────────────┘    │
│                                                                          │
│  VLAN SEGMENTATION                                                       │
│  ├── VLAN 10: Corporate Users                                           │
│  ├── VLAN 20: Servers                                                   │
│  ├── VLAN 30: Guest Network                                             │
│  └── VLAN 99: Management                                                │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 13.6 Modern Network Architectures

### SD-WAN Architecture

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    SD-WAN ARCHITECTURE                                   │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│                    ┌─────────────────────────┐                          │
│                    │   SD-WAN Controller     │                          │
│                    │  (Cloud-hosted/On-prem) │                          │
│                    └───────────┬─────────────┘                          │
│                                │                                         │
│         ┌──────────────────────┼──────────────────────┐                 │
│         │                      │                      │                 │
│         ▼                      ▼                      ▼                 │
│  ┌─────────────┐       ┌─────────────┐       ┌─────────────┐           │
│  │   HQ Edge   │       │ Branch Edge │       │ Branch Edge │           │
│  │   Device    │       │   Device    │       │   Device    │           │
│  └──────┬──────┘       └──────┬──────┘       └──────┬──────┘           │
│         │                     │                     │                   │
│         │  ┌─────────────────────────────────────┐ │                   │
│         └──┤        UNDERLAY TRANSPORTS          ├─┘                   │
│            │                                      │                     │
│            │  ┌────────┐  ┌────────┐  ┌────────┐ │                     │
│            │  │  MPLS  │  │Internet│  │  LTE   │ │                     │
│            │  └────────┘  └────────┘  └────────┘ │                     │
│            │                                      │                     │
│            └─────────────────────────────────────┘                      │
│                                                                          │
│  BENEFITS                                                                │
│  ├── Centralized management and visibility                             │
│  ├── Application-aware routing                                         │
│  ├── Automatic failover across transports                              │
│  ├── Zero-touch provisioning for branches                              │
│  └── Direct cloud access (breakout)                                    │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

### SASE (Secure Access Service Edge)

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    SASE ARCHITECTURE                                     │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  USERS                           APPLICATIONS                            │
│  ┌─────────┐ ┌─────────┐        ┌─────────┐ ┌─────────┐                │
│  │ Remote  │ │  Branch │        │  SaaS   │ │  IaaS   │                │
│  │ Workers │ │  Office │        │  Apps   │ │  Apps   │                │
│  └────┬────┘ └────┬────┘        └────┬────┘ └────┬────┘                │
│       │          │                   │          │                       │
│       └──────────┴───────────────────┴──────────┘                       │
│                          │                                               │
│                          ▼                                               │
│  ┌───────────────────────────────────────────────────────────────────┐  │
│  │                    SASE CLOUD PLATFORM                            │  │
│  │                                                                   │  │
│  │  ┌─────────────────────────────────────────────────────────────┐ │  │
│  │  │ NETWORK SERVICES          SECURITY SERVICES                 │ │  │
│  │  │                                                              │ │  │
│  │  │ ┌─────────┐ ┌─────────┐   ┌─────────┐ ┌─────────┐          │ │  │
│  │  │ │  SD-WAN │ │  WAN    │   │  SWG    │ │  CASB   │          │ │  │
│  │  │ └─────────┘ │ Optim.  │   └─────────┘ └─────────┘          │ │  │
│  │  │             └─────────┘                                     │ │  │
│  │  │ ┌─────────┐ ┌─────────┐   ┌─────────┐ ┌─────────┐          │ │  │
│  │  │ │  CDN    │ │ Private │   │  ZTNA   │ │   FWaaS │          │ │  │
│  │  │ └─────────┘ │ Access  │   └─────────┘ └─────────┘          │ │  │
│  │  │             └─────────┘                                     │ │  │
│  │  └─────────────────────────────────────────────────────────────┘ │  │
│  │                                                                   │  │
│  └───────────────────────────────────────────────────────────────────┘  │
│                                                                          │
│  SWG = Secure Web Gateway    CASB = Cloud Access Security Broker        │
│  ZTNA = Zero Trust Network Access    FWaaS = Firewall as a Service      │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 13.7 Career Path

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    NETWORK ARCHITECT CAREER PATH                         │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  ENTRY POINTS                                                            │
│  ┌─────────────────┐  ┌─────────────────┐                               │
│  │    Network      │  │    Systems      │                               │
│  │    Engineer     │  │   Administrator │                               │
│  │   (5+ years)    │  │   (5+ years)    │                               │
│  └────────┬────────┘  └────────┬────────┘                               │
│           │                    │                                         │
│           └──────────┬─────────┘                                         │
│                      ▼                                                   │
│             ┌─────────────────┐                                         │
│             │     NETWORK     │                                         │
│             │    ARCHITECT    │                                         │
│             │   (3-5 years)   │                                         │
│             └────────┬────────┘                                         │
│                      │                                                   │
│       ┌──────────────┼──────────────┐                                   │
│       ▼              ▼              ▼                                   │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐                              │
│  │ Sr. Net  │  │ Infra    │  │ Cloud    │                              │
│  │ Architect│  │ Architect│  │ Architect│                              │
│  └──────────┘  └──────────┘  └──────────┘                              │
│                      │                                                   │
│                      ▼                                                   │
│             ┌─────────────────┐                                         │
│             │   IT Director / │                                         │
│             │  VP of Network  │                                         │
│             └─────────────────┘                                         │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

### Certifications

| Certification | Provider | Relevance |
|---------------|----------|-----------|
| CCIE (Any track) | Cisco | Essential |
| CCNP Enterprise | Cisco | High |
| AWS Advanced Networking | AWS | High |
| Azure Network Engineer | Microsoft | High |
| Palo Alto PCNSE | Palo Alto | Medium |

---

## 13.8 Sample Scenarios

### Scenario 1: Multi-Cloud Network Design

**Situation**: Company needs to connect AWS, Azure, and on-premises datacenter with consistent security policies.

**Network Architect Actions**:
1. Design hub-and-spoke topology with transit gateways
2. Implement consistent IP addressing across environments
3. Set up cloud interconnects (Direct Connect, ExpressRoute)
4. Design BGP peering strategy
5. Implement centralized firewall inspection
6. Create network segmentation aligned across platforms
7. Design DNS resolution across hybrid environment
8. Document traffic flows and failover scenarios

### Scenario 2: Zero Trust Network Implementation

**Situation**: Organization wants to move from perimeter-based to zero trust network architecture.

**Network Architect Actions**:
1. Inventory all network flows and access patterns
2. Design microsegmentation strategy
3. Implement identity-aware network access
4. Deploy ZTNA for remote access
5. Create software-defined perimeter
6. Implement continuous monitoring
7. Design gradual migration from legacy VPN
8. Train teams on new network model

---

## 13.9 Comparison with Other Roles

| Aspect | Network Architect | Infrastructure Architect | Security Architect |
|--------|------------------|------------------------|-------------------|
| **Focus** | Network design | All infrastructure | Security controls |
| **Routing** | Expert | Intermediate | Basic |
| **Security** | Network security | Infrastructure security | All security |
| **Cloud** | Network services | All cloud | Security services |

---

## Key Takeaways

- Network Architects design the **connectivity foundation** for all IT services
- Must understand **both traditional and cloud-native** networking
- **Security is integral** to network design, not an afterthought
- **SD-WAN and SASE** are transforming enterprise networking
- **Automation skills** are increasingly important
- Role requires **deep protocol knowledge** and troubleshooting ability

---

## Practical Exercises

1. **Network Design**: Design a network for a new office location with 500 users, guest Wi-Fi, and cloud connectivity.

2. **Security Zone Design**: Create a network segmentation plan for PCI-DSS compliance.

3. **Cloud Networking**: Design a multi-VPC architecture in AWS with transit gateway and on-premises connectivity.

4. **Troubleshooting**: Given a packet capture, identify the cause of intermittent connectivity issues.

---

## Further Reading

- [Cisco CCIE Study Materials](https://learningnetwork.cisco.com/)
- [AWS Advanced Networking](https://aws.amazon.com/certification/certified-advanced-networking-specialty/)
- [Network Warrior by Gary Donahue](https://www.oreilly.com/library/view/network-warrior-2nd/9781449307974/)
- [SASE for Dummies](https://www.paloaltonetworks.com/resources/ebooks/sase-for-dummies)
