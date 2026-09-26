# Azure Deployment Notes

This file translates the project report's implementation sequence into an execution checklist.

## Resource Naming Convention
Use a consistent naming scheme, for example:
- Resource Group: `rg-public-portal`
- Front Door profile: `afd-public-portal`
- WAF policy: `waf-public-portal`
- Storage/App Service origin: `origin-public-portal`

Choose names that comply with Azure naming rules and your team's subscription policies.

## Origin Option A – Azure Storage
Use a Storage Account configured for static website hosting and upload the contents of `portal/`.

## Origin Option B – Azure App Service
Deploy the `portal/` static site through an App Service-compatible deployment method.

## Front Door
Configure:
- Front Door profile
- Origin group
- Origin
- Endpoint
- Route
- HTTPS
- Caching for appropriate static content

## WAF
Configure a WAF policy and associate it with the Front Door security configuration. Review logs and tune rules carefully to reduce false positives.

## Custom Domain
Add the domain to Front Door, configure the required DNS records, validate the domain, and enable HTTPS/TLS.

## Final Verification
Confirm:
- Portal loads
- Custom domain resolves
- HTTPS works
- Static files load
- Repeat static requests can be served from cache
- WAF security behavior is visible in logs/events
- Cache purge delivers updated content
- Front Door can reach the origin

## Important
Azure Portal screens and resource options can change. Use the current Azure Portal interface for the actual deployment and capture screenshots from the team's own subscription.
