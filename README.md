# DemoAzureDevOpsDeploy
A demo project containing a Winforms app to demonstrate publishing downloadable zip versions from the front page in the ReadMe (or could be a Github pages site).
The title suggests this will only work with Azure DevOps, however, it is also set up with a manually triggered GitHub Actions workflow. 
The goal is to have a pipeline that can be triggered to publish the application, creating a zip file of the bin folder, which is then published in some location.
Ideally, a Github release would probably make the most sense, at least for demo apps, so that is what is created here.

A few goals of the application are
1. Have it not only work with a Github actions workflow but also with Azure DevOps, which is probably more common in professional settings, at least for .NET environments.
2. The goal is to have the below link to a Github Pages page dedicated to downloads, maybe with downloads of specific versions of the application.
3. Eventually make versioning of releases, however they are deployed, update the application information so the version is correct when you right-click the executable. 

Download now [here](https://github.com/zacharywatson1129/DemoAzureDevOpsDeploy/releases/tag/v1.0.1)
