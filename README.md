# Azure Front Door with Caching and WAF for a Public Portal

**Project Code:** 24CC3046-P027  
**Academic Year:** 2026–2027  
**Branch:** Computer Science and Engineering (CSE)  
**Institution:** KL University Academic

## Team
| ID | Name |
|---|---|
| 2400032145 | Kilaru kohima |
| 2400032033 | Keerthana |
| 2400032042 | Sandeep |
| 240003228 | Meghana |

## Project Overview
This project demonstrates a secure and high-performance public web portal using Microsoft Azure. Azure Front Door acts as the global entry point, edge caching improves delivery of frequently requested static resources, and Azure Web Application Firewall (WAF) provides an additional security layer.

The implementation scope includes:
- Public portal hosting
- Azure Front Door
- Edge caching
- WAF policy
- HTTPS/TLS
- Custom domain
- Cache and security testing
- Monitoring and troubleshooting

## Repository Structure
```text
azure-front-door-public-portal/
├── README.md
├── .gitignore
├── submission-checklist.md
├── docs/
│   ├── 01-project-abstract.md
│   ├── 02-project-architecture.md
│   ├── 03-technologies-and-services.md
│   ├── 04-implementation.md
│   ├── 05-testing-and-evidence.md
│   ├── 06-cache-policy.md
│   └── 07-bottlenecks-and-solutions.md
├── tasks/
│   ├── task-1-resource-group.md
│   ├── task-2-public-portal.md
│   ├── task-3-front-door-and-caching.md
│   ├── task-4-waf.md
│   └── task-5-domain-https-testing.md
├── architecture/
│   └── architecture.svg
├── portal/
│   ├── index.html
│   ├── styles.css
│   └── script.js
├── azure/
│   └── deployment-notes.md
└── screenshots/
    └── README.md
```

## Important Evidence Note
The repository contains the complete project documentation, architecture diagram, portal source, implementation procedure, and task evidence checklists.

**Do not upload invented Azure Portal screenshots.** For the final submission, replace the screenshot placeholders in `screenshots/` with screenshots captured from the team's actual Azure environment after each task is executed.

## Source Basis
The project documentation follows the uploaded project report for:
- Abstract and objectives
- Technology list
- Module descriptions
- Implementation sequence
- Cache policy
- Bottlenecks and solutions
- Testing cases
- Expected results
- Limitations and future enhancements

## Quick Start: Local Portal
Open `portal/index.html` in a browser, or serve the `portal/` directory with any static HTTP server.

Example:
```bash
cd portal
python -m http.server 8080
```
Then open `http://localhost:8080`.

## Azure Implementation Order
1. Create Resource Group
2. Deploy the Public Portal
3. Create Azure Front Door
4. Configure endpoint and route
5. Enable caching
6. Configure WAF
7. Configure custom domain
8. Configure HTTPS/TLS
9. Execute testing and capture evidence

See the `tasks/` directory for task-by-task documentation.
