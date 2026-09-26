# Task 3 – Azure Front Door and Caching

## Objective
Configure Azure Front Door as the global entry point and enable caching for suitable static resources.

## Procedure
1. Create an Azure Front Door profile.
2. Create/configure the origin group.
3. Add the deployed portal as the origin.
4. Create an endpoint.
5. Create a route to the origin.
6. Enable caching for suitable static resources.
7. Ensure dynamic, personalized, authentication, and sensitive API content is not cached.
8. Open the Front Door endpoint and verify that the portal is accessible.
9. Repeat a static resource request and inspect the available response/cache information.

## Expected Result
Front Door routes users to the origin and suitable static resources can be delivered from edge cache.

## Screenshot Evidence Required
- Screenshot 1: Front Door profile.
- Screenshot 2: Origin/origin group.
- Screenshot 3: Endpoint and route.
- Screenshot 4: Cache configuration.
- Screenshot 5: Front Door endpoint serving the portal.

> Replace the screenshot placeholders in `screenshots/task-3/` with actual screenshots.
