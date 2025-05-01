# Secure Azure ☁️ Virtual Machine Deployment (NSG + JIT)

### 📌 Objective
To deploy a secure, cost-effective virtual machine in Azure (using the Free Tier). The VM is protected with a Network Security Group (NSG) and Just-In-Time (JIT) access to minimize security risks while showcasing AZ-900 core concepts.
-------
### 🛠️ Technologies Used
- Azure Portal (Free Tier)
- Azure Virtual Machines (B1s)
- Network Security Groups (NSGs)
- Microsoft Defender for Cloud (JIT Access)
- Azure Resource Groups & Tags
---
### ☑️ What I Did
- Deployed a Linux VM (Ubuntu 22.04) using B1s size 
- Configured inbound access via **port 22 (SSH)** only
- Applied an NSG to control and monitor network access
- Enabled **Just-In-Time VM Access** to restrict constant SSH exposure
- Scheduled **auto-shutdown** to reduce resource cost
- Organized resources using a tagged **Resource Group**
- Documented all steps with screenshots and explanations

---

### 🔐 Security Configurations

| Component | Setting |
|----------|---------|
| NSG Inbound Rule | Allow TCP on port 22 (SSH) |
| NSG Deny All | Default rule blocks all other inbound traffic |
| JIT Access | Enabled for SSH, allowed only from my IP |
| Auto-shutdown | Configured for 10:00 PM daily |
| Public IP + NIC | Set to auto-delete with VM |

-------


### 🖼️ Screenshots

- Basics Tab Configuration  
  
  <img width="519" alt="Screenshot 2025-05-01 at 11 48 00 AM" src="https://github.com/user-attachments/assets/bcd5af64-623c-4061-8c7c-b38a1f5d3fc0" />

- Networking Tab with NSG  

 <img width="483" alt="Screenshot 2025-05-01 at 11 48 06 AM" src="https://github.com/user-attachments/assets/0fda7bcd-2b1a-4928-86e2-4a5f79c49352" />

- VM Deployment
-   
  <img width="1121" alt="Screenshot 2025-05-01 at 11 50 59 AM" src="https://github.com/user-attachments/assets/2e49700a-9698-49f2-909c-dbd74f90e67c" />

- Just-In-Time Access Enabled

   <img width="685" alt="Screenshot 2025-05-01 at 1 22 38 PM" src="https://github.com/user-attachments/assets/2fb63470-bba6-4599-8035-d8b25ee5b7c0" />
   
- Auto-Shutdown Setup  
  
  <img width="785" alt="Screenshot 2025-05-01 at 11 35 21 AM" src="https://github.com/user-attachments/assets/48923c2d-6893-4a6c-8af1-80854dead58f" />
  
- Tags
  
  <img width="755" alt="Screenshot 2025-05-01 at 11 43 49 AM" src="https://github.com/user-attachments/assets/3e898016-d9c5-4c7f-b15f-cfc905af719e" />

- Pricing

  <img width="675" alt="Screenshot 2025-05-01 at 11 45 55 AM" src="https://github.com/user-attachments/assets/e7a124b8-12c5-443d-8fd0-ecbe8c07a012" />

---

### 💡 What I Learned
- How to deploy and configure a VM securely in Azure  
- The purpose and power of NSGs in network protection  
- The value of Just-In-Time access to reduce attack exposure  
- Resource tagging and cost-saving practices



### 🏷️ Tags
`#azure` `#az900` `#cloudfundamentals` `#nsg` `#virtualmachine` `#jitaccess` `#cybersecurity`

