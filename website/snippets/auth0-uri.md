
The URI used for SSO connections on multi-tenant dbt Cloud instances will vary based on your dbt Cloud hosted region. Use your login URL (also referred to as your Access URL) to determine the correct Auth0 URI for your environment.

| Region              | dbt Cloud Access URL | Auth0 SSO URI &lt;YOUR_AUTH0_URI&gt; | Auth0 Entity ID &lt;YOUR_AUTH0_ENTITYID&gt;* |
|---------------------|-----------------------|-------------------------------|----------------------------------------------------|
| AWS NA multi-tenant | cloud.getdbt.com      | auth.cloud.getdbt.com         | us-production-mt                                   |
| AWS NA cell 1       | \{account prefix\}.us1.dbt.com | auth.cloud.getdbt.com| us-production-mt                                   |
| AWS EMEA            | emea.dbt.com          | auth.emea.dbt.com             | emea-production-mt                                 |
| AWS APAC            | au.dbt.com            | auth.au.dbt.com               | au-production-mt                                   |
| Azure NA            | \{account prefix\}.us2.dbt.com | auth.cloud.getdbt.com| us-production-mt                                   |
| Azure EMEA          | \{account prefix\}.eu2.dbt.com | auth.emea.dbt.com    | emea-production-mt                                 |

*Only applicable to SAML and Okta configurations.
