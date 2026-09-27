# Task 5 – Custom Domain, HTTPS and Final Testing

## Objective
Configure the custom domain and HTTPS/TLS and execute the final portal tests.

## Procedure
1. Add the custom domain to Front Door.
2. Configure the required DNS records with the domain provider.
3. Validate the domain.
4. Enable HTTPS/TLS using the supported certificate configuration.
5. Open the custom domain in a browser.
6. Verify the secure HTTPS connection.
7. Test portal accessibility.
8. Test static resources.
9. Test cache behavior.
10. Test WAF behavior using the authorized controlled test.
11. Verify origin connectivity.
12. Purge cache when required and verify updated content.

## Expected Result
The public portal is accessible through the custom HTTPS domain, static content is delivered efficiently, WAF protection is active, and the origin is reachable through Front Door.

## Screenshot Evidence Required
- Screenshot 1: Custom domain configuration.
- Screenshot 2: DNS/domain validation.
- Screenshot 3: HTTPS/TLS enabled.
- Screenshot 4: Browser showing custom HTTPS domain.
- Screenshot 5: Final testing evidence.

<img width="1897" height="1021" alt="image" src="https://github.com/user-attachments/assets/8f47e981-f26d-4314-b236-37517f414373" />
ambitious-coast-06fe79200.2.azurestaticapps.net → Validated ✅
“Here we can see that the domain has been successfully validated by Azure.”
https://ambitious-coast-06fe79200.2.azurestaticapps.net

<img width="1907" height="1025" alt="image" src="https://github.com/user-attachments/assets/f07d38e0-cef9-4946-9208-11e87ecf2034" />
<img width="1912" height="561" alt="image" src="https://github.com/user-attachments/assets/2c060b67-6b59-4fcd-a6c2-0b7f2724e2fc" />
<img width="1898" height="677" alt="image" src="https://github.com/user-attachments/assets/c1fc534c-d0f5-47bf-a8d5-aca35456adfd" />
<img width="1907" height="870" alt="image" src="https://github.com/user-attachments/assets/87db239d-69d4-43f4-a9cd-16df3846a831" />


> Replace the screenshot placeholders in `screenshots/task-5/` with actual screenshots.
