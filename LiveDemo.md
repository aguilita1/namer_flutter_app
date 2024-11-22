# DevOps Managed Services (Azure Pipelines)

### Walk through reference implementation
* https://github.com/aguilita1/namer_flutter_app
* [Microsoft-hosted agents](https://learn.microsoft.com/en-us/azure/devops/pipelines/agents/hosted?view=azure-devops&tabs=yaml#software)
  * Using [macOS 14](https://github.com/actions/runner-images/blob/main/images/macos/macos-14-Readme.md#macos-14) because it has xcode v15.4 
* [Azure Pipeline Documentation](https://learn.microsoft.com/en-us/azure/devops/pipelines/?view=azure-devops)

### Walk through Continuous Integration pipeline
* https://github.com/aguilita1/namer_flutter_app/blob/main/.ado/azure-pipeline-streamline-android.yml
  * [Set pipeline variable in bash script](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/set-variables-scripts?view=azure-devops&tabs=bash) e.g. $(minSdkVersion)
  * Note pipeline variable ``$(JAVA_HOME_17_X64)`` predefined variables specific to Microsoft-hosted agent
  * Review variable groups and Secure files
* https://github.com/aguilita1/namer_flutter_app/blob/main/.ado/azure-pipeline-streamline-ios.yml

* Note ``DOCKERHUB_TOKEN`` and ``DOCKERHUB_USERNAME`` are [Repository secrets](https://github.com/aguilita1/SampleSyncApp/settings/secrets/actions)

### Visio Studio Marketplace & Actions Used
* https://marketplace.visualstudio.com/search?target=AzureDevOps&category=Azure%20Pipelines&sortBy=Installs
* https://github.com/aguilita1/namer_flutter_app

# Continuous Integration / Continuous Deployment (azure-pipeline-streamline-android.yml) Pipeline Live Demo 

### How to run CI/CD pipeline
* Run on ``main`` branch manually for (azure-pipeline-streamline-android.yml)
  * Review published artifacts 
    
