# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

**Azure APP Service**- Is a Platform as a Service(PaaS), which has a high availability, auto-scaling, continuous deployment, and cost contorls such as three different tiers of hardware to host applications such as: 

* Dev/Test
* Production
* Isolated 

**Azure Virtual Machines(VMs)**- are infrastructure as a Service(Iaas), which allows you to create and use virtual machines. VMs allow full control of the VMs, lower up-front cost compared to purchasing hardware, various configuration options, the ability to install custom images, and the option to use load balancers or virtual machine scale sets. Overall, VMs are ideal for full control of the application and Testing/Development. 

**My selection**- After analzying Azure VMs and Azure App Service I believe that for this project Azure App Service is the best option. App Service allows me to focus on building out the application and it handles the infrastructure. Since this project application is lightweight and doesnt need high performance compute services. 


### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.*

**Azure APP Service**- If this application would need features that Azure does not provide then I would have to change my decision to VMs. In addition if this application required more control of the hardware/infrastructure then I would also have to switch to VMs. 

**Azure Virtual Machines(VMs)**- If this application had a decline of traffic then its best to switch to App Service for more cost savings since high performance compute would not be needed. Overall if there were budgeting contraints then moving the application to App Service would create cost savings. Lastly, if there are tight deadlines then moving to a App Service will reduce the time it takes to deploy an applicaion. 