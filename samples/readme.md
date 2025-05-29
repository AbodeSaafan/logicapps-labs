# Logic Apps Samples

You can use this folder to share Logic Apps sample.

## List of Samples

- [**Sample Logic Apps Workspace**](./sample-logicapp-workspace/): This is a simple request response project, just to exemplify the required structure.

## How to contribute

Follow the instructions bellow before sharing projects.

- Create one folder for each sample.
- Your sample project should be created in VS Code as a workspace.

### Readme at the workspace root

You must include a readme.md file at your workspace root folder - at the same level you include the workspace file. This document should include:

- A description of the project and each workflow.
- Required connections
- Deployment instructions

### Logic Apps Project

The Logic Apps Project should be called LogicApps. The project folder should include the following files:

- **cloud.settings.json** - create a file called cloud.setting.json with the keys that are required by customers to recreate the local.settings.json
- **readme.md** - include a readme.md file with instructions to recreate local.settings.json and recover keys and URLs required.

### Deployment Scripts

If you are providing deployment scripts to Azure Portal or to regenerate Azure connectors, add a Deployment folder to the workspace and provide the scripts under this folder.
