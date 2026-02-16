# Systems Architect

> **Navigation**: [Back to Lesson Overview](../README.md) | [Previous: Platform Architect](../13-specialist-platform-architect/README.md) | [Next: Principal/Staff Architect](../15-leadership-principal-staff-architect/README.md)

---

## 14.1 Role Overview

The **Systems Architect** designs complex systems involving multiple interacting components, often including both hardware and software elements. Common in aerospace, telecommunications, defense, and embedded systems industries, this role requires understanding how to integrate diverse subsystems into a cohesive whole.

```
┌─────────────────────────────────────────────────────────────────────────┐
│                      SYSTEMS ARCHITECT POSITION                          │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│                        SYSTEM REQUIREMENTS                               │
│     ┌──────────────┐  ┌──────────────┐  ┌──────────────┐                │
│     │ Functional   │  │ Performance  │  │ Environmental│                │
│     │ Requirements │  │    Specs     │  │ Constraints  │                │
│     └──────┬───────┘  └──────┬───────┘  └──────┬───────┘                │
│            │                 │                 │                         │
│            └─────────────────┼─────────────────┘                         │
│                              │                                           │
│                              ▼                                           │
│  ┌──────────────────────────────────────────────────────────────────┐   │
│  │                    SYSTEMS ARCHITECT                             │   │
│  │                                                                  │   │
│  │   ┌─────────────────────────────────────────────────────────┐   │   │
│  │   │                  COMPLETE SYSTEM                         │   │   │
│  │   │                                                          │   │   │
│  │   │  ┌─────────┐  ┌─────────┐  ┌─────────┐  ┌─────────┐    │   │   │
│  │   │  │Hardware │  │Firmware │  │Software │  │ Network │    │   │   │
│  │   │  │Subsystem│◄─┤Subsystem│◄─┤Subsystem│◄─┤Subsystem│    │   │   │
│  │   │  └─────────┘  └─────────┘  └─────────┘  └─────────┘    │   │   │
│  │   │                      ▲                                   │   │   │
│  │   │                      │                                   │   │   │
│  │   │              ┌───────┴───────┐                          │   │   │
│  │   │              │   External    │                          │   │   │
│  │   │              │  Interfaces   │                          │   │   │
│  │   │              └───────────────┘                          │   │   │
│  │   └─────────────────────────────────────────────────────────┘   │   │
│  │                                                                  │   │
│  │   DESIGNS: Architecture │ Interfaces │ Integration │ Validation │   │
│  └──────────────────────────────────────────────────────────────────┘   │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 12.2 Core Responsibilities

### Primary Responsibilities

| Responsibility | Description | Time Allocation |
|----------------|-------------|-----------------|
| **System Design** | Design overall system architecture | 30% |
| **Subsystem Integration** | Define interfaces between subsystems | 20% |
| **Requirements Analysis** | Translate needs into technical specs | 15% |
| **Trade-off Analysis** | Evaluate design alternatives | 15% |
| **Verification & Validation** | Ensure system meets requirements | 10% |
| **Technical Leadership** | Guide subsystem teams | 10% |

### Systems Engineering Domains

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    SYSTEMS ENGINEERING DOMAINS                           │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  SYSTEM DESIGN                       INTERFACE ENGINEERING               │
│  ├── System Decomposition            ├── Hardware-Software Interfaces   │
│  ├── Functional Allocation           ├── Communication Protocols        │
│  ├── Physical Architecture           ├── API Specifications             │
│  ├── Logical Architecture            ├── Data Formats                   │
│  └── Behavior Modeling               └── Electrical Interfaces          │
│                                                                          │
│  VERIFICATION & VALIDATION           SYSTEM INTEGRATION                  │
│  ├── Requirements Traceability       ├── Integration Planning           │
│  ├── Test Planning                   ├── Interface Testing              │
│  ├── System Testing                  ├── Component Integration          │
│  ├── Acceptance Testing              ├── System-of-Systems              │
│  └── Simulation & Modeling           └── Commissioning                  │
│                                                                          │
│  RELIABILITY & SAFETY                LIFECYCLE MANAGEMENT                │
│  ├── FMEA/FMECA                      ├── Configuration Management       │
│  ├── Fault Tolerance                 ├── Change Control                 │
│  ├── Safety Analysis                 ├── Version Control                │
│  ├── Redundancy Design               ├── Obsolescence Management        │
│  └── Degraded Mode Operation         └── Sustainability                 │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 12.3 Day-to-Day Activities

### Typical Week

```
┌─────────────────────────────────────────────────────────────────────────┐
│                   SYSTEMS ARCHITECT WEEKLY SCHEDULE                      │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  MONDAY                                                                  │
│  ├── 09:00  Program status meeting                                     │
│  ├── 10:30  Subsystem interface review                                 │
│  ├── 14:00  Requirements analysis session                              │
│  └── 16:00  System design documentation                                │
│                                                                          │
│  TUESDAY                                                                 │
│  ├── 09:00  Trade study review (HW vs SW allocation)                   │
│  ├── 11:00  Integration planning meeting                               │
│  ├── 14:00  Cross-functional design review                             │
│  └── 16:00  Model-based systems engineering work                       │
│                                                                          │
│  WEDNESDAY                                                               │
│  ├── 09:00  Customer/stakeholder meeting                               │
│  ├── 11:00  Technical risk assessment                                  │
│  ├── 14:00  System simulation review                                   │
│  └── 16:00  Interface control document updates                         │
│                                                                          │
│  THURSDAY                                                                │
│  ├── 09:00  Verification planning                                      │
│  ├── 11:00  Supplier technical review                                  │
│  ├── 14:00  Safety/reliability analysis                                │
│  └── 16:00  Change control board                                       │
│                                                                          │
│  FRIDAY                                                                  │
│  ├── 09:00  Weekly technical review                                    │
│  ├── 11:00  Team coordination                                          │
│  ├── 14:00  Technical documentation                                    │
│  └── 16:00  Planning and lessons learned                               │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 12.4 Required Skills

### Technical Skills

| Skill Category | Required Proficiency | Examples |
|----------------|---------------------|----------|
| **Systems Engineering** | Expert | INCOSE SE Handbook, V-Model |
| **Requirements Engineering** | Expert | DOORS, Jama, Polarion |
| **Model-Based SE** | Advanced | SysML, Simulink, MATLAB |
| **Hardware Engineering** | Intermediate | PCB, FPGA, sensors |
| **Software Engineering** | Intermediate | Embedded, real-time |
| **Verification & Test** | Advanced | Test planning, simulation |
| **Domain Knowledge** | Expert | Specific industry expertise |

### Systems Engineering V-Model

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    SYSTEMS ENGINEERING V-MODEL                           │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  DEFINITION PHASE                            VERIFICATION PHASE          │
│                                                                          │
│  Stakeholder       ─────────────────────────────▶    System              │
│  Requirements                                        Validation          │
│       │                                                  ▲               │
│       ▼                                                  │               │
│  System            ─────────────────────────────▶    System              │
│  Requirements                                      Verification          │
│       │                                                  ▲               │
│       ▼                                                  │               │
│  System            ─────────────────────────────▶    Integration         │
│  Architecture                                        Testing             │
│       │                                                  ▲               │
│       ▼                                                  │               │
│  Subsystem         ─────────────────────────────▶    Subsystem           │
│  Design                                              Testing             │
│       │                                                  ▲               │
│       ▼                                                  │               │
│  Component         ─────────────────────────────▶    Component           │
│  Design                                              Testing             │
│       │                                                  ▲               │
│       └──────────────▶  IMPLEMENTATION  ◀──────────────┘               │
│                                                                          │
│  Each level on left traces to corresponding verification on right       │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 12.5 Key Deliverables

### Primary Artifacts

| Deliverable | Purpose | Audience |
|-------------|---------|----------|
| **System Architecture Document** | Overall system design | All stakeholders |
| **System Requirements Spec (SRS)** | Detailed requirements | Engineering teams |
| **Interface Control Documents (ICD)** | Subsystem interfaces | Integration teams |
| **Trade Study Reports** | Design decision rationale | Technical leadership |
| **Verification Matrix** | Requirements traceability | Test teams |
| **System Models (SysML)** | Architecture modeling | Engineering teams |

