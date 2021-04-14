# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- VM is more expensive than a simple App Service. Scalablitly is much higher and the OS can be configured. Interesting esp. for special applications that are not supported by App Serivces.
- App Serivice is muchsimpler to deploy and to maintain. Availability is high and it is easy to scale.
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- For this project I would choose App Service instead of an VM due to costs, workflow and scalabilty. But most important, its an easy App withou any specialties and we should focus on cost efficiency.
- *Justify your choice*
- see above

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
- I would switch to a VM if I want to scale up (higher than popssible for an app service) or if I want to have the control of the OS for other tasts, update status etc or if I need Windows.
- Also intersting, If i want to have high-AV system with a load-balancer.

