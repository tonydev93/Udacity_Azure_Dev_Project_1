# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
Ease of use: App Service is a fully managed service, which means that Microsoft takes care of all the underlying infrastructure, such as provisioning and managing virtual machines, patching, and security. This can save you a lot of time and effort, especially if you are not familiar with managing virtual machines.
Scalability: App Service is highly scalable, so you can easily increase or decrease the number of resources allocated to your app as needed. This is important for small web apps that may experience sudden spikes in traffic.
Cost-effectiveness: App Service is a pay-as-you-go service, so you only pay for the resources that you use. This can be a more cost-effective option than virtual machines, especially if your app is not used very often.
Features: App Service comes with a number of features that are not available with virtual machines, such as built-in continuous integration and continuous delivery (CI/CD), support for multiple programming languages (here is python)

For reasons above, I chose App service instead of the VM.
### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 