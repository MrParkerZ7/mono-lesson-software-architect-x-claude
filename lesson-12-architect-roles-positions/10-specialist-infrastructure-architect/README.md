# Infrastructure Architect

> **Navigation**: [Back to Lesson Overview](../README.md) | [Previous: Security Architect](../09-specialist-security-architect/README.md) | [Next: Network Architect](../11-specialist-network-architect/README.md)

---

## 10.1 Role Overview

The **Infrastructure Architect** designs the foundational technology infrastructure that supports all applications and services. This includes physical and virtual servers, storage systems, networking, and datacenter operations. They ensure infrastructure is reliable, scalable, cost-effective, and aligned with business needs.

```
┌─────────────────────────────────────────────────────────────────────────┐
│                   INFRASTRUCTURE ARCHITECT POSITION                      │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│                        BUSINESS REQUIREMENTS                             │
│     ┌──────────────┐  ┌──────────────┐  ┌──────────────┐                │
│     │ Performance  │  │ Availability │  │    Cost      │                │
│     │ Requirements │  │    SLAs      │  │  Constraints │                │
│     └──────┬───────┘  └──────┬───────┘  └──────┬───────┘                │
│            │                 │                 │                         │
│            └─────────────────┼─────────────────┘                         │
│                              │                                           │
│                              ▼                                           │
│  ┌──────────────────────────────────────────────────────────────────┐   │
│  │                 INFRASTRUCTURE ARCHITECT                         │   │
│  │                                                                  │   │
│  │   ┌─────────────┐  ┌─────────────┐  ┌─────────────┐             │   │
│  │   │   COMPUTE   │  │   STORAGE   │  │   NETWORK   │             │   │
│  │   │             │  │             │  │             │             │   │
│  │   │ • Servers   │  │ • SAN/NAS   │  │ • Switches  │             │   │
│  │   │ • VMs       │  │ • Object    │  │ • Routers   │             │   │
│  │   │ • Containers│  │ • Block     │  │ • Firewalls │             │   │
│  │   │ • HCI       │  │ • Backup    │  │ • Load Bal. │             │   │
│  │   └─────────────┘  └─────────────┘  └─────────────┘             │   │
│  │                                                                  │   │
│  │   DESIGNS: Capacity │ Reliability │ Performance │ Recovery      │   │
│  └──────────────────────────────────────────────────────────────────┘   │
│                              │                                           │
│                              ▼                                           │
│                     ┌─────────────────┐                                 │
│                     │  INFRASTRUCTURE │                                 │
│                     │    PLATFORM     │                                 │
│                     └─────────────────┘                                 │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 9.2 Core Responsibilities

### Primary Responsibilities

| Responsibility | Description | Time Allocation |
|----------------|-------------|-----------------|
| **Infrastructure Design** | Design compute, storage, and network infrastructure | 30% |
| **Capacity Planning** | Forecast and plan for growth | 15% |
| **Availability Design** | Design for high availability and disaster recovery | 15% |
| **Performance Engineering** | Optimize infrastructure performance | 15% |
| **Vendor Management** | Evaluate and manage technology vendors | 10% |
| **Standards & Governance** | Define infrastructure standards | 15% |

### Infrastructure Domains

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    INFRASTRUCTURE DOMAINS                                │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  COMPUTE                            STORAGE                              │
│  ├── Physical Servers               ├── SAN (Fibre Channel, iSCSI)      │
│  ├── Virtualization (VMware, HV)    ├── NAS (NFS, SMB)                  │
│  ├── Containers (Docker, K8s)       ├── Object Storage (S3-like)        │
│  ├── Hyperconverged (HCI)           ├── Backup & Archive                │
│  └── Bare Metal Cloud               └── Data Protection                 │
│                                                                          │
│  NETWORK                            DATACENTER                           │
│  ├── LAN/WAN                        ├── Power & Cooling                 │
│  ├── Software-Defined (SDN)         ├── Physical Security               │
│  ├── Load Balancing                 ├── Cabling & Connectivity          │
│  ├── DNS/DHCP                       ├── Environmental Monitoring        │
│  └── Network Security               └── Colocation Management           │
│                                                                          │
│  HYBRID/MULTI-CLOUD                 OPERATIONS                           │
│  ├── Cloud Connectivity             ├── Monitoring & Alerting           │
│  ├── Hybrid Integration             ├── Automation                      │
│  ├── Multi-Cloud Strategy           ├── Patch Management                │
│  └── Edge Computing                 └── Change Management               │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 9.3 Day-to-Day Activities

### Typical Week

```
┌─────────────────────────────────────────────────────────────────────────┐
│                INFRASTRUCTURE ARCHITECT WEEKLY SCHEDULE                  │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  MONDAY                                                                  │
│  ├── 09:00  Infrastructure team standup                                │
│  ├── 10:00  Capacity review meeting                                    │
│  ├── 14:00  Design review: New storage solution                        │
│  └── 16:00  Vendor call (hardware refresh)                             │
│                                                                          │
│  TUESDAY                                                                 │
│  ├── 09:00  Performance analysis review                                │
│  ├── 11:00  DR design session                                          │
│  ├── 14:00  Project architecture review                                │
│  └── 16:00  Standards documentation                                    │
│                                                                          │
│  WEDNESDAY                                                               │
│  ├── 09:00  Change advisory board (CAB)                                │
│  ├── 11:00  Virtualization strategy discussion                         │
│  ├── 14:00  Cost optimization review                                   │
│  └── 16:00  Infrastructure automation work                             │
│                                                                          │
│  THURSDAY                                                                │
│  ├── 09:00  Security review (infrastructure hardening)                 │
│  ├── 11:00  Hybrid cloud design session                                │
│  ├── 14:00  Incident review (post-mortem)                              │
│  └── 16:00  Technology research                                        │
│                                                                          │
│  FRIDAY                                                                  │
│  ├── 09:00  Weekly infrastructure review                               │
│  ├── 11:00  Team mentoring sessions                                    │
│  ├── 14:00  Roadmap planning                                           │
│  └── 16:00  Documentation and handoff                                  │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 9.4 Required Skills

