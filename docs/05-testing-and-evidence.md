# 5. Testing and Evidence

| Test Case | Expected Result | Evidence |
|---|---|---|
| Open portal | Portal loads successfully | Screenshot |
| Open custom domain | Domain resolves correctly | Screenshot |
| Access using HTTPS | Secure connection established | Screenshot |
| Request static files | Files load successfully | Screenshot |
| Repeat static request | Cached content is delivered | Screenshot/log |
| Malicious request | WAF detects/blocks request | Screenshot/log |
| Purge cache | Updated content is delivered | Screenshot |
| Origin connectivity | Front Door reaches origin | Screenshot |

## Evidence Rule
Only screenshots captured from the actual project Azure environment should be submitted as execution evidence. The repository provides placeholders and documentation so that the team can insert genuine screenshots after executing each step.
