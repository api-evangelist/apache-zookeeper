# Apache ZooKeeper (apache-zookeeper)

Apache ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services for distributed systems. It provides a hierarchical key-value store (znodes), watches for change notifications, ephemeral nodes for presence detection, and sequential nodes for leader election and distributed locking. ZooKeeper exposes a Java/C client API and an HTTP Admin Server API for monitoring and management. It is widely used by Kafka, Hadoop, HBase, Storm, and other distributed systems.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-zookeeper/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-zookeeper/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Configuration Management
- Distributed Coordination
- Leader Election
- Service Discovery
- Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Apache ZooKeeper Admin Server API

The ZooKeeper Admin Server provides HTTP endpoints on port 8080 that expose the four-letter-word equivalent commands as REST endpoints for cluster monitoring, configuration, and diagnostics. Endpoints include /commands/conf (server configuration), /commands/stats (server statistics), /commands/mntr (monitoring metrics), /commands/envi (environment info), /commands/dump (session/ephemeral node dump), /commands/crst (connection reset), and /commands/leader (leader info for QuorumPeerMain).

- **Human URL:** [https://zookeeper.apache.org/doc/current/zookeeperAdmin.html#sc_4lw](https://zookeeper.apache.org/doc/current/zookeeperAdmin.html#sc_4lw)
- **Base URL:** `http://localhost:8080/commands`

#### Tags

- REST
- Admin
- Monitoring
- Cluster Management

#### Properties

- [Documentation](https://zookeeper.apache.org/doc/current/zookeeperAdmin.html#sc_4lw)
- [OpenAPI](openapi/zookeeper-admin-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zookeeper-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zookeeper-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache ZooKeeper Client API

The ZooKeeper client API provides Java and C language bindings for distributed coordination operations. Operations include create (create znodes), delete, exists (check existence), getData, setData, getChildren, getACL, setACL, and multi (batch operations). Watch mechanisms notify clients of znode changes. Curator is the recommended high-level Java client with recipes for distributed locks, leader elections, service discovery, and caches.

- **Human URL:** [https://zookeeper.apache.org/doc/current/zookeeperProgrammers.html](https://zookeeper.apache.org/doc/current/zookeeperProgrammers.html)

#### Tags

- Java
- C
- Coordination
- Leader Election

#### Properties

- [Documentation](https://zookeeper.apache.org/doc/current/zookeeperProgrammers.html)
- [API Reference](https://zookeeper.apache.org/doc/current/apidocs/zookeeper-server/)
- [SDK](https://search.maven.org/search?q=org.apache.zookeeper)
- [SDK](https://curator.apache.org/)
- [Postman Collection](collections/zookeeper-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zookeeper-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Repository](https://github.com/apache/zookeeper)
- [Documentation](https://zookeeper.apache.org/doc/current/)
- [Portal](https://zookeeper.apache.org/)
- [Getting Started](https://zookeeper.apache.org/doc/current/zookeeperStarted.html)
- [Release Notes](https://github.com/apache/zookeeper/releases)
- [Support](https://zookeeper.apache.org/lists.html)
- [Terms of Service](https://www.apache.org/licenses/)
- [Spectral Rules](rules/apache-zookeeper-spectral-rules.yml)
- [SDK](https://pypi.org/project/kazoo/)
- [SDK](https://www.npmjs.com/package/node-zookeeper-client)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
