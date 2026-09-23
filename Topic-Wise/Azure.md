# Azure — DevOps Interview Questions & Answers

> **Source:** `Interview Questions-3.xlsx` → `Azure` worksheet.
>
> **Important:** The workbook is the source of truth for the questions and supplied answers. Where the workbook does not provide an answer, this document explicitly says so. No missing answer has been presented as if it came from the workbook.

## Revision Format

For each question:

**Question → Simple Explanation → Interview-Ready Answer → Source Answer → Real-World Example → Follow-up Questions**

The **Simple Explanation** and **Interview-Ready Answer** are reorganized/rewritten from the workbook content where an answer exists. Real-world examples and follow-up questions are not present in the workbook and are therefore not invented here.

## Q1. Types of instances offerd by azure

### Simple Explanation
Azure provides various types of instances, including Virtual Machines (VMs), Virtual Machine Scale Sets, Azure Kubernetes Service (AKS), Azure Functions, and more

### Interview-Ready Answer
Azure provides various types of instances, including Virtual Machines (VMs), Virtual Machine Scale Sets, Azure Kubernetes Service (AKS), Azure Functions, and more. Each serves different use cases and workloads.

### Source Answer from Workbook
> Azure provides various types of instances, including Virtual Machines (VMs), Virtual Machine Scale Sets, Azure Kubernetes Service (AKS), Azure Functions, and more. Each serves different use cases and workloads.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q2. How do you setup azure VM?

### Simple Explanation
The setup process for an Azure VM involves creating a Virtual Machine in the Azure Portal

### Interview-Ready Answer
The setup process for an Azure VM involves creating a Virtual Machine in the Azure Portal. Specify details such as VM size, operating system, storage, network configuration, and optional features. After creation, you can connect to the VM for configuration and management.

### Source Answer from Workbook
> The setup process for an Azure VM involves creating a Virtual Machine in the Azure Portal. Specify details such as VM size, operating system, storage, network configuration, and optional features. After creation, you can connect to the VM for configuration and management.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q3. Diffrence between scaleset and availability set?

### Simple Explanation
Azure Availability Sets are used for ensuring high availability within a datacenter by distributing VMs across fault domains and update domains

### Interview-Ready Answer
Azure Availability Sets are used for ensuring high availability within a datacenter by distributing VMs across fault domains and update domains. Azure Virtual Machine Scale Sets are designed for high-scale applications, automatically scaling VM instances based on demand.

### Source Answer from Workbook
> Azure Availability Sets are used for ensuring high availability within a datacenter by distributing VMs across fault domains and update domains. Azure Virtual Machine Scale Sets are designed for high-scale applications, automatically scaling VM instances based on demand.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q4. What are iaas, paas, saas?

### Simple Explanation
- IaaS (Infrastructure as a Service): Provides virtualized computing resources over the internet

### Interview-Ready Answer
- IaaS (Infrastructure as a Service): Provides virtualized computing resources over the internet. - PaaS (Platform as a Service): Offers a platform allowing customers to develop, run, and manage applications without dealing with the underlying infrastructure. - SaaS (Software as a Service): Delivers software applications over the internet, eliminating the need for users to install, maintain, and run the software locally.

### Source Answer from Workbook
> - IaaS (Infrastructure as a Service): Provides virtualized computing resources over the internet. - PaaS (Platform as a Service): Offers a platform allowing customers to develop, run, and manage applications without dealing with the underlying infrastructure. - SaaS (Software as a Service): Delivers software applications over the internet, eliminating the need for users to install, maintain, and run the software locally.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q5. What is Public private and hybrid cloud?

### Simple Explanation
- Public Cloud: Resources are owned and operated by a third-party provider and made available to the general public

### Interview-Ready Answer
- Public Cloud: Resources are owned and operated by a third-party provider and made available to the general public. - Private Cloud: Resources are used exclusively by one organization, providing more control and customization. - Hybrid Cloud: Combines public and private cloud environments, allowing data and applications to be shared between them.

