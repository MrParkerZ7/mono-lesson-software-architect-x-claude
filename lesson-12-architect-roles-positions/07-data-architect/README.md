# Data Architect

> **Navigation**: [Back to Lesson Overview](../README.md) | [Previous: Cloud Architect](../06-cloud-architect/README.md) | [Next: Security Architect](../08-security-architect/README.md)

---

## 7.1 Role Overview

The **Data Architect** designs and manages an organization's data infrastructure, including data models, storage solutions, data pipelines, and governance frameworks. They ensure data is accessible, reliable, secure, and optimized for both operational and analytical use cases.

```
┌─────────────────────────────────────────────────────────────────────────┐
│                       DATA ARCHITECT POSITION                            │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│                      DATA SOURCES                                        │
│      ┌──────────┐  ┌──────────┐  ┌──────────┐  ┌──────────┐            │
│      │Transact. │  │  APIs    │  │  IoT     │  │  Files   │            │
│      │ Systems  │  │          │  │ Sensors  │  │          │            │
│      └────┬─────┘  └────┬─────┘  └────┬─────┘  └────┬─────┘            │
│           │             │             │             │                    │
│           └─────────────┴──────┬──────┴─────────────┘                   │
│                                │                                         │
│                                ▼                                         │
│  ┌──────────────────────────────────────────────────────────────────┐   │
│  │                      DATA ARCHITECT                              │   │
│  │                                                                  │   │
│  │   DESIGNS                          GOVERNS                       │   │
│  │   ├── Data Models                  ├── Data Quality             │   │
│  │   ├── Data Pipelines               ├── Master Data              │   │
│  │   ├── Storage Strategy             ├── Data Catalog             │   │
│  │   ├── Integration Patterns         ├── Privacy & Security       │   │
│  │   └── Analytics Platform           └── Compliance               │   │
│  │                                                                  │   │
│  └──────────────────────────────────────────────────────────────────┘   │
│                                │                                         │
│           ┌────────────────────┼────────────────────┐                   │
│           ▼                    ▼                    ▼                   │
│   ┌─────────────┐      ┌─────────────┐      ┌─────────────┐            │
│   │ Operational │      │  Analytics  │      │    ML/AI    │            │
│   │   Systems   │      │  Warehouse  │      │  Platforms  │            │
│   └─────────────┘      └─────────────┘      └─────────────┘            │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 7.2 Core Responsibilities

### Primary Responsibilities

| Responsibility | Description | Time Allocation |
|----------------|-------------|-----------------|
| **Data Modeling** | Design conceptual, logical, and physical data models | 25% |
| **Data Platform Architecture** | Design data infrastructure and pipelines | 25% |
| **Data Governance** | Establish data quality, security, and compliance | 20% |
| **Analytics Architecture** | Design BI, reporting, and analytics solutions | 15% |
| **Integration Design** | Design data flows between systems | 10% |
| **Team Enablement** | Support data engineers and analysts | 5% |

### Data Architecture Domains

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    DATA ARCHITECTURE DOMAINS                             │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  OPERATIONAL DATA                    ANALYTICAL DATA                     │
│  ├── OLTP databases                  ├── Data Warehouse                 │
│  ├── Master Data                     ├── Data Lake                      │
│  ├── Reference Data                  ├── Data Lakehouse                 │
│  ├── Transactional Systems           ├── Data Marts                     │
│  └── Caching Layers                  └── ML Feature Stores              │
│                                                                          │
│  DATA INTEGRATION                    DATA GOVERNANCE                     │
│  ├── ETL/ELT Pipelines               ├── Data Catalog                   │
│  ├── Event Streaming                 ├── Data Quality                   │
│  ├── API Integration                 ├── Data Lineage                   │
│  ├── Data Replication                ├── Data Privacy                   │
│  └── CDC (Change Data Capture)       └── Data Security                  │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 7.3 Day-to-Day Activities

### Typical Week

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    DATA ARCHITECT WEEKLY SCHEDULE                        │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  MONDAY                                                                  │
│  ├── 09:00  Data team standup                                          │
│  ├── 10:00  Data model review for new feature                          │
│  ├── 14:00  Data governance committee meeting                          │
│  └── 16:00  Pipeline architecture review                               │
│                                                                          │
│  TUESDAY                                                                 │
│  ├── 09:00  Data quality issue investigation                           │
│  ├── 11:00  Design session: New analytics requirements                 │
│  ├── 14:00  Stakeholder meeting (business requirements)                │
│  └── 16:00  Data modeling work                                         │
│                                                                          │
│  WEDNESDAY                                                               │
│  ├── 09:00  Architecture review board                                  │
│  ├── 11:00  Data catalog maintenance                                   │
│  ├── 14:00  ML team sync (feature engineering)                         │
│  └── 16:00  Security/compliance review                                 │
│                                                                          │
│  THURSDAY                                                                │
│  ├── 09:00  Data engineering code review                               │
│  ├── 11:00  Performance optimization work                              │
│  ├── 14:00  Vendor evaluation (new data tools)                         │
│  └── 16:00  Documentation updates                                      │
│                                                                          │
│  FRIDAY                                                                  │
│  ├── 09:00  Weekly data platform review                                │
│  ├── 11:00  Research: New data technologies                            │
│  ├── 14:00  Mentoring data engineers                                   │
│  └── 16:00  Planning and prioritization                                │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 7.4 Required Skills

### Technical Skills

| Skill Category | Required Proficiency | Examples |
|----------------|---------------------|----------|
| **Data Modeling** | Expert | Dimensional, 3NF, Data Vault |
| **SQL** | Expert | Complex queries, optimization |
| **Data Warehousing** | Expert | Snowflake, Redshift, BigQuery |
| **ETL/ELT** | Advanced | dbt, Spark, Airflow |
| **Streaming** | Advanced | Kafka, Kinesis, Pub/Sub |
| **Programming** | Intermediate | Python, SQL, Scala |
| **Cloud Data Services** | Advanced | AWS/Azure/GCP data services |

### Data Modeling Expertise

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    DATA MODELING APPROACHES                              │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  CONCEPTUAL MODEL                                                        │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │  Business concepts and relationships (Entity-Relationship)      │    │
│  │                                                                  │    │
│  │  [Customer] ────< places >──── [Order] ────< contains >── [Item] │    │
│  │                                                                  │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                                                          │
│  LOGICAL MODEL (3NF - Normalized)                                        │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │  Detailed entities with attributes, no physical considerations  │    │
│  │                                                                  │    │
│  │  Customer(id, name, email)                                       │    │
│  │  Order(id, customer_id, order_date, status)                     │    │
│  │  OrderItem(id, order_id, product_id, quantity, price)           │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                                                          │
│  PHYSICAL MODEL (Dimensional - Star Schema)                              │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │                      ┌─────────────┐                             │    │
│  │                      │ dim_date    │                             │    │
│  │                      └──────┬──────┘                             │    │
│  │  ┌─────────────┐           │           ┌─────────────┐          │    │
│  │  │dim_customer │──────┬────┼────┬──────│ dim_product │          │    │
│  │  └─────────────┘      │    │    │      └─────────────┘          │    │
│  │                       │    │    │                                │    │
│  │                    ┌──┴────┴────┴──┐                             │    │
│  │                    │  fact_sales   │                             │    │
│  │                    └───────────────┘                             │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 7.5 Key Deliverables

### Primary Artifacts

| Deliverable | Purpose | Audience |
|-------------|---------|----------|
| **Data Models** | Define data structure and relationships | Developers, analysts |
| **Data Architecture Document** | Overall data strategy | All stakeholders |
| **Data Dictionary** | Metadata and definitions | All data users |
| **Data Flow Diagrams** | System data movement | Engineers, architects |
| **Data Quality Rules** | Validation specifications | Data engineers |
| **Data Governance Policies** | Standards and procedures | Organization |

### Modern Data Stack Architecture

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    MODERN DATA STACK                                     │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  INGESTION                 STORAGE                  TRANSFORMATION       │
│  ┌──────────┐             ┌──────────┐             ┌──────────┐         │
│  │ Fivetran │             │Snowflake │             │   dbt    │         │
│  │ Airbyte  │────────────▶│BigQuery  │────────────▶│  Spark   │         │
│  │ Stitch   │             │Redshift  │             │ Dataform │         │
│  └──────────┘             │Databricks│             └──────────┘         │
│                           └──────────┘                   │              │
│                                                          │              │
│  ┌───────────────────────────────────────────────────────┘              │
│  │                                                                       │
│  │  SERVING                 ORCHESTRATION            OBSERVABILITY      │
│  │  ┌──────────┐           ┌──────────┐             ┌──────────┐        │
│  │  │  Looker  │           │ Airflow  │             │Monte Carlo│        │
│  │  │ Tableau  │◀──────────│ Dagster  │────────────▶│  Atlan   │        │
│  │  │ Metabase │           │ Prefect  │             │Great Exp.│        │
│  │  └──────────┘           └──────────┘             └──────────┘        │
│  │                                                                       │
│  └───────────────────────────────────────────────────────────────────────│
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 7.6 Data Governance Framework

### Data Governance Components

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    DATA GOVERNANCE FRAMEWORK                             │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  DATA QUALITY                        DATA SECURITY                       │
│  ├── Completeness                    ├── Access Control                 │
│  ├── Accuracy                        ├── Encryption                     │
│  ├── Consistency                     ├── Masking/Anonymization          │
│  ├── Timeliness                      ├── Audit Logging                  │
│  └── Validity                        └── Data Classification            │
│                                                                          │
│  DATA CATALOG                        DATA PRIVACY                        │
│  ├── Metadata Management             ├── PII Identification             │
│  ├── Data Discovery                  ├── Consent Management             │
│  ├── Data Lineage                    ├── GDPR/CCPA Compliance           │
│  ├── Business Glossary               ├── Data Retention                 │
│  └── Usage Tracking                  └── Right to Deletion              │
│                                                                          │
│  MASTER DATA MANAGEMENT                                                  │
│  ├── Golden Record Creation                                             │
│  ├── Match/Merge Rules                                                  │
│  ├── Data Stewardship                                                   │
│  └── Reference Data Management                                          │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

### Data Quality Dimensions

| Dimension | Definition | Example |
|-----------|------------|---------|
| **Completeness** | All required data is present | No null values in required fields |
| **Accuracy** | Data correctly represents reality | Customer address matches actual |
| **Consistency** | Same data across systems | Customer name same everywhere |
| **Timeliness** | Data is current and available when needed | Orders synced within 1 hour |
| **Validity** | Data conforms to defined formats | Email format is valid |
| **Uniqueness** | No unintended duplicates | One record per customer |

---

## 7.7 Data Pipeline Patterns

### ETL vs ELT

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    ETL vs ELT COMPARISON                                 │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  ETL (Extract, Transform, Load)                                          │
│  ┌─────────┐    ┌─────────────┐    ┌─────────┐    ┌─────────┐          │
│  │ Source  │───▶│  Transform  │───▶│  Load   │───▶│  Target │          │
│  └─────────┘    │  (Staging)  │    └─────────┘    │   DW    │          │
│                 └─────────────┘                    └─────────┘          │
│  - Transform before loading                                             │
│  - Good for: Complex transformations, data cleansing                   │
│  - Limited by ETL server capacity                                      │
│                                                                          │
│  ELT (Extract, Load, Transform)                                          │
│  ┌─────────┐    ┌─────────┐    ┌─────────────┐    ┌─────────┐          │
│  │ Source  │───▶│  Load   │───▶│  Transform  │───▶│ Serving │          │
│  └─────────┘    │ (Raw)   │    │   (in DW)   │    │  Layer  │          │
│                 └─────────┘    └─────────────┘    └─────────┘          │
│  - Load raw, transform in warehouse                                    │
│  - Good for: Cloud DW (Snowflake, BQ), dbt workflows                  │
│  - Leverages DW compute power                                          │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 7.8 Career Path

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    DATA ARCHITECT CAREER PATH                            │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  ENTRY POINTS                                                            │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐          │
│  │     Data        │  │   Database      │  │      BI         │          │
│  │    Engineer     │  │   Administrator │  │    Developer    │          │
│  │   (4+ years)    │  │   (5+ years)    │  │   (5+ years)    │          │
│  └────────┬────────┘  └────────┬────────┘  └────────┬────────┘          │
│           │                    │                    │                    │
│           └────────────────────┼────────────────────┘                    │
│                                ▼                                         │
│                    ┌───────────────────────┐                            │
│                    │        DATA           │                            │
│                    │      ARCHITECT        │                            │
│                    │      (3-5 years)      │                            │
│                    └───────────┬───────────┘                            │
│                                │                                         │
│              ┌─────────────────┼─────────────────┐                      │
│              ▼                 ▼                 ▼                      │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐         │
│  │    Principal    │  │   Chief Data    │  │    Enterprise   │         │
│  │  Data Architect │  │    Officer      │  │    Architect    │         │
│  └─────────────────┘  └─────────────────┘  └─────────────────┘         │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

### Certifications

| Certification | Provider | Relevance |
|---------------|----------|-----------|
| AWS Data Analytics Specialty | AWS | High |
| Azure Data Engineer Associate | Microsoft | High |
| GCP Professional Data Engineer | Google | High |
| Snowflake SnowPro Core | Snowflake | High |
| CDMP (Certified Data Management Professional) | DAMA | High |
| Databricks Data Engineer | Databricks | Medium |

---

## 7.9 Sample Scenarios

### Scenario 1: Data Platform Modernization

**Situation**: A retail company has data scattered across legacy SQL servers, spreadsheets, and SaaS applications. Leadership wants a unified analytics platform.

**Data Architect Actions**:
1. Assess current data landscape and inventory sources
2. Define data domains and ownership
3. Design cloud data warehouse architecture (Snowflake/BigQuery)
4. Create dimensional model for core business metrics
5. Design ingestion pipelines (batch and real-time)
6. Implement data catalog and governance framework
7. Define data quality monitoring and alerting
8. Plan migration waves with minimal business disruption

### Scenario 2: GDPR Compliance

**Situation**: Company needs to ensure all personal data handling complies with GDPR.

**Data Architect Actions**:
1. Inventory all PII across systems
2. Classify data by sensitivity level
3. Implement data lineage tracking
4. Design consent management data model
5. Create right-to-deletion workflows
6. Implement data retention policies
7. Set up audit logging for data access
8. Document data processing activities

---

## 7.10 Comparison with Other Roles

| Aspect | Data Architect | Data Engineer | Analytics Engineer |
|--------|---------------|---------------|-------------------|
| **Focus** | Architecture & governance | Building pipelines | Analytics layer |
| **Coding** | Medium (SQL, modeling) | High (Python, Spark) | Medium (SQL, dbt) |
| **Scope** | Enterprise-wide | Project/team | Analytics domain |
| **Primary Output** | Models, standards | Data pipelines | Reports, dashboards |

---

## Key Takeaways

- Data Architects **design the foundation** for all data initiatives
- **Governance** is as important as technical design
- Modern data architecture leverages **cloud-native services**
- **Data quality** must be built-in, not bolted-on
- Success requires **strong partnership** with business stakeholders
- Role is increasingly important as organizations become **data-driven**

---

## Practical Exercises

1. **Data Modeling**: Design a dimensional model for a subscription business (users, subscriptions, payments, usage).

2. **Data Governance Plan**: Create a data governance framework for a healthcare organization including quality rules and privacy requirements.

3. **Architecture Design**: Design a real-time data pipeline for an e-commerce platform that needs to process clickstream data.

4. **Data Catalog**: Create a data dictionary for a sample database with business definitions and technical metadata.

---

## Further Reading

- [The Data Warehouse Toolkit by Ralph Kimball](https://www.amazon.com/Data-Warehouse-Toolkit-Definitive-Dimensional/dp/1118530802)
- [Fundamentals of Data Engineering by Reis & Housley](https://www.oreilly.com/library/view/fundamentals-of-data/9781098108298/)
- [DAMA-DMBOK: Data Management Body of Knowledge](https://www.dama.org/cpages/body-of-knowledge)
- [Building a Scalable Data Warehouse with Data Vault 2.0](https://www.amazon.com/Building-Scalable-Data-Warehouse-Vault/dp/0128025107)