### Technical Skills

| Skill Category | Required Proficiency | Examples |
|----------------|---------------------|----------|
| **Virtualization** | Expert | VMware vSphere, Hyper-V, KVM |
| **Storage Systems** | Expert | SAN, NAS, object storage |
| **Networking** | Advanced | Routing, switching, firewalls |
| **Operating Systems** | Advanced | Windows Server, Linux |
| **Cloud Platforms** | Advanced | AWS, Azure, GCP infrastructure |
| **Automation** | Intermediate | Ansible, PowerShell, Terraform |
| **Containers** | Intermediate | Docker, Kubernetes infrastructure |

### Infrastructure Stack

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    INFRASTRUCTURE STACK                                  │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  LAYER               ON-PREMISES              CLOUD                      │
│  ─────────────────────────────────────────────────────────────────────  │
│                                                                          │
│  Applications        VMs, Containers          EC2, AKS, GKE             │
│                                                                          │
│  Orchestration       vCenter, SCVMM           AWS Console, Portal       │
│                                                                          │
│  Virtualization      VMware ESXi, HyperV      Hypervisor (managed)      │
│                                                                          │
│  Compute             Physical Servers          Bare Metal, Instances    │
│                                                                          │
│  Storage             SAN, NAS, DAS            EBS, S3, Azure Disk       │
│                                                                          │
│  Network             Switches, Routers        VPC, VNet, Subnets        │
│                                                                          │
│  Facilities          Power, Cooling, Space    Managed by Provider       │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 9.5 Key Deliverables

### Primary Artifacts

| Deliverable | Purpose | Audience |
|-------------|---------|----------|
| **Infrastructure Architecture Document** | Overall infrastructure design | All stakeholders |
| **Capacity Plans** | Growth projections and requirements | Management, finance |
| **DR/BC Plans** | Disaster recovery procedures | Operations, management |
| **Performance Baselines** | Normal operation metrics | Operations |
| **Infrastructure Standards** | Configuration guidelines | Operations teams |
| **Network Diagrams** | Physical and logical topology | Operations, security |

