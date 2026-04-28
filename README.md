# Sentinel

A personal collection of Microsoft Sentinel content, including analytics rules, hunting queries, workbooks, playbooks, and other security operations resources.

## Overview

This repository contains custom Microsoft Sentinel components intended to support security monitoring, threat detection, investigation, automation, and response activities.

The content may include:

- Analytics rules
- Hunting queries
- Exploration queries
- Playbooks
- Workbooks
- KQL queries
- Other Microsoft Sentinel-related resources

## Repository Structure

```text
.
├── analytics/   # Detection rules and analytics content
├── playbooks/   # Automation playbooks and response workflows
├── workbooks/   # Microsoft Sentinel workbook definitions
└── README.md
```

## Usage

You can use the content in this repository as a reference or starting point for your own Microsoft Sentinel environment.

Before deploying any content:

1. Review the logic and configuration.
2. Validate the query or template in a test environment.
3. Adjust tenant-specific values, table names, parameters, and thresholds.
4. Confirm that the content matches your organization’s security requirements.
5. Deploy only after proper testing and approval.

## Requirements

Depending on the specific component, you may need:

- Microsoft Sentinel enabled in an Azure subscription
- A Log Analytics workspace
- Appropriate permissions to deploy analytics rules, workbooks, or playbooks
- Relevant data connectors enabled
- Azure Logic Apps permissions for playbooks
- Knowledge of KQL for query customization

## Disclaimer

This is a personal repository and is not an official Microsoft Sentinel repository.

All content is provided as-is, without warranty of any kind. Use it at your own risk. You are responsible for reviewing, testing, validating, and maintaining any content before using it in a production environment.

## Contributing

Contributions, suggestions, and improvements are welcome. If you find an issue or have an idea for enhancement, feel free to open a pull request or submit feedback.

## License

No license has been specified for this repository. Unless a license is added, all rights are reserved by the repository owner.
