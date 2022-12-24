Q: **Monolith** require to maintain as a whole component, even one small change needs build, deploy, etc the whole applications.  
S: Microservices could resolve this issue.  
Q: Micorservices may depends on differnet versions of various libraries.  
S: **Containerized technologies** could resolve this issue, like Docker  
Q: What is **DevOps**?  
S1: **DevOps** are set of tools and people that facility the software lifecycle goes smoothly.   
S2: This means the developer, QA, and operations teams now need to collaborate throughout the whole process. This practice is called DevOps.  
Q: VMs VS Containers  
S1: VM needs more overhead since it needs its' own system processes, multiple apps running on a VM. Container could run one application in each individual container.  
S2: **Difference** 
* VM - Guest OS, Hypervisor, Host OS
* Container - Host OS  

Container Mechanisms
  * Linux Namespaces
  * Linux Control Group

Container is only able to access limited compute resources!