### Source Answer from Workbook
> - Public Cloud: Resources are owned and operated by a third-party provider and made available to the general public. - Private Cloud: Resources are used exclusively by one organization, providing more control and customization. - Hybrid Cloud: Combines public and private cloud environments, allowing data and applications to be shared between them.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q6. How to do we perform connectivity in between Vm if they are in different subscription.

### Simple Explanation
To connect Azure VMs in different subscriptions, you can use Virtual Network Peering

### Interview-Ready Answer
To connect Azure VMs in different subscriptions, you can use Virtual Network Peering. Establish peering relationships between the virtual networks in each subscription, allowing seamless communication between VMs.

### Source Answer from Workbook
> To connect Azure VMs in different subscriptions, you can use Virtual Network Peering. Establish peering relationships between the virtual networks in each subscription, allowing seamless communication between VMs.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q7. why you are using application gateway as entrypoint?

### Simple Explanation
Azure Application Gateway serves as an entry point for web traffic

### Interview-Ready Answer
Azure Application Gateway serves as an entry point for web traffic. It provides features like SSL termination, URL-based routing, and web application firewall, enhancing the security, scalability, and performance of web applications.

### Source Answer from Workbook
> Azure Application Gateway serves as an entry point for web traffic. It provides features like SSL termination, URL-based routing, and web application firewall, enhancing the security, scalability, and performance of web applications.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q8. what is loadbalancers and its lb rule.

### Simple Explanation
Azure Load Balancers distribute incoming network traffic across multiple servers to ensure high availability and reliability

### Interview-Ready Answer
Azure Load Balancers distribute incoming network traffic across multiple servers to ensure high availability and reliability. Load Balancer rules define how the traffic is distributed, specifying criteria such as port numbers and protocols.

### Source Answer from Workbook
> Azure Load Balancers distribute incoming network traffic across multiple servers to ensure high availability and reliability. Load Balancer rules define how the traffic is distributed, specifying criteria such as port numbers and protocols.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q9. /16 and /28 which will have more usable ip

### Simple Explanation
- /16: Represents a subnet with 65,536 IP addresses

### Interview-Ready Answer
The workbook answer compares `/16` with `/24`, not the `/28` asked in the question. The source answer states that `/16` represents 65,536 IP addresses and `/24` represents 256, so `/16` provides the larger address space. Verify the intended comparison before using this answer in an interview.

### Source Answer from Workbook
> - /16: Represents a subnet with 65,536 IP addresses. - /24: Represents a subnet with 256 IP addresses. /16 provides a larger address space and more usable IP addresses compared to /24.

> **Source mismatch to note:** The interview question says `/16 vs /28`, while the workbook's answer says `/16 vs /24`. The original question is preserved above.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q10. What is address prifixes.

### Simple Explanation
Address prefixes in Azure Virtual Network define IP address ranges for subnets within the VNet

### Interview-Ready Answer
Address prefixes in Azure Virtual Network define IP address ranges for subnets within the VNet. They help in segmenting and organizing the IP address space to accommodate different components of the network.

### Source Answer from Workbook
> Address prefixes in Azure Virtual Network define IP address ranges for subnets within the VNet. They help in segmenting and organizing the IP address space to accommodate different components of the network.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q11. what is access control (IAM) in azure.

### Simple Explanation
Identity and Access Management (IAM) in Azure allows you to control access to resources

### Interview-Ready Answer
Identity and Access Management (IAM) in Azure allows you to control access to resources. It includes roles like Owner, Contributor, and Reader, which grant different levels of permissions to users, groups, or applications.

### Source Answer from Workbook
> Identity and Access Management (IAM) in Azure allows you to control access to resources. It includes roles like Owner, Contributor, and Reader, which grant different levels of permissions to users, groups, or applications.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q12. What are the different types of Storage in Azure.

### Simple Explanation
Azure offers various types of storage, including Blob Storage (for unstructured data), Table Storage (NoSQL key-value store), Queue Storage (for reliable messaging between components), File Storage (file shares accessible via SMB), and Disk Storage (for VM disks).

