# 2. Project Architecture

## Architecture Flow

```text
User / Browser
      |
      | HTTPS
      v
+----------------------+
| Azure Front Door     |
| Global Entry Point   |
+----------+-----------+
           |
     +-----+------+
     |            |
     v            v
+---------+   +---------+
|  Edge   |   |  WAF    |
| Cache   |   | Policy  |
+----+----+   +----+----+
     |             |
     +------+------+
            |
            v
+----------------------+
| Origin                |
| Azure Storage /       |
| Azure App Service     |
| Public Portal         |
+----------------------+
```

## Components

1. **User/Browser** – Sends HTTPS requests to the public portal.
2. **Azure Front Door** – Acts as the global entry point and routes requests to the origin.
3. **Edge Cache** – Stores frequently requested static resources such as images, CSS, JavaScript, and suitable static HTML.
4. **Azure WAF** – Inspects HTTP/HTTPS traffic and helps identify malicious requests.
5. **Origin** – Hosts the actual public portal using Azure Storage or Azure App Service.
6. **Custom Domain + HTTPS/TLS** – Provides a professional URL and encrypted communication.

## Request Behaviour

- If suitable content exists in the edge cache, it can be delivered without repeatedly contacting the origin.
- If content is not cached or is dynamic, Front Door forwards the request to the origin.
- WAF inspects incoming traffic as part of the security layer.
- Authentication, personalized content, and sensitive API responses should not be cached.
