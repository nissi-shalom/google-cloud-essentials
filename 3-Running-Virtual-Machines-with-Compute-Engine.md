# Running Virtual Machines with Compute Engine

Often people get introduced to Compute engine through App engine. Compute engine is undeniably more flexible (Mostly considered as backend)

#### Compute engine Fundamentals.
1. IssS
   * Infrastructure as a Service.
   * Full access to configuring
1. Scalabe high performance virtual machines (VMs)
1. Comes in numerous configurations, completly customisable.
1. Run public disk images or private images.
   * Public: Preconfigured and offered by google.
   * Private: Accessible only you.
1. Various storage options. Everything from standard persistant disks located remotely to local solid state drives.
1. VMs are configured so that you can optionally work with docker containers. This increases protability for the project.
1. Virtual Private Network (VPC) support. Allows both general and internal access.
1. Default and custom firewalls.
1. Complete routing capabilites as well.

* **Virtual machines are the true heart of the compute engines**
* Google Cloud allows you to create two different types of instance groups. Managed and Unmanaged.

#### Unmanaged instance group
* Unmanged instance groups are the collections of different configurations. Typically these are used if you are applying load-balancing to your preexisting configurations.
* With unmanaged groups you don't get auto scalling. You can't update the support on a rolling basis.

#### Managed instance groups
* Instances are identical. you can manage them as a single unit. Any change you need to make on one you have to do it to all of them.
* They automatically scale, load balancing is built-in.
* If there are health issue in one of issues, like, if gets destroyed or something - the other instances will automatically recreates it.
* These instances can be zonal or Regional.