### Interview-Ready Answer
Azure offers various types of storage, including Blob Storage (for unstructured data), Table Storage (NoSQL key-value store), Queue Storage (for reliable messaging between components), File Storage (file shares accessible via SMB), and Disk Storage (for VM disks).

### Source Answer from Workbook
> Azure offers various types of storage, including Blob Storage (for unstructured data), Table Storage (NoSQL key-value store), Queue Storage (for reliable messaging between components), File Storage (file shares accessible via SMB), and Disk Storage (for VM disks).

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q13. Explain Managed identity and service connection and principal

### Simple Explanation
- Managed Identity: An Azure service principal managed by Azure, simplifying authentication to Azure services

### Interview-Ready Answer
- Managed Identity: An Azure service principal managed by Azure, simplifying authentication to Azure services. - Service Connection: In Azure DevOps, a service connection is used to connect to Azure services securely. - Principal: In Azure Active Directory, a security principal represents a user, group, or application that is granted access to resources.

### Source Answer from Workbook
> - Managed Identity: An Azure service principal managed by Azure, simplifying authentication to Azure services. - Service Connection: In Azure DevOps, a service connection is used to connect to Azure services securely. - Principal: In Azure Active Directory, a security principal represents a user, group, or application that is granted access to resources.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q14. what are the methods to create VM ?

### Simple Explanation
Azure VMs can be created using the Azure Portal, Azure PowerShell, Azure CLI, Azure Resource Manager (ARM) templates, or through Azure Virtual Machine Scale Sets for auto-scaling.

### Interview-Ready Answer
Azure VMs can be created using the Azure Portal, Azure PowerShell, Azure CLI, Azure Resource Manager (ARM) templates, or through Azure Virtual Machine Scale Sets for auto-scaling.

### Source Answer from Workbook
> Azure VMs can be created using the Azure Portal, Azure PowerShell, Azure CLI, Azure Resource Manager (ARM) templates, or through Azure Virtual Machine Scale Sets for auto-scaling.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q15. How can you control traffic on VM ?

### Simple Explanation
Traffic on VMs can be controlled using Network Security Groups (NSGs) to define inbound and outbound rules

### Interview-Ready Answer
Traffic on VMs can be controlled using Network Security Groups (NSGs) to define inbound and outbound rules. NSGs filter traffic based on IP addresses, ports, and protocols, providing security at the network layer.

### Source Answer from Workbook
> Traffic on VMs can be controlled using Network Security Groups (NSGs) to define inbound and outbound rules. NSGs filter traffic based on IP addresses, ports, and protocols, providing security at the network layer.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q16. How many type of different storages are there in azure ?

### Simple Explanation
Azure offers various types of storage, including Blob Storage (for unstructured data), Table Storage (NoSQL key-value store), Queue Storage (for reliable messaging between components), File Storage (file shares accessible via SMB), and Disk Storage (for VM disks).

### Interview-Ready Answer
Azure offers various types of storage, including Blob Storage (for unstructured data), Table Storage (NoSQL key-value store), Queue Storage (for reliable messaging between components), File Storage (file shares accessible via SMB), and Disk Storage (for VM disks).

### Source Answer from Workbook
> Azure offers various types of storage, including Blob Storage (for unstructured data), Table Storage (NoSQL key-value store), Queue Storage (for reliable messaging between components), File Storage (file shares accessible via SMB), and Disk Storage (for VM disks).

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q17. Is it possible to increase the disk size after deploying VM if yes how can you do it without effecting its running .

### Simple Explanation
In Azure, you can increase the disk size of a VM without affecting its running state

### Interview-Ready Answer
In Azure, you can increase the disk size of a VM without affecting its running state. Stop the VM, resize the data disk in the Azure Portal, and restart the VM. Ensure that the operating system disk allows resizing, or use managed disks for more flexibility. The workbook itself contains a stop/restart instruction, so this answer should be verified for the exact disk type and operating system before using it as a production procedure.

