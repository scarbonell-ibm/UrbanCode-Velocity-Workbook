```json
{
  "_id": "5d93994e61b513280db74e59",
  "pipelineId": "fe0758c9-09d2-4f24-81fe-d5c85b8ced4d",
  "tenantId": "5ade13625558f2c6688d15ce",
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
          "name": "QA",
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
  "integrations": [
    {
      "_id": "5d8f9b54a7be2471b38011b9",
      "type": "ucv-ext-github",
      "tenant_id": "5ade13625558f2c6688d15ce",
      "name": "d_app 🚀 (GitHub)",
      "properties": {
        "url": "https://github.com/UrbanCodeVelocity/d_app",
        "name": "d_app",
        "owner": "UrbanCodeVelocity",
        "apiUrl": "https://api.github.com",
        "token": "****"
      },
      "disabled": false,
      "latest": false,
      "startTime": -,
      "status": "success"
    },
    {
      "_id": "5d9365fda7be24285b8011ba",
      "type": "ucv-ext-jira",
      "tenant_id": "5ade13625558f2c6688d15ce",
      "name": "d_app 🚀 (Jira)",
      "properties": {
        "baseUrl": "https://microservice.atlassian.net",
        "username": "sylvain.carbonell@hcl.com",
        "password": "****",
        "jiraProjects": [
          "DA"
        ]
      },
      "disabled": true,
      "latest": false,
      "startTime": 1569966673917,
      "status": "success",
      "tenantId": "5ade13625558f2c6688d15ce"
    }
  ],
  "linkRules": [],
  "metrics": null,
  "metricsBar": null
}
```