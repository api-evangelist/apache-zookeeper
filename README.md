# Apache ZooKeeper (apache-zookeeper)
Apache ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and group services for distributed systems. It is widely used by Kafka, Hadoop, HBase, Storm, and Solr for coordination, leader election, and service discovery.

**URL:** [https://zookeeper.apache.org/](https://zookeeper.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Configuration Management, Distributed Coordination, Leader Election, Service Discovery, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache ZooKeeper Admin Server API
HTTP endpoints on port 8080 exposing four-letter-word equivalent commands for cluster monitoring, configuration, and diagnostics including /commands/conf, /commands/stats, /commands/mntr, and /commands/leader.

**Human URL:** [https://zookeeper.apache.org/doc/current/zookeeperAdmin.html#sc_4lw](https://zookeeper.apache.org/doc/current/zookeeperAdmin.html#sc_4lw)

#### Tags:

 - REST, Admin, Monitoring, Cluster Management

#### Properties

- [Documentation](https://zookeeper.apache.org/doc/current/zookeeperAdmin.html#sc_4lw)
- [OpenAPI](openapi/zookeeper-admin-api.yml)

### Apache ZooKeeper Client API
Java and C language bindings for distributed coordination operations including create, delete, getData, setData, getChildren, watches, and multi-operation batches.

**Human URL:** [https://zookeeper.apache.org/doc/current/zookeeperProgrammers.html](https://zookeeper.apache.org/doc/current/zookeeperProgrammers.html)

#### Tags:

 - Java, C, Coordination, Leader Election

#### Properties

- [Documentation](https://zookeeper.apache.org/doc/current/zookeeperProgrammers.html)
- [APIReference](https://zookeeper.apache.org/doc/current/apidocs/zookeeper-server/)
- [Java Maven SDK](https://search.maven.org/search?q=org.apache.zookeeper)
- [Apache Curator (High-Level Java Client)](https://curator.apache.org/)

## Common Properties

- [GitHubRepository](https://github.com/apache/zookeeper)
- [Documentation](https://zookeeper.apache.org/doc/current/)
- [Portal](https://zookeeper.apache.org/)
- [GettingStarted](https://zookeeper.apache.org/doc/current/zookeeperStarted.html)
- [ReleaseNotes](https://github.com/apache/zookeeper/releases)
- [Support](https://zookeeper.apache.org/lists.html)
- [TermsOfService](https://www.apache.org/licenses/)
- [SpectralRules](rules/apache-zookeeper-spectral-rules.yml)
- [Python Kazoo Client](https://pypi.org/project/kazoo/)
- [Node.js Client](https://www.npmjs.com/package/node-zookeeper-client)

## Features

| Name | Description |
|------|-------------|
| Hierarchical Namespace | Tree-structured znode namespace for organized configuration storage. |
| Watch Notifications | Client watches trigger one-time callbacks on znode change events. |
| Ephemeral Nodes | Nodes that disappear on session expiry for presence detection. |
| Sequential Nodes | Auto-incrementing sequential znodes for distributed queues and leader election. |
| Atomic Operations | Compare-and-set and multi-operation batches for consistent state updates. |
| ACL Security | Per-znode access control lists for authentication and authorization. |
| Observer Mode | Read-only observer servers for scaling read throughput. |

## Use Cases

| Name | Description |
|------|-------------|
| Leader Election | Distributed leader election using ephemeral sequential znodes. |
| Distributed Configuration Management | Centralized configuration with watch-based change notification. |
| Service Registry and Discovery | Service registration and lookup using ephemeral znodes. |
| Distributed Locking | Distributed mutex and read/write locks using ephemeral sequential znode recipes. |
| Cluster Coordination | Kafka broker coordination, HBase region server management, and Hadoop NameNode fencing. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Kafka | ZooKeeper (legacy) for Kafka broker metadata and controller election. |
| Apache HBase | ZooKeeper for HBase region server coordination and master election. |
| Apache Hadoop | ZooKeeper for HDFS NameNode HA fencing and YARN ResourceManager HA. |
| Apache Storm | ZooKeeper for Storm Nimbus coordination and worker heartbeat tracking. |
| Apache Solr | ZooKeeper for SolrCloud cluster coordination and leader election. |
| Apache Curator | High-level ZooKeeper client with recipes for common distributed patterns. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache ZooKeeper Admin Server API](openapi/zookeeper-admin-api.yml)

## Rules

- [Apache ZooKeeper Spectral Rules](rules/apache-zookeeper-spectral-rules.yml) — 10 rules across 5 categories enforcing Apache ZooKeeper API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