### Interface Control Document Example

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    INTERFACE CONTROL DOCUMENT                            │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  INTERFACE: Sensor Controller ↔ Processing Unit                         │
│  ═══════════════════════════════════════════════                        │
│                                                                          │
│  PHYSICAL INTERFACE                                                      │
│  ├── Connector: MIL-DTL-38999 Series III                               │
│  ├── Pins: 19 pins                                                      │
│  └── Cable Length: Max 2 meters                                         │
│                                                                          │
│  ELECTRICAL INTERFACE                                                    │
│  ├── Power: +28V DC ± 4V, 500mA max                                    │
│  ├── Signal: RS-422 differential                                       │
│  ├── Baud Rate: 115200 bps                                             │
│  └── Protocol: Custom binary (see below)                               │
│                                                                          │
│  DATA INTERFACE                                                          │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │  Field        │ Size    │ Type    │ Description                │    │
│  │───────────────┼─────────┼─────────┼────────────────────────────│    │
│  │  Sync         │ 2 bytes │ uint16  │ 0xAA55                     │    │
│  │  Msg Type     │ 1 byte  │ uint8   │ Message identifier         │    │
│  │  Length       │ 2 bytes │ uint16  │ Payload length             │    │
│  │  Payload      │ N bytes │ varies  │ Message-specific data      │    │
│  │  CRC          │ 2 bytes │ uint16  │ CRC-16-CCITT               │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                                                          │
│  TIMING REQUIREMENTS                                                     │
│  ├── Message Rate: 50 Hz                                               │
│  ├── Latency: < 10ms                                                   │
│  └── Startup Time: < 2 seconds                                         │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 12.6 Trade Study Process

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    TRADE STUDY PROCESS                                   │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  1. DEFINE PROBLEM                                                       │
│     └── What decision needs to be made?                                 │
│                                                                          │
│  2. IDENTIFY ALTERNATIVES                                                │
│     ├── Alternative A: Commercial off-the-shelf (COTS)                  │
│     ├── Alternative B: Custom development                               │
│     └── Alternative C: Modified existing component                      │
│                                                                          │
│  3. DEFINE CRITERIA & WEIGHTS                                            │
│     ├── Performance (30%)                                               │
│     ├── Cost (25%)                                                      │
│     ├── Schedule (20%)                                                  │
│     ├── Risk (15%)                                                      │
│     └── Maintainability (10%)                                           │
│                                                                          │
│  4. EVALUATE ALTERNATIVES                                                │
│     ┌────────────────────────────────────────────────────────────┐      │
│     │ Criteria      │ Weight │ Alt A │ Alt B │ Alt C │           │      │
│     │───────────────┼────────┼───────┼───────┼───────┤           │      │
│     │ Performance   │  0.30  │  4    │  5    │  4    │           │      │
│     │ Cost          │  0.25  │  5    │  2    │  4    │           │      │
│     │ Schedule      │  0.20  │  4    │  2    │  3    │           │      │
│     │ Risk          │  0.15  │  3    │  4    │  3    │           │      │
│     │ Maintain.     │  0.10  │  4    │  5    │  3    │           │      │
│     │───────────────┼────────┼───────┼───────┼───────┤           │      │
│     │ WEIGHTED SCORE│        │ 4.05  │ 3.50  │ 3.55  │           │      │
│     └────────────────────────────────────────────────────────────┘      │
│                                                                          │
│  5. RECOMMEND                                                            │
│     └── Alternative A recommended based on highest weighted score       │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 12.7 Industry Applications

### Common Industries

| Industry | System Examples | Key Concerns |
|----------|----------------|--------------|
| **Aerospace** | Aircraft, satellites, drones | Safety, certification (DO-178C) |
| **Defense** | Weapons systems, radar, C2 | Reliability, security, ITAR |
| **Automotive** | ADAS, autonomous vehicles | Safety (ISO 26262), real-time |
| **Telecom** | 5G infrastructure, networks | Performance, scalability |
| **Medical** | Imaging, surgical robots | Safety (IEC 62304), FDA |
| **Industrial** | Automation, robotics, IoT | Reliability, interoperability |

---