### High Availability Design

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    HIGH AVAILABILITY PATTERNS                            │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  N+1 REDUNDANCY                                                          │
│  ┌─────────┐ ┌─────────┐ ┌─────────┐                                   │
│  │ Server 1│ │ Server 2│ │ Server 3│  ← 2 active, 1 standby            │
│  │ (Active)│ │ (Active)│ │(Standby)│                                   │
│  └─────────┘ └─────────┘ └─────────┘                                   │
│                                                                          │
│  ACTIVE-ACTIVE CLUSTER                                                   │
│  ┌────────────────────────────────────────────────────┐                 │
│  │              LOAD BALANCER                          │                 │
│  └─────────────┬─────────────────────┬────────────────┘                 │
│                ▼                     ▼                                   │
│         ┌───────────┐         ┌───────────┐                             │
│         │  Node A   │◄───────▶│  Node B   │  ← Both active              │
│         │ (Active)  │  Sync   │ (Active)  │                             │
│         └───────────┘         └───────────┘                             │
│                                                                          │
│  ACTIVE-PASSIVE (FAILOVER)                                               │
│         ┌───────────┐         ┌───────────┐                             │
│         │  Primary  │────────▶│ Secondary │  ← Standby takes over      │
│         │ (Active)  │  Replic │ (Passive) │    on failure               │
│         └───────────┘         └───────────┘                             │
│                                                                          │
│  GEOGRAPHIC REDUNDANCY                                                   │
│  ┌─────────────────┐                    ┌─────────────────┐             │
│  │   Site A        │◄───── WAN Link ───▶│    Site B       │             │
│  │   (Primary)     │    Replication     │   (DR Site)     │             │
│  └─────────────────┘                    └─────────────────┘             │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 9.6 Capacity Planning

### Capacity Planning Process

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    CAPACITY PLANNING PROCESS                             │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  1. MEASURE CURRENT STATE                                                │
│     ├── CPU utilization trends                                          │
│     ├── Memory usage patterns                                           │
│     ├── Storage consumption rates                                       │
│     ├── Network bandwidth utilization                                   │
│     └── IOPS and latency metrics                                        │
│                                                                          │
│  2. ANALYZE TRENDS                                                       │
│     ├── Historical growth rates                                         │
│     ├── Seasonal patterns                                               │
│     ├── Business growth projections                                     │
│     └── New project requirements                                        │
│                                                                          │
│  3. FORECAST REQUIREMENTS                                                │
│     ├── 6-month projections                                             │
│     ├── 12-month projections                                            │
│     ├── 3-year strategic view                                           │
│     └── Buffer for unexpected growth                                    │
│                                                                          │
│  4. PLAN ACQUISITIONS                                                    │
│     ├── Hardware procurement timelines                                  │
│     ├── Budget requirements                                             │
│     ├── Installation and configuration                                  │
│     └── Migration planning                                              │
│                                                                          │
│  5. EXECUTE & MONITOR                                                    │
│     ├── Implement capacity additions                                    │
│     ├── Validate projections                                            │
│     └── Adjust models based on actuals                                  │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 9.7 Disaster Recovery

### DR Tier Classification

| Tier | RTO | RPO | Solution | Cost |
|------|-----|-----|----------|------|
| **Tier 1** | < 1 hour | < 15 min | Active-Active, sync replication | $$$$ |
| **Tier 2** | 1-4 hours | < 1 hour | Warm standby, async replication | $$$ |
| **Tier 3** | 4-24 hours | 1-4 hours | Cold standby, periodic backup | $$ |
| **Tier 4** | 24-72 hours | 24 hours | Backup restore, manual recovery | $ |

### DR Architecture

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    DISASTER RECOVERY ARCHITECTURE                        │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│       PRIMARY SITE                           DR SITE                     │
│  ┌─────────────────────┐              ┌─────────────────────┐           │
│  │                     │              │                     │           │
│  │  ┌───────────────┐  │   Sync/     │  ┌───────────────┐  │           │
│  │  │  Production   │  │   Async     │  │   Standby     │  │           │
│  │  │   Servers     │──┼────────────▶│  │   Servers     │  │           │
│  │  └───────────────┘  │  Replicat.  │  └───────────────┘  │           │
│  │                     │              │                     │           │
│  │  ┌───────────────┐  │              │  ┌───────────────┐  │           │
│  │  │   Storage     │──┼────────────▶│  │   Storage     │  │           │
│  │  │    (SAN)      │  │             │  │   (Replica)   │  │           │
│  │  └───────────────┘  │              │  └───────────────┘  │           │
│  │                     │              │                     │           │
│  │  ┌───────────────┐  │   Backup    │  ┌───────────────┐  │           │
│  │  │   Backup      │──┼────────────▶│  │    Backup     │  │           │
│  │  │   Server      │  │   Copy      │  │    Copy       │  │           │
│  │  └───────────────┘  │              │  └───────────────┘  │           │
│  │                     │              │                     │           │
│  └─────────────────────┘              └─────────────────────┘           │
│                                                                          │
│  FAILOVER PROCESS                                                        │
│  1. Detect failure (automated/manual)                                   │
│  2. DNS/Traffic switch                                                  │
│  3. Activate DR systems                                                 │
│  4. Validate services                                                   │
│  5. Communicate status                                                  │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 9.8 Career Path

