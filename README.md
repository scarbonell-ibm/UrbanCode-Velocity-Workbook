UrbanCode Velocity Workbook
last updated for Velocity 1.3.0

## Scenario 1: Introduction to Value Streams (with JIRA, GitHub, Jenkins)

### Objective
Create a value stream with Jira, Github, and Jenkins integrations and excercise it from beginning to end.

### Description
First, we will create the integrations that we need. This is mostly done through the Velocity settings page with some inclusion of the external tools we're integrating. In the case of Jenkins, we will need to install the UrbanCode Velocity plugin on the Jenkins server.

After creating integrations, we will frame-out a [new value stream](valueStream/valueStream.md) by defining its phases and stages. We will be introduced to the vsm.json file and its configuration importance. We will use this file to [add the Jira and GitHub integrations](valueStream/addIntegrations/addIntegrations.md) to the value stream (the Jenkins integration does not need to be added this way). After this, we will create [stage queries](valueStream/stageQueries/stageQueries.md) to map work item state to particular stages. We will then create [link rules](valueStream/linkRules/linkRules.md) to map data from different sources to a single unit of interest (a work item or "dot").

Finally, we can mimic process activity between Velocity and external tools, all the way from planning to deployment, and observe the dot as it moves through these stages. It's a good idea to experiment with the value stream features such as dot behavior, stage definitions, pipelines, and history while imagining the value it can bring to your own processes.

### Before Starting
1. UrbanCode Velocity
   1.	Installed
    2.	Access to user account with roles/permissions to create a value stream and add integrations.
2. External
   1. Instances and accounts for the following:
      1.	JIRA (on premise or cloud)
      2.	GitHub (on premise or cloud)
      3.	Jenkins (on premise)
   2. Network
      1.	Velocity has network access to instances of the following: JIRA, GitHub, and Jenkins
      2.	The following have network access to Velocity: Jenkins
3. Host system access (nice to have)
   1.	Velocity host system
   2.	Jenkins host system

---

### Workbook Outline

Follow each step (follow links for details).

1. Create integrations
   1. [Jira](jira/jiraIntegration.md)
   2.	[GitHub](github/githubIntegration.md)
   3. [Jenkins](jenkinsPlugin/jenkinsPlugin.md)
2. Setup value stream
   1. [Create a new Value Stream](valueStream/valueStream.md)
   2. [Configure value stream stage queries](valueStream/stageQueries/stageQueries.md)
   3. [Configure value stream link rules](valueStream/linkRules/linkRules.md)
3. Move items through value stream
   1.	Perform external actions from planning to deployment
   2.	Experiment with order of actions and value stream setup

*--- YouTube Playlist ---*
[![YouTube Playlist](general/YouTubePlaylist.PNG)](https://www.youtube.com/playlist?list=PLDq88EzQBSsAcitaMxyYapVhDeHQELxXC)

---
*This content is supplemental. Please also refer to version specific product documentation.*
![Documentation can be accessed in the upper right of Velocity](general/docs.png)
