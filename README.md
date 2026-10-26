# Azure Database for MySQL (microsoft-azure-mysql)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
