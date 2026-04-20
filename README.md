# Apache ShardingSphere (apache-shardingsphere)
Apache ShardingSphere is an open-source ecosystem for distributed database systems providing data sharding, distributed transactions, and database governance. It supports MySQL, PostgreSQL, and other databases with transparent sharding capabilities.

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-shardingsphere/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-shardingsphere/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Database, Distributed SQL, Read-Write Splitting, Sharding, SQL, Apache, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache ShardingSphere REST API
ShardingSphere provides REST endpoints for managing logical databases, physical data sources, sharding rules, read-write splitting configuration, and cluster status via the ShardingSphere Proxy admin API.

**Human URL:** [https://shardingsphere.apache.org/document/current/](https://shardingsphere.apache.org/document/current/)

#### Tags:

 - Database, Distributed SQL, REST, Apache, Open Source

#### Properties

- [Documentation](https://shardingsphere.apache.org/document/current/)
- [OpenAPI](openapi/apache-shardingsphere-rest-api.yaml)

## Common Properties

- [GitHubOrganization](https://github.com/apache/shardingsphere)
- [Documentation](https://shardingsphere.apache.org/)
- [SpectralRules](rules/apache-shardingsphere-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-shardingsphere-vocabulary.yaml)
- [NaftikoCapability](capabilities/shardingsphere-workflow.yaml)
- [JSON-LD](json-ld/apache-shardingsphere-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Database Sharding | Horizontal database sharding with flexible sharding algorithms |
| Read-Write Splitting | Transparent primary/replica read-write splitting |
| Distributed Transactions | XA and BASE distributed transaction support |
| Data Encryption | Transparent data encryption at the SQL layer |
| Shadow Database | Shadow database for production traffic testing |
| DistSQL | SQL-based distributed database management language |
| Database Federation | Query across heterogeneous database instances |

## Use Cases

| Name | Description |
|------|-------------|
| Database Scale-Out | Horizontally scale relational databases without changing application code |
| Multi-Tenant Sharding | Shard data by tenant ID for SaaS applications |
| Read Scaling | Scale read traffic with primary/replica splitting |
| Data Migration | Online data migration between database clusters |

## Integrations

| Name | Description |
|------|-------------|
| MySQL | MySQL-compatible sharding and proxy |
| PostgreSQL | PostgreSQL protocol support for sharding |
| Apache ZooKeeper | Cluster coordination and configuration storage |
| Spring Boot | ShardingSphere Spring Boot starter for Java applications |
| Kubernetes | Kubernetes operator for cloud-native deployment |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache ShardingSphere REST API](openapi/apache-shardingsphere-rest-api.yaml)

### JSON Schema

- [Database](json-schema/apache-shardingsphere-database-schema.json)
- [Sharding Rule](json-schema/apache-shardingsphere-sharding-rule-schema.json)
- [Data Source](json-schema/apache-shardingsphere-data-source-schema.json)
- [And more...](json-schema/)

### JSON Structure

- [Apache ShardingSphere JSON Structures](json-structure/)

### JSON-LD

- [Apache ShardingSphere Context](json-ld/apache-shardingsphere-context.jsonld)

### Examples

- [Apache ShardingSphere Examples](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Distributed SQL Workflow](capabilities/shardingsphere-workflow.yaml) | Apache ShardingSphere | 7 | Database Administrator, Platform Engineer |

## Vocabulary

- [Apache ShardingSphere Vocabulary](vocabulary/apache-shardingsphere-vocabulary.yaml) — Unified taxonomy mapping distributed SQL resources, actions, workflows, and personas

## Rules

- [Apache ShardingSphere Spectral Rules](rules/apache-shardingsphere-spectral-rules.yml) — Rules enforcing Apache ShardingSphere API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
