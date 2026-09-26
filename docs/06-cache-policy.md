# 6. Cache Management Policy

Caching reduces the number of requests sent to the origin server.

| Content Type | Cache |
|---|---|
| Images | Yes |
| CSS | Yes |
| JavaScript | Yes |
| Static pages | Yes, when appropriate |
| Login pages | No |
| User-specific information | No |
| Sensitive API responses | No |

## Stale Cache
Users may temporarily receive older content after an update.

### Mitigation
- Configure suitable cache expiration.
- Use versioned static files where appropriate.
- Purge cache when important content changes.
