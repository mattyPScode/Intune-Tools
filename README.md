# Intune Apps Analyzer

Intune Apps Analyzer is a professional PowerShell-based GUI tool designed for Microsoft Intune administrators to analyze mobile application assignments through Microsoft Graph API.

The application provides a fast and intuitive way to inspect Include/Exclude group assignments and export detailed reports for auditing and troubleshooting purposes.

![Application](IntuneAppsAnalyzer/Screenshots/Application.jpg)
---

## Features

- Assignment Analysis
- Identify applications without assignments
- Get applications Information
- Export results to CSV/HTML
- Export results to CSV
- Export results to HTML

### Security
- Read-only Microsoft Graph permissions
- No modification of Intune configuration
- Safe for production environments

---

## Requirements

### Microsoft Graph Permissions
The following delegated permissions are required:

- `DeviceManagementApps.Read.All`
- `Group.Read.All`

Admin consent may be required depending on tenant configuration.

---
## Example Use Cases

- Intune environment auditing
- Assignment troubleshooting
- Security reviews
- Deployment verification
- Reporting and documentation
- Tenant cleanup operations

---

## Technologies Used

- PowerShell
- WPF (Windows Presentation Foundation)
- Microsoft Graph API
- XAML