```
┌─────────────────────────────────────────────────────────────────────────┐
│                 INFRASTRUCTURE ARCHITECT CAREER PATH                     │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  ENTRY POINTS                                                            │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐          │
│  │    Systems      │  │    Network      │  │    Storage      │          │
│  │   Administrator │  │    Engineer     │  │   Administrator │          │
│  │   (5+ years)    │  │   (5+ years)    │  │   (5+ years)    │          │
│  └────────┬────────┘  └────────┬────────┘  └────────┬────────┘          │
│           │                    │                    │                    │
│           └────────────────────┼────────────────────┘                    │
│                                ▼                                         │
│                    ┌───────────────────────┐                            │
│                    │    INFRASTRUCTURE     │                            │
│                    │      ARCHITECT        │                            │
│                    │      (3-5 years)      │                            │
│                    └───────────┬───────────┘                            │
│                                │                                         │
│              ┌─────────────────┼─────────────────┐                      │
│              ▼                 ▼                 ▼                      │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐         │
│  │     Cloud       │  │   Enterprise    │  │  IT Director/   │         │
│  │   Architect     │  │   Architect     │  │     VP          │         │
│  └─────────────────┘  └─────────────────┘  └─────────────────┘         │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

### Certifications

| Certification | Provider | Relevance |
|---------------|----------|-----------|
| VMware VCP/VCAP | VMware | High |
| Cisco CCNP/CCIE | Cisco | High |
| AWS Solutions Architect | AWS | High |
| Microsoft Azure Administrator | Microsoft | Medium |
| ITIL Foundation/Expert | Axelos | Medium |

---

## 9.9 Sample Scenarios

### Scenario 1: Datacenter Consolidation

**Situation**: Company has 3 datacenters and wants to consolidate to 2 with improved DR.

**Infrastructure Architect Actions**:
1. Inventory all workloads across datacenters
2. Assess application dependencies and criticality
3. Design consolidated architecture with proper sizing
4. Plan network connectivity between sites
5. Design storage migration strategy
6. Create migration waves with rollback plans
7. Define DR strategy for consolidated environment
8. Plan decommissioning of vacated datacenter

### Scenario 2: Hybrid Cloud Infrastructure

**Situation**: Organization wants to extend on-premises infrastructure to cloud for burst capacity.

**Infrastructure Architect Actions**:
1. Assess workloads suitable for cloud extension
2. Design network connectivity (VPN/Direct Connect)
3. Create unified identity management approach
4. Design storage integration strategy
5. Define workload placement policies
6. Implement monitoring across hybrid environment
7. Create cost management and optimization plan
8. Document operational procedures

---

## 9.10 Comparison with Other Roles

| Aspect | Infrastructure Architect | Cloud Architect | Network Architect |
|--------|------------------------|----------------|------------------|
| **Focus** | All infrastructure | Cloud platforms | Network only |
| **Physical Hardware** | High | Low | Medium |
| **Datacenter** | Yes | Minimal | Partial |
| **Virtualization** | Expert | Advanced | Intermediate |
| **Scope** | Compute, storage, network | Cloud services | Network topology |

---

## Key Takeaways

- Infrastructure Architects design the **foundation for all IT services**
- **Reliability and performance** are primary concerns
- **Capacity planning** prevents outages and over-spending
- Must understand **both on-premises and cloud** infrastructure
- **Disaster recovery** design is a critical responsibility
- Role is evolving with **hybrid cloud and automation**

---

## Practical Exercises

1. **Capacity Plan**: Create a capacity plan for a growing e-commerce platform with 30% YoY growth.

2. **DR Design**: Design a disaster recovery solution for a Tier 2 application (RTO: 4 hours, RPO: 1 hour).

3. **Infrastructure Review**: Review a sample infrastructure diagram and identify single points of failure.

4. **Migration Plan**: Create a migration plan for moving 50 VMs from on-premises to cloud.

---

## Further Reading

- [The Practice of System and Network Administration](https://www.amazon.com/Practice-System-Network-Administration-Enterprise/dp/0321919165)
- [VMware vSphere Design](https://www.amazon.com/VMware-vSphere-Design-Forbes-Guthrie/dp/1118407911)
- [Site Reliability Engineering (Google)](https://sre.google/books/)
- [AWS Infrastructure Patterns](https://aws.amazon.com/architecture/)