## 12.8 Career Path

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    SYSTEMS ARCHITECT CAREER PATH                         │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  ENTRY POINTS                                                            │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐          │
│  │   Systems       │  │   Hardware      │  │   Software      │          │
│  │   Engineer      │  │   Engineer      │  │   Engineer      │          │
│  │   (5+ years)    │  │   (5+ years)    │  │   (5+ years)    │          │
│  └────────┬────────┘  └────────┬────────┘  └────────┬────────┘          │
│           │                    │                    │                    │
│           └────────────────────┼────────────────────┘                    │
│                                ▼                                         │
│                    ┌───────────────────────┐                            │
│                    │       SYSTEMS         │                            │
│                    │       ARCHITECT       │                            │
│                    │      (5-10 years)     │                            │
│                    └───────────┬───────────┘                            │
│                                │                                         │
│              ┌─────────────────┼─────────────────┐                      │
│              ▼                 ▼                 ▼                      │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐         │
│  │    Chief        │  │   Technical     │  │    Program      │         │
│  │   Engineer      │  │   Fellow        │  │   Manager       │         │
│  └─────────────────┘  └─────────────────┘  └─────────────────┘         │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

### Certifications

| Certification | Provider | Relevance |
|---------------|----------|-----------|
| INCOSE CSEP/ESEP | INCOSE | Essential |
| PMP | PMI | Medium |
| AWS/Azure (for IT systems) | Cloud Providers | Medium |
| Domain-specific (DO-178C, ISO 26262) | Various | High (industry-specific) |

---

## 12.9 Sample Scenarios

### Scenario 1: Autonomous Vehicle System

**Situation**: Design the system architecture for an autonomous vehicle including perception, planning, and control subsystems.

**Systems Architect Actions**:
1. Define system-level requirements (safety, performance)
2. Decompose into subsystems (sensors, perception, planning, actuation)
3. Define interfaces between subsystems
4. Allocate requirements to subsystems
5. Design safety architecture (redundancy, fail-safe)
6. Plan integration sequence
7. Create verification and validation plan
8. Coordinate with subsystem teams

### Scenario 2: Satellite Communication System

**Situation**: Design ground-to-space communication system for a constellation of LEO satellites.

**Systems Architect Actions**:
1. Analyze link budget and coverage requirements
2. Design ground station architecture
3. Define space-ground interfaces
4. Specify handover protocols between satellites
5. Design for graceful degradation
6. Plan frequency coordination and licensing
7. Create integration and test plan
8. Support certification activities

---

## 12.10 Comparison with Other Roles

| Aspect | Systems Architect | Solution Architect | Software Architect |
|--------|------------------|-------------------|-------------------|
| **Scope** | Complete systems | Business solutions | Software systems |
| **Hardware** | Yes | Rarely | No |
| **Safety/Cert** | Often critical | Rarely | Sometimes |
| **Industry** | Aerospace, Defense, Auto | IT, Enterprise | IT, Software |
| **Lifecycle** | Full V-model | Project-focused | Development-focused |

---

## Key Takeaways

- Systems Architects design **complex multi-component systems**
- Must understand **both hardware and software** integration
- **Requirements traceability** and **interface management** are critical
- Often work in **safety-critical** and **regulated** industries
- **Trade studies** are essential for informed decision-making
- Role requires **deep technical breadth** across multiple disciplines

---

## Practical Exercises

1. **System Decomposition**: Decompose a home automation system into subsystems and define interfaces.

2. **Trade Study**: Conduct a trade study comparing three approaches for a sensor data processing system.

3. **ICD Development**: Create an interface control document for communication between two subsystems.

4. **V&V Planning**: Develop a verification matrix for a simple embedded system.

---

## Further Reading

- [INCOSE Systems Engineering Handbook](https://www.incose.org/products-and-publications/se-handbook)
- [Systems Engineering Principles and Practice by Kossiakoff et al.](https://www.wiley.com/en-us/Systems+Engineering+Principles+and+Practice%2C+3rd+Edition-p-9781119516668)
- [NASA Systems Engineering Handbook](https://www.nasa.gov/reference/systems-engineering-handbook/)
- [Model-Based Systems Engineering with SysML (Friedenthal)](https://www.elsevier.com/books/a-practical-guide-to-sysml/friedenthal/978-0-12-800202-5)
