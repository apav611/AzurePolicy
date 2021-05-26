# Configure Azure App Service with Private Endpoint

Internal App Services should restrict access to a private IP on an internal VNet. The following Azure Policy deploys a Private Link into a designated Subnet based on designated tag keypair tagName:tagValue.

# Tagging Example

tagName: Type <br>
tagValue: Internal or External

Complimentary Policy requiring tagging and allowed values on App Service needed to enforce guardrail.
