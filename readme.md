# Study notes for AZ-302

This is in the order studied due to their % worth at the time of sitting the test. I'm not saying this is what's in the exam, this is what I read/re-read in the run up.  I haven't changed this content since the exam was passed (End of April 2019), it's just been tidied a little.  For each section I worked out what I thought was after based on experience, and then researched further.

All coding examples and builds were completed, it turned into a crash course in Visual Studio for someone rarely uses it.  I did this to grasp the concepts as am not a developer, I think it served me well.
Get yourself a free months trial to Pluralsight, I've kept mine on paid, if you're serious about skilling up across the board it's well worth the subscription.

The content for this exam was as below in March 2019.  It was restructured to different headings and percentages in May 2019, however, the content is the same.  There's also alot of crossover here to AZ-300 and AZ-301 too.  There are links in here to opsedx courses which are no longer open for registration.  I used these for hints on what to study when I wasn't sure, which is why they are still listed.

One tip, don't underestimate the lab times, in AZ-1** and AZ-3** it's a huge factor in time management, I ran out of time, but still nailed enough to get over the line with a solid score :) On the labs for any Azure exam, make sure you have a decent monitor size, I lost huge amount of time on one section as I wasn't able to scroll to the right to select some options, the resolution just wasn't up to scratch. That's the main reason I ran out of time.

Last but not least, build everything!


## Develop for the cloud (45-50%)
* [Develop for Long Running Processes](sections/1a.dev-for-cloud_long-running.md)
* [Configure Message Based Integration Architecture](sections/1b.dev-for-cloud_configure-message-based.md)
* [Asynchronous Processing](sections/1c.dev-for-cloud_asynchronous-processing.md)
* [Develop For Autoscaling](sections/1d.dev-for-cloud_develop-for-autoscaling.md)
* [Implement distributed transactions](sections/1e.dev-for-cloud_implement-distributed-transactions.md)
* [Develop advanced cloud workloads](sections/1f.dev-for-cloud_develop-advanced-cloud-workloads.md)
## Design a Business Continuity Strategy (15-20%)
* [Design a Continuity Strategy](sections/2a.design_a_business_continuity_strategy.md)
## Determine Workload Requirements (15-20%)
* [Determine Workload Requirements](sections/3.determine_workload_requirements.md)
    - [Some links taken from Gregor Suttie's Study Notes - awesome content, many thanks!](https://gregorsuttie.com/2019/01/10/az-302-exam-study-notes/)
## Implement Authentication and Secure Data (15-20%)
* [Implement Authentication and Secure Data](sections/4.implement_authentication_and_secure_data.md)
## Design for Security and Identity (5-10%)
* [Design for Security and Identity](sections/6.design_for_identity_and_security.md)
## Implement Workloads and Security (5-10%)
* [Implement Workloads and Security](sections/5.implement_workloads_and_security.md)

## Architecture Documentation
* Made sure was familiar with the following from [Azure reference Architectures](https://docs.microsoft.com/en-gb/azure/architecture/reference-architectures/)
    - VM Workloads, single, n-tier, multi-region n-tier
    - Web Apps, basic, multi-region
    - Hybrid, VPN, ExpressRoute & failover
    - Enterprise Integration
    - Serverless
    - Identity
    
## Hands on items ran through again on run up to exam:
* Function Apps and settings
* Web Apps and Service Plans
* Webjobs
* Eventgrid
* Logic Apps
* Service Bus
* VMs with different availability requirements
* VMs with different disk configs
* VMs with different OS's
* Application gateway setup and settings
* Load balancer setup and settings
* Traffic Manager
* Create Storage accounts with different requirements
* VNets and VNet peering, service endpoints
* NSGs 
* Expressroute/S2x VPN preparation
* RBAC/ create Azure AD Group and assign roles
* Run through the basics of the above with azcli
