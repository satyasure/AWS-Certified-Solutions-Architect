# AWS-Certified-Solutions-Architect

AWS Certified Solutions Architect : Associate SAA‐C02 Exam

## The Core AWS Services

## Cloud Computing and Virtualization

* The technology that lies at the core of all cloud operations is virtualization.

* Virtualization lets you divide the hardware resources of a single physical server into smaller units.

* That physical server could therefore host multiple virtual machines (VMs) running their own complete operating systems, each with its own memory, storage, and network access.

### Virtual Machine

> Virtualization's flexibility makes it possible to provision a virtual server in a matter of seconds, run it for exactly the time your project requires, and then shut it down. The resources released will become instantly available to other workloads. 
> The usage density you can achieve lets you squeeze the greatest value from your hardware and makes it easy to generate experimental and sandboxed environments.

![Virtualization](./VM-Cloud.png)

### AWS Cloud VM

#### Cloud Computing Architecture

> Major cloud providers like AWS have enormous server farms where hundreds of thousands of servers and disk drives are maintained along with the network cabling necessary to connect them. A well‐built virtualized environment could provide a virtual server using storage, memory, compute cycles, and network bandwidth collected from the most efficient mix of available sources it can find.

> A cloud computing platform offers on‐demand, self‐service access to pooled compute resources where your usage is metered and billed according to the volume you consume. Cloud computing systems allow for precise billing models, sometimes involving fractions of a penny for an hour of consumption

![Virtualization](./AWS-Virtulization.png)

## AWS Platform Architecture

> AWS maintains data centers for its physical servers around the world. Because the centers are so widely distributed, you can reduce your own services' network transfer latency by hosting your workloads geographically close to your users. 
> It can also help you manage compliance with regulations requiring you to keep data within a particular legal jurisdiction.
> Data centers exist within AWS regions, of which there are currently 21—not including private U.S. government AWS GovCloud regions—although this number is constantly growing. 
> It's important to always be conscious of the region you have selected when you launch new AWS resources; pricing and service availability can vary from one to the next
