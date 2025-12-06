<p align="center" >
  Azure Fundametals

</p>

<p align="center">
  <img 
    src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSX1z5XvAwS8G_ojSep2CpJdkYJ7MhpUvJ_8g&s" 
    width="400" 
    style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.25);" 
  />
</p>

* **Cloud Computing**
Cloud computing is the delivery of computing services over the internet, such as servers, storage, databases, software, and networking.

* **High availability**
High availability means that a system stays working and online all the time, even if something goes wrong.

* **Scalability**
Scalability means the ability of a system to grow and handle increased demand without losing performance.

* **Elasticity**
  Elasticity is the ability of a system to automatically add or remove resources based on current demand.
* **Agility**
  Agility is the ability to move quickly and adapt easily to changes or new requirements.
* **Fault tolerance**
  Fault tolerance is the ability of a system to continue working correctly even when one or more parts fail.
* **Disaster recovery**
  Disaster recovery is the process and plan used to restore systems and data after a major failure or disaster, so the business can continue operating.

# Basic concepts

* **VNet (Virtual Network)**

A VNet is a private, isolated network inside the cloud.
It works like your own network in Azure where you place resources (VMs, databases, apps) and control how they communicate.

* **Subnet**

A Subnet is a smaller section inside a VNet.
You use subnets to organize and separate resources — for example, one subnet for public-facing services and another for internal services.

* **Route Table**

A Route Table contains rules that decide how network traffic should move inside the VNet.
It tells Azure where to send packets — for example, to the internet, a firewall, or another subnet.

* **Internet**

The Internet is the global network that connects devices and services worldwide.
From a cloud perspective, “internet” usually means public access from outside Azure into your service or from your service out to the world.

* **Network Security Group (NSG)**

An NSG is a firewall at the network level.
It controls which traffic is allowed or denied to subnets or network interfaces based on rules (port, protocol, source, destination).


* **Private DNS Zone**
  
In Azure is a private, internal DNS service that lets resources inside your VNet resolve names without going through the public internet.

* **DNS (Domain Name System)**

Is essentially the internet’s directory service. Its purpose is to translate human-friendly names into machine-friendly IP addresses.
