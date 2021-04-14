# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
__*Analyze costs, scalability, availability, and workflow*__
__Costs:__
- Costs difference from case to case in general. It dependes on the other factors and the real needs. For CMS Test it is enough to have a Free Ap Service. Later On, on production it depends on real needs usage, needed performance, etc. 
- Test Would be free for App Service and would cost around 4 euros for the VM. In Prod the price would be at the lowest 69 Euro for the App Serivce and you get it for the same money a VM but it depends extremly on your needs!

__scalability and availability:__
- Auto Scaling and high-availabilty for the App Service till a certain point like RAM max of 32GB. With VMs you have full flexible options. You can setup multiple mashines, group them, have a load balancer, redundancy etc. That will increase the costs heavily but makes sense in some production cases to build complex, High-AV and multi scalable infrastrutkure.

__workflow:__
workflow is similiar in both cases. App Services can be easy deployed by external repos like github without any huge knowledge of installation/running and OS insights.

__*Choose the appropriate solution (VM or App Service) for deploying the app*__
- App Service
  
__*Justify your choice*__
- For this project I would choose App Service instead of an VM due to costs, workflow and scalabilty. It is easy to add the code from an external repo, scale easyl without having to much understanding of the OS (and we do not have to take care of). But most important, its an easy App without any specialties and we should focus on cost efficiency. All waht we need esp. for test is given in App service.

### Assess app changes that would change your decision.

__*Detail how the app and any other needs would have to change for you to change your decision in the last section.*__
- I would switch to a VM if I want to scale up (higher than popssible for an app service) or if I want to have the control of the OS for other tasts, update status etc. Also intersting, If i want to have high-AV system with a load-balancer, memory-optimzed (or CPU optimized) flexible maschines. 