### Source Answer from Workbook
> In Azure, you can increase the disk size of a VM without affecting its running state. Stop the VM, resize the data disk in the Azure Portal, and restart the VM. Ensure that the operating system disk allows resizing, or use managed disks for more flexibility.

> **Source wording note:** The workbook says the VM can be resized without affecting its running state, but then instructs stopping the VM. Treat the supplied answer as source material and verify the exact Azure disk/OS procedure for the specific scenario.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q18. If you want to login VM without sharing username and password , how you will do that ?

### Simple Explanation
Use Azure Virtual Machine Extensions or Azure Key Vault to enable Azure AD-based login without sharing usernames and passwords

### Interview-Ready Answer
Use Azure Virtual Machine Extensions or Azure Key Vault to enable Azure AD-based login without sharing usernames and passwords. Managed identities and Azure AD authentication methods enhance security and ease of access.

### Source Answer from Workbook
> Use Azure Virtual Machine Extensions or Azure Key Vault to enable Azure AD-based login without sharing usernames and passwords. Managed identities and Azure AD authentication methods enhance security and ease of access.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q19. How can we connect On Prim VM and Virtual VM

### Simple Explanation
Use Azure Virtual Network Gateway, Site-to-Site VPN, or Azure ExpressRoute to establish a secure connection between on-premises networks and Azure VNets

### Interview-Ready Answer
Use Azure Virtual Network Gateway, Site-to-Site VPN, or Azure ExpressRoute to establish a secure connection between on-premises networks and Azure VNets. Ensure proper network configurations, address spaces, and security settings.

### Source Answer from Workbook
> Use Azure Virtual Network Gateway, Site-to-Site VPN, or Azure ExpressRoute to establish a secure connection between on-premises networks and Azure VNets. Ensure proper network configurations, address spaces, and security settings.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q20. Suppose we have created a VM , and i want to send some script files in those VM , how can i do this ?

### Simple Explanation
This question checks your understanding of the Azure concept mentioned in the question.

### Interview-Ready Answer
The workbook provides no answer for this question.

### Source Answer from Workbook
**No answer provided in the workbook.**

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q21. Define Fault domain and Update domain.

### Simple Explanation
This question checks your understanding of the Azure concept mentioned in the question.

### Interview-Ready Answer
The workbook provides no answer for this question.

### Source Answer from Workbook
**No answer provided in the workbook.**

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q22. What is bastion ?

### Simple Explanation
Bastion refers to a secure and controlled entry point into a network

### Interview-Ready Answer
Bastion refers to a secure and controlled entry point into a network. In Azure, Azure Bastion is a managed service that provides secure and seamless RDP and SSH access to Azure VMs directly through the Azure Portal. It eliminates the need to expose VMs to the public internet.

### Source Answer from Workbook
> Bastion refers to a secure and controlled entry point into a network. In Azure, Azure Bastion is a managed service that provides secure and seamless RDP and SSH access to Azure VMs directly through the Azure Portal. It eliminates the need to expose VMs to the public internet.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q23. Can we replace bastion with firwall ?

### Simple Explanation
Bastion and firewalls serve different purposes

### Interview-Ready Answer
Bastion and firewalls serve different purposes. While a bastion provides secure remote access to VMs, a firewall controls and filters network traffic. They are complementary, and using both enhances security. Bastion focuses on access, while a firewall focuses on traffic filtering.

### Source Answer from Workbook
> Bastion and firewalls serve different purposes. While a bastion provides secure remote access to VMs, a firewall controls and filters network traffic. They are complementary, and using both enhances security. Bastion focuses on access, while a firewall focuses on traffic filtering.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q24. What is NGS and ASG ?

### Simple Explanation
- NSGs: Azure NSGs are stateful Layer 4 firewalls that control inbound and outbound traffic to Azure resources based on rules

### Interview-Ready Answer
- NSGs: Azure NSGs are stateful Layer 4 firewalls that control inbound and outbound traffic to Azure resources based on rules. - ASGs: Azure ASGs allow logical grouping of VMs based on application-centric logic. They simplify security rule management by enabling rule configuration based on application memberships.

