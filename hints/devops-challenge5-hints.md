# Shift-left with SonarCloud
## Hints
- Create a free [SonarCloud] account [here](https://sonarcloud.io)
- Add build taks to your pipeline for this. Search for SonarCloud
- Once you have the SonarCloud application, new tasks will  be available to add
- The prepare task should be added at the start of the pipeline and this is where the keys are stored for accessing the SonarCloud service
- You may get a failure because the Sample Application Project does not have a unique GUID present.  GUIDs can be generated [here](https://www.guidgenerator.com/online-guid-generator.aspx>)
- You only need to add a GUID to the main application project to get analysis to run.
- On the build summary page click the link to the SonarCloud detailed report and explore that.

Detailed instructions for this challenge are available [here](https://github.com/nikkh/maug3010/wiki/Extend-your-build-pipeline-with-Sonarcloud)

[back](../azure-devops-projects-mini-hack.md)
