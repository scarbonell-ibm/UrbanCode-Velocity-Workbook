### Link Rules

Link rules combine data from separate sources into the same work item. You can configure a link rule within the vsm.json file and upload it to Velocity. For instance, to link GitHub pull requests from the integration named "GitHub_Integration_1" with Jira items from the integration named "Jira_Integration_1" use a link rule as follows:

```json
      "linkRules": [
        {
          "fromIntegrationName": "GitHub_Integration_1",
          "toIntegrationName": "Jira_Integration_1",
          "fromField": "pr.name",
          "toField": "issue.id",
          "pattern": "([A-Z]+-[0-9]+)"
        }
      ],
```