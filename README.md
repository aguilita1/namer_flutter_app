# namer_flutter_app

A reference implementation to demonstrate how to use Azure Piplines with a simple Flutter application that targets iOS and Andriod.

### ⚠️WARNING: Currently broken still working through use-case to build and deploy to Google App Store and Apple App Store.

## Demonstrates Various Continuous Integration Stages
* Download Secure File [``DownloadSecureFile@1``](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/download-secure-file-v1?view=azure-pipelines)
* Copy File [``CopyFiles@2``](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/copy-files-v2?view=azure-pipelines&tabs=yaml)
* Command Line [``CmdLine@2``](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/cmd-line-v2?view=azure-pipelines)
* Bash [``Bash@3``](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/bash-v3?view=azure-pipelines)
* Flutter Install [``FlutterInstall@0``](https://marketplace.visualstudio.com/items?itemName=Hey24sheep.flutter)
* Flutter Command [``FlutterCommand@0``](https://marketplace.visualstudio.com/items?itemName=Hey24sheep.flutter)
* Flutter Analyze Task [``FlutterAnalyzeTask@0``](https://marketplace.visualstudio.com/items?itemName=Hey24sheep.flutter)
* Flutter Build [``FlutterBuild@0``](https://marketplace.visualstudio.com/items?itemName=Hey24sheep.flutter)
* Android Signing [``AndroidSigning@3``](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/android-signing-v3?view=azure-pipelines)
* Archive Files [``ArchiveFiles@2``](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/archive-files-v2?view=azure-pipelines)
* Publish Pipeline Artifact [``PublishPipelineArtifact@1``](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/publish-pipeline-artifact-v1?view=azure-pipelines)
* Download Pipeline Artifact [``DownloadPipelineArtifact@2``](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/download-pipeline-artifact-v2?view=azure-pipelines)
* Google Play Release [``GooglePlayRelease@4``](https://marketplace.visualstudio.com/items?itemName=ms-vsclient.google-play)
* Generate Release Notes [``XplatGenerateReleaseNotes@4``](https://marketplace.visualstudio.com/items?itemName=richardfennellBM.BM-VSTS-XplatGenerateReleaseNotes)
* Install Apple Certificate [``InstallAppleCertificate@2``](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/install-apple-certificate-v2?view=azure-pipelines)
* Install Apple Provisioning Profile [``InstallAppleProvisioningProfile@1``](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/install-apple-provisioning-profile-v1?view=azure-pipelines)
* Xcode [``Xcode@5``](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/xcode-v5?view=azure-pipelines)
* Apple App Store Release [``AppStoreRelease@1``](https://marketplace.visualstudio.com/items?itemName=ms-vsclient.app-store)


## This project leverages the Flutter Codelab app

If you need to learn more about Flutter here are a few resources to get you started:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
