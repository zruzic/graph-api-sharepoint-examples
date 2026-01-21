# Microsoft Graph API for SharePoint Online

This repository contains my personal collection of Microsoft Graph API request examples focused on SharePoint Online.

## Features

- Authentication using client credentials flow  
- File and Document Set management (create, upload, move, delete)  
- Site and list provisioning and lifecycle management  
- Sharing and permissions management  
- Compliance label handling  
- SharePoint page creation, publishing, and web part management  

## Usage

### API Collections (GUI Clients)

Import the collection file that matches your preferred API client:

- **Postman**: [GraphAPI Online SharePoint Postman Version.json](GraphAPI%20Online%20SharePoint%20Postman%20Version.json)  
- **Bruno**: [GraphAPI Online SharePoint Bruno Version.json](GraphAPI%20Online%20SharePoint%20Bruno%20Version.json)  

### PowerShell Module (Automation)

Located in the [`PowerShell/`](PowerShell) folder. Ideal for Windows admins and scheduled tasks.  
Includes the `GraphAPI-Client.psm1` module and example scripts demonstrating common operations.

### Python Scripts (Cross-Platform)

Located in the [`Python/`](Python) folder. Ideal for cross-platform automation and integration.  
Uses the `requests` library. See `Python/requirements.txt` for dependencies.

## Documentation

Detailed API endpoint descriptions and request examples are available in the included HTML documentation:  
[Docs/GraphAPI - SharePoint-documentation.html](Docs/GraphAPI%20-%20SharePoint-documentation.html)


## Contributing

This is a personal collection, but suggestions and improvements are welcome via issues or pull requests.

---

*Please ensure you do not commit any real secrets or credentials. Use environment variables or local config files ignored by Git.*

<img width="596" height="685" alt="GraphAPI-Online-SharePoint" src="https://github.com/user-attachments/assets/f59f6468-62dd-4a87-afe4-70d674e663cb" />
