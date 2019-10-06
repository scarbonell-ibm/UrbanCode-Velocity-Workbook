```json
{
  "tenantId": "123p498fp9832y4iuhsfu",
  "description": null,
  "query": "",
  "phases": [
    {
      "name": "Planning",
      "description": "",
      "stages": [
        {
          "name": "Backlog",
          "query": "",
          "description": "",
          "wipLimit": null,
          "gates": null
        },
        {
          "name": "Selected for Development",
          "query": "",
          "description": "",
          "wipLimit": null,
          "gates": null
        }
      ]
    },
    {
      "name": "Development",
      "description": "",
      "stages": [
        {
          "name": "In Progress",
          "query": "",
          "description": "",
          "wipLimit": 10,
          "gates": null
        },
        {
          "name": "In Review",
          "query": "",
          "description": "",
          "wipLimit": 5,
          "gates": null
        },
        {
          "name": "Merged",
          "query": "",
          "description": "",
          "wipLimit": null,
          "gates": null
        },
        {
          "name": "Latest Build",
          "query": "",
          "description": "",
          "wipLimit": null,
          "gates": null
        }
      ]
    },
    {
      "name": "Deployment",
      "description": "",
      "stages": [
        {
          "name": "DEV",
          "query": "",
          "description": "",
          "wipLimit": null,
          "gates": null
        },
        {
          "name": "PROD",
          "query": "",
          "description": "",
          "wipLimit": null,
          "gates": null
        }
      ]
    }
  ],
  "leadTime": {
    "start": "Backlog",
    "end": "PROD"
  },
  "cycleTime": {
    "start": "In Progress",
    "end": "PROD"
  },
  "mappings": {
    "priority": {
      "Lowest": [
        "Lowest"
      ],
      "Low": [
        "Low"
      ],
      "Medium": [
        "Medium"
      ],
      "High": [
        "High"
      ],
      "Highest": [
        "Highest"
      ]
    }
  },
  "integrations": [],
  "linkRules": [],
  "metrics": null,
  "metricsBar": null
}
````