# 4. Implementation Procedure

## Step 1 – Create Azure Resource Group
Create a resource group in Azure Portal to organize all project resources.

**Evidence:** Capture the Resource Group overview showing the project resource group.

## Step 2 – Deploy the Public Portal
Host the web application using Azure Storage or Azure App Service.

**Evidence:** Capture the deployed portal and the hosting resource overview.

## Step 3 – Create Azure Front Door
Create an Azure Front Door profile and configure the portal as the origin.

**Evidence:** Capture the Front Door profile overview.

## Step 4 – Configure Endpoint and Route
Create the Front Door endpoint and route requests to the origin.

**Evidence:** Capture the endpoint/route configuration.

## Step 5 – Enable Caching
Enable caching for suitable static resources. Do not cache dynamic, personalized, authentication, or sensitive API content.

**Evidence:** Capture the route/cache configuration and a cache test.

## Step 6 – Configure WAF
Create a WAF policy and associate it with the Front Door endpoint.

**Evidence:** Capture WAF policy configuration and security logs/test result.

## Step 7 – Configure Custom Domain
Add the required domain and configure the DNS records.

**Evidence:** Capture domain validation/configuration.

## Step 8 – Configure HTTPS
Enable HTTPS/TLS for the custom domain.

**Evidence:** Capture the HTTPS/TLS status and a browser HTTPS test.

## Step 9 – Test the Portal
Test:
- Website accessibility
- HTTPS connectivity
- Cache behavior
- WAF protection
- Custom domain functionality
- Origin connectivity
