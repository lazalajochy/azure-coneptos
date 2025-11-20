# azure-coneptos

<p align="center">
  <img 
    src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSX1z5XvAwS8G_ojSep2CpJdkYJ7MhpUvJ_8g&s" 
    width="400" 
    style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.25);" 
  />
</p>



[link](https://chatgpt.com/share/69165efd-7838-8005-b185-31b7124d7c42)


# Cloud Models: IaaS, PaaS, SaaS

| Model                                  | Definition                                                                                                                                                | Example                              |
| -------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------ |
| **IaaS (Infrastructure as a Service)** | Provides virtualized computing resources over the internet, such as virtual machines, networks, storage, and servers. You manage the OS and applications. | Azure Virtual Machines, AWS EC2      |
| **PaaS (Platform as a Service)**       | Provides a platform with tools and environment to build, run, and manage applications without managing servers or infrastructure.                         | Azure App Service, Google App Engine |
| **SaaS (Software as a Service)**       | Fully managed software delivered over the internet. Users just access and use the application.                                                            | Gmail, Office 365, Salesforce        |

---
# High Availability, Scalability, Fault Tolerance, Disaster Recovery

| Concept                    | Definition                                                                      |
| -------------------------- | ------------------------------------------------------------------------------- |
| **High Availability (HA)** | Ensures that a system is always operational with minimal downtime.              |
| **Scalability**            | Ability to increase or decrease resources depending on the demand.              |
| **Fault Tolerance**        | Ability of a system to continue operating even if some components fail.         |
| **Disaster Recovery (DR)** | A plan and tools to restore systems and data after a major failure or disaster. |


---

# Azure Resource Manager (ARM) and ARM Templates

| Concept                          | Definition                                                                                                  |
| -------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| **Azure Resource Manager (ARM)** | The management layer in Azure that allows deploying, managing, and organizing resources.                    |
| **ARM Templates**                | JSON files that define infrastructure as code (IaC) to deploy Azure resources automatically and repeatedly. |


# Virtual Networks (VNet) and Subnets

| Concept                    | Definition                                                                                                                                                         |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Virtual Network (VNet)** | A private network in Azure that allows resources like VMs, databases, and services to securely communicate with each other, the internet, or on-premises networks. |
| **Subnets**                | Logical segments inside a VNet that divide the network into smaller parts to organize resources and improve security.                                              |


# VPN Gateway and ExpressRoute (Hybrid Connections)

| Concept          | Definition                                                                                                                                  |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| **VPN Gateway**  | A service that creates an encrypted connection between an on-premises network and an Azure VNet over the public internet.                   |
| **ExpressRoute** | A private, dedicated connection from on-premises infrastructure to Azure, offering higher speed, lower latency, and more security than VPN. |


# NSG, Firewalls, Azure Front Door, and Application Gateway
| Component                        | Definition                                                                                                                     |
| -------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| **NSG (Network Security Group)** | Rules that allow or block network traffic to Azure resources based on IP, port, and protocol. Works at subnet or NIC level.    |
| **Firewall (Azure Firewall)**    | A managed network security service that protects Azure networks from threats with advanced filtering and monitoring.           |
| **Azure Front Door**             | A global entry point that provides faster delivery using CDN, web application firewall (WAF), and load balancing for web apps. |
| **Application Gateway**          | A layer-7 load balancer that distributes traffic based on HTTP/HTTPS rules and includes WAF for security.                      |


# Load Balancers: Azure Load Balancer and Traffic Manager

| Service                 | Definition                                                                                                                    |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| **Azure Load Balancer** | A layer-4 (TCP/UDP) load balancer that distributes traffic across virtual machines or services within a region.               |
| **Traffic Manager**     | A DNS-based load balancer that distributes traffic across regions for global applications. Used for geo-routing and failover. |
