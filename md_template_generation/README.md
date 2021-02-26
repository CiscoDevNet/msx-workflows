# OpenSource MSX Managed Device Workflows
This repository includes OpenSource workflows that are to be used with Managed Device to provide some extra functionality or as tools to perform some specific actions.


## Template Generation Workflow
Managed Device can be used to generate Device Templates from CLI command list. As long as the CLI NED is loaded on the Managed Device NSO, this workflow can be invoked from MSX UI, from the Workflow section - it will show up as *MD Template Generation Workflow*.


### Importing the workflow
This workflow will create a JSON RPC Account Key (*md-nso-credentials*) and an NSO target for the MD NSO (*md-nso-target*).


#### Configuring Account Key
Please fill in the username and password (marked by **REPLACE ME**) in the *md-nso-credentials* account key before importing. Please reach out to the MSX team for information.


#### Configuring Target
By default, the target is configured for a production environment. If you would like to run this against a local install or mini-msx install, please replace **host**  value in the *md-nso-target* target to point to your system.


## License
MIT licensed. See the LICENSE file for details.
