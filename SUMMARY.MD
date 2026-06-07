# Azure Lab Summary

# Region Chosen

My resources were deployed in the East US region.

# Why East US?

- It is one of Azure’s major regions with broad service availability.
- It provides low latency and reliable performance for general workloads.
- It was the region selected during the creation of my Resource Group.

# Resource Deployed

Inside my Resource Group GodwinRG, I deployed several resources.  
For the purpose of this summary, I am focusing on the Virtual Machine (DDOSVM).

# Resource Details

- Resource Group: GodwinRG
- Region: East US
- Resource Type: Virtual Machine
- Associated Resources:
  - Public IP
  - Network Interface
  - Network Security Group
  - OS Disk
  - SSH Keys

# Shared Responsibility Model (Applied to the Virtual Machine)

Azure uses a Shared Responsibility Model, meaning Microsoft and the customer each handle different parts of security and management.

# What Microsoft is responsible for:

- Physical datacenter security
- Power, cooling, and hardware maintenance
- The underlying virtualization layer
- The Azure networking fabric
- Ensuring the Azure platform is available and patched

# What "I" (the customer) am responsible for:

- Securing the operating system inside the VM (patching, updates)
- Managing user accounts, SSH keys, and access policies
- Configuring Network Security Groups (NSGs) and firewall rules
- Protecting the data stored on the VM
- Monitoring logs, alerts, and cost usage
- Ensuring applications running inside the VM are secure

# Summary

Microsoft secures the cloud infrastructure.  
I secure everything inside the VM and how it is accessed.

# Conclusion

The East US region was chosen for availability and performance.  
The Shared Responsibility Model ensures that while Azure provides a secure and reliable platform, I am responsible for securing and managing the resources I deploy within it.
