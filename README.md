# W5 Build Demos  
## Description:  
This repository contains sample projects and associated GitHub Actions workflows for several sample projects covering Java and C# .Net.

## Practical Tasks:  
1. Clone the repository to your local PC.
2. Using the command line build explore the built in tasks that the dotnet build and the Gradle wrapper build tools provide for the C# .net and Java project respectively.
3. Generate test reports and documentation for each project. You may have to add doc comments and some additional tests. Experiment by also adding some failing tests.
4. Add separate GitHub action workflows for the .net and java projects. The workflows should in the first instance should build and test the respective projects. 
5. Enhance the workflow files by:
    - Separate the build and test jobs.
    - Use artifact storage to share build artifacts between jobs.
    - Exploring the use of caching of dependencies and other build artifacts to speed up workflow execution. Refer to GitHub Actions and build tool documentation for further guidance. 
    - Generate and publish test reports.
    - Add status badges for each workflow

## Additional links 
[Gradle getting started](https://docs.gradle.org/current/userguide/getting_started_eng.html)  
[dotnet build CLI](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet)  
[Building and testing Java with Gradle](https://docs.github.com/en/actions/tutorials/build-and-test-code/java-with-gradle)  
[Building and testing .NET](https://docs.github.com/en/actions/tutorials/build-and-test-code/net)  
[Dependency caching reference](https://docs.github.com/en/actions/reference/workflows-and-actions/dependency-caching)  
[A Better Way to Use Gradle With Github Actions](https://blog.gradle.org/gh-actions)  
[Gradle Cache Action](https://github.com/marketplace/actions/gradle-cache)  
[Adding a workflow status badge](https://docs.github.com/en/actions/how-tos/monitor-workflows/add-a-status-badge)  
[Configuring a publishing source for your GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)  
[A composite Action for packaging and uploading artifact that can be deployed to GtiHub pages](https://github.com/actions/upload-pages-artifact)  
