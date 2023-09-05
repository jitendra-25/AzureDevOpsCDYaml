# Azure DevOps CD Yaml
Repository for CD yaml pipeline used in Azure DevOps for dotnet core app deployment on IIS.

1. CoreWebApp02_BuildPipeline.yml - It is the build pipeline used to compile and publish the artifacts which are later deployed on IIS.
2. CoreWebApp02_Deployment.yml - This is the CD yml pipeline. You can use this yml file to deploy dotnet core application on IIS on a server. It also has tasks to stop/start and recycle IIS AppPool.
