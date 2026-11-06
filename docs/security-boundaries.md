# Security and release boundaries

Do not commit secrets, recovery codes or customer data. Do not merge or migrate production identity, request or store data based on matching names or email addresses.

Production deployment, payment configuration, DNS changes, Shopify checkout changes, production data migration and deletion require separate explicit approval. Local test success is not production acceptance.

The local Vendure dependency audit identified high-severity findings requiring review and remediation before acceptance. License and dependency reviews remain open. Tenant isolation must be demonstrated through direct API tests for each relevant resource.