### Source Answer from Workbook
> - NSGs: Azure NSGs are stateful Layer 4 firewalls that control inbound and outbound traffic to Azure resources based on rules. - ASGs: Azure ASGs allow logical grouping of VMs based on application-centric logic. They simplify security rule management by enabling rule configuration based on application memberships.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q25. What is the use of virtual network in azure ?

### Simple Explanation
Azure Virtual Network (VNet) is a fundamental building block that provides a logically isolated network within Azure

### Interview-Ready Answer
Azure Virtual Network (VNet) is a fundamental building block that provides a logically isolated network within Azure. It enables secure connectivity, segmentation of resources, integration with on-premises networks, and serves as the foundation for deploying various Azure services.

### Source Answer from Workbook
> Azure Virtual Network (VNet) is a fundamental building block that provides a logically isolated network within Azure. It enables secure connectivity, segmentation of resources, integration with on-premises networks, and serves as the foundation for deploying various Azure services.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q26. What are the resources you have worked on azure ?

### Simple Explanation
While I don't have personal experiences, I can provide information on various Azure resources, including VMs, VNets, Azure Resource Manager, Azure Storage, Azure Active Directory, Azure App Service, Azure SQL Database, Azure DevOps, and more.

### Interview-Ready Answer
The workbook lists VMs, VNets, Azure Resource Manager, Azure Storage, Azure Active Directory, Azure App Service, Azure SQL Database, and Azure DevOps as Azure resources to discuss. In an interview, answer only with services you have actually worked with.

### Source Answer from Workbook
> While I don't have personal experiences, I can provide information on various Azure resources, including VMs, VNets, Azure Resource Manager, Azure Storage, Azure Active Directory, Azure App Service, Azure SQL Database, Azure DevOps, and more.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q27. If there is one Frontend application ( Web Application ) hosted on app service and there is backend server and my web app is connected to that web server, and i need to ensure my web application is higly avaiable and my data base also higly available.

### Simple Explanation
- Azure Update Management - Azure Security Center - Azure Automation - Azure Traffic Manager - Azure Load Balancer - Azure Application Gateway - Azure Database Services - Azure Virtual Machine Scale Sets

### Interview-Ready Answer
- Azure Update Management - Azure Security Center - Azure Automation - Azure Traffic Manager - Azure Load Balancer - Azure Application Gateway - Azure Database Services - Azure Virtual Machine Scale Sets

### Source Answer from Workbook
> - Azure Update Management - Azure Security Center - Azure Automation - Azure Traffic Manager - Azure Load Balancer - Azure Application Gateway - Azure Database Services - Azure Virtual Machine Scale Sets

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q28. I have a virtual machine and i use to apply some security patches in that VM , how are you going to do that

### Simple Explanation
- Use Azure Update Management for automated patching

### Interview-Ready Answer
- Use Azure Update Management for automated patching. - Leverage Azure Security Center for security recommendations. - Implement Azure Automation for patch deployment. - Manually patch by connecting to VM and applying updates. - Follow general best practices for monitoring and testing.

### Source Answer from Workbook
> - Use Azure Update Management for automated patching. - Leverage Azure Security Center for security recommendations. - Implement Azure Automation for patch deployment. - Manually patch by connecting to VM and applying updates. - Follow general best practices for monitoring and testing.

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q29. What is LRS, GRS and RAGRS?

### Simple Explanation
This question checks your understanding of the Azure concept mentioned in the question.

### Interview-Ready Answer
The workbook provides no answer for this question.

### Source Answer from Workbook
**No answer provided in the workbook.**

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.

## Q30. What is session affinity?

### Simple Explanation
This question checks your understanding of the Azure concept mentioned in the question.

### Interview-Ready Answer
The workbook provides no answer for this question.

### Source Answer from Workbook
**No answer provided in the workbook.**

### Real-World Example
Not provided in the workbook.

### Follow-up Questions
Not provided in the workbook.
