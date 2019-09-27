UrbanCode Velocity
VSM Workbook
v1.0 (9/24/2019)

### [Scenario 1: Basic Value Stream Management (VSM) with JIRA, GitHub, Jenkins](scenario_1.md)

The goal of this scenario is to create a brand-new value stream along with supporting integrations and to exercise it from beginning to end.

#### Before Starting
1. UrbanCode Velocity
   1.	Installed
    2.	Access to user account with roles/permissions to create a value stream and add integrations.
2. External
   1. Instances and accounts for the following:
      1.	JIRA (on premise or cloud)
      2.	GitHub (on premise or cloud)
      3.	Jenkins (on premise)
   2.	Network
   1.	Velocity has network access to instances of the following: JIRA, GitHub, and Jenkins
   2.	The following have network access to Velocity: Jenkins
3. Host system access (nice to have)
   1.	Velocity host system
   2.	Jenkins host system
___

#### Getting Started
1. [Frame New Value Stream](valueStream/valueStream.md)
   1.	Create new value stream
   2.	Define stages: Introduction to VSM json
2. Setup data sources
   1. Create integrations
      1. [JIRA](jira/jiraIntegration.md)
      2.	GitHub
      3. [Jenkins](jenkinsPlugin/jenkinsPlugin.md)
   2.	Add integrations to value stream
   3.	Confirm that integrations are working
3. Create stage queries
4. Create link rules
5. Full run of value stream
   1.	Perform external actions from planning to deployment
   2.	Experiment with order of actions and value stream setup