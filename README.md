# Azure Database for MySQL (microsoft-azure-mysql)

Azure Database for MySQL is a fully managed relational database service based on the open-source MySQL community edition. Its REST APIs enable management of flexible servers, single servers, databases, firewall and network rules, configurations, replicas, and backups with built-in high availability and automated backups.

**APIs.json:** [https://azure.microsoft.com/en-us/services/mysql/](https://azure.microsoft.com/en-us/services/mysql/)

## Tags

- Database
- Flexible Server
- Managed Database
- MySQL
- Open Source
- Relational Database

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-05-19

## APIs

### Azure Database for MySQL Flexible Servers API

Create and manage MySQL Flexible Servers, including SKU, storage, networking, high availability mode, maintenance windows, and identity. Flexible Server provides granular control and zone redundant high availability for production workloads.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/servers](https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/servers)
- **Base URL:** `https://management.azure.com`

#### Tags

- Flexible Server
- High Availability
- MySQL
- Server Management

#### Properties

- [OpenAPI](openapi/microsoft-azure-mysql-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-azure-mysql.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-mysql.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/servers)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Getting Started](https://learn.microsoft.com/en-us/azure/mysql/flexible-server/quickstart-create-server-portal)

### Azure Database for MySQL Databases API

Create, list, retrieve, and delete databases hosted on a MySQL Flexible Server. Manage character sets and collations for each database within a server.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/databases](https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/databases)
- **Base URL:** `https://management.azure.com`

#### Tags

- Charset
- Collation
- Database
- MySQL

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/databases)
- [Postman Collection](collections/microsoft-azure-mysql.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-mysql.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Database for MySQL Firewall Rules API

Create and manage server-level firewall rules to grant access to a MySQL Flexible Server from specified client IP address ranges. Required for clients connecting from outside the Azure network.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/firewall-rules](https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/firewall-rules)
- **Base URL:** `https://management.azure.com`

#### Tags

- Access Control
- Firewall Rules
- IP Allowlist
- Networking

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/firewall-rules)
- [Reference](https://learn.microsoft.com/en-us/azure/mysql/flexible-server/concepts-networking)
- [Postman Collection](collections/microsoft-azure-mysql.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-mysql.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Database for MySQL Configurations API

Manage server parameters (configurations) for a MySQL Flexible Server. Adjust MySQL engine variables such as character_set_server, time_zone, and innodb_buffer_pool_size to tune performance and behavior.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/configurations](https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/configurations)
- **Base URL:** `https://management.azure.com`

#### Tags

- Configuration
- Parameters
- Server Settings
- Tuning

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/configurations)
- [Reference](https://learn.microsoft.com/en-us/azure/mysql/flexible-server/concepts-server-parameters)
- [Postman Collection](collections/microsoft-azure-mysql.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-mysql.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Database for MySQL Replicas API

Manage read replicas for MySQL Flexible Server to scale out read-heavy workloads. Create replicas in the same or different region for performance and read distribution.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/replicas](https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/replicas)
- **Base URL:** `https://management.azure.com`

#### Tags

- Read Replica
- Replication
- Scale-Out

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/replicas)
- [Reference](https://learn.microsoft.com/en-us/azure/mysql/flexible-server/concepts-read-replicas)
- [Postman Collection](collections/microsoft-azure-mysql.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-mysql.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Database for MySQL Backups API

List and manage automated backups for MySQL Flexible Servers, including on-demand backup creation, retention configuration, and point-in-time restore operations.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/backups](https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/backups)
- **Base URL:** `https://management.azure.com`

#### Tags

- Backup
- Disaster Recovery
- Point-In-Time Restore
- Retention

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/backups)
- [Reference](https://learn.microsoft.com/en-us/azure/mysql/flexible-server/concepts-backup-restore)
- [Postman Collection](collections/microsoft-azure-mysql.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-mysql.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Database for MySQL Administrators API

Configure Azure Active Directory administrators for MySQL Flexible Server. Allows tenant users, groups, or service principals to be designated as MySQL administrators for AAD-based authentication.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/azure-ad-administrators](https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/azure-ad-administrators)
- **Base URL:** `https://management.azure.com`

#### Tags

- AAD
- Administrators
- Authentication
- Identity

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/azure-ad-administrators)
- [Reference](https://learn.microsoft.com/en-us/azure/mysql/flexible-server/concepts-azure-ad-authentication)
- [Postman Collection](collections/microsoft-azure-mysql.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-mysql.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Database for MySQL Check Name Availability API

Check whether a proposed MySQL Flexible Server name is available within the Azure global namespace before creating a new server.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/check-name-availability](https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/check-name-availability)
- **Base URL:** `https://management.azure.com`

#### Tags

- Availability
- Name Validation
- Provisioning

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/check-name-availability)
- [Postman Collection](collections/microsoft-azure-mysql.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-mysql.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Database for MySQL Operations API

List Azure Database for MySQL provider operations available in the subscription, including supported operation types and metadata.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/operations](https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/operations)
- **Base URL:** `https://management.azure.com`

#### Tags

- Operations
- Provider
- Resource Provider

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/operations)
- [Postman Collection](collections/microsoft-azure-mysql.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-mysql.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://portal.azure.com)
- [Documentation](https://learn.microsoft.com/en-us/azure/mysql/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/mysql/flexible-server/quickstart-create-server-portal)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [S D Ks](https://learn.microsoft.com/en-us/azure/mysql/flexible-server/connect-csharp)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/mysql/)
- [Status Page](https://status.azure.com/)
- [Support](https://azure.microsoft.com/en-us/support/options/)
- [Blog](https://azure.microsoft.com/en-us/blog/tag/azure-database-for-mysql/)
- [Changelog](https://learn.microsoft.com/en-us/azure/mysql/flexible-server/whats-new)
- [Terms of Service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [GitHub Organization](https://github.com/Azure)
- [Website](https://azure.microsoft.com/en-us/products/mysql)
- [Login](https://portal.azure.com)
- [Sign Up](https://azure.microsoft.com/en-us/free)
- [L L Ms Txt](https://portal.azure.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
