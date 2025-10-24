
## Virtual Private Cloud (VPC)

**Name:** INDHUMATHI L 
**Register Number:** 212224220037

---

## AIM
To study the steps involved in setting up a private cloud using **AWS** or **Microsoft Azure** platforms and explore its core features and services.

---

## PROCEDURE

### **Step 1: Create a Cloud Account**
- Sign up for an account on **AWS** or **Microsoft Azure**.
- Complete verification using your **email** and **credit card**.
- Log in to the **AWS Management Console** or **Azure Portal**.

---

### **Step 2: Set Up a Virtual Private Cloud (VPC / VNet)**
- **For AWS:**
  1. Go to **VPC Dashboard** → Click **Create VPC**.
  2. Enter a name and specify the **CIDR block** (e.g., `10.0.0.0/16`).

- **For Azure:**
  1. Navigate to **Virtual Network (VNet)** in Azure Portal.
  2. Create a VNet by defining **name**, **region**, and **address space**.

---

### **Step 3: Configure Subnets and Routing**
- Create **Public** and **Private Subnets** within the VPC or VNet.
- Configure **Route Tables** to manage traffic between subnets and the internet.
- Attach an **Internet Gateway** to the public subnet for external connectivity.
- Keep private subnets isolated for internal communication.

---

### **Step 4: Create and Launch Instances**
- Launch an **EC2 Instance** (AWS) or **Virtual Machine** (Azure) within your VPC/VNet.
- Choose an appropriate **AMI** or **OS Image** (Ubuntu, Amazon Linux, Windows).
- Assign each instance to the respective subnet (Public/Private).

---

### **Step 5: Security Configuration**
- Create **Security Groups** (AWS) or **Network Security Groups (NSGs)** (Azure).
- Configure **inbound/outbound rules**:
  - Allow `SSH (22)` for Linux access.
  - Allow `RDP (3389)` for Windows access.
  - Allow `HTTP (80)` for web servers.
- Ensure private subnet instances are **not directly accessible** from the internet.

---

### **Step 6: Storage and Networking**
- Attach **Elastic Block Store (EBS)** volumes or **Azure Managed Disks**.
- Configure **Load Balancers** and **NAT Gateways** if needed.
- Verify DNS, IP allocation, and subnet connectivity.

---

### **Step 7: Testing**
- Use `ping`, `ssh`, or **RDP** to check connectivity between instances.
- Test public instance access through the internet.
- Confirm internal communication between private instances.

---

## OUTPUT


 VPC / VNet Creation 
 
<img width="1920" height="1200" alt="VPC" src="https://github.com/user-attachments/assets/a631fc4a-4a29-4ba5-8e40-65970527df1e" />

 
Subnets & Routing Configuration 

<img width="1920" height="1200" alt="VPC ROUTING" src="https://github.com/user-attachments/assets/4cecc4ba-25e8-4a79-8e86-0b102341cbba" />

<img width="1920" height="1200" alt="SUBNETS" src="https://github.com/user-attachments/assets/74dd00bf-4683-4ad4-a4e1-1dfbc884363b" />

 EC2 / VM Launch 

<img width="1919" height="988" alt="EC2 Instances" src="https://github.com/user-attachments/assets/175dcf06-6a7e-444b-8d2f-4392b87dd4ca" />

 
 Network Testing Results 

<img width="1920" height="1200" alt="grade" src="https://github.com/user-attachments/assets/53c4cfac-db45-4f59-9f65-e5fb788dd902" />

---

## RESULT
A **private cloud environment** was successfully created using the **AWS/Azure** platform.  
Core components such as **VPC/VNet**, **Subnets**, **Instances**, and **Security Groups** were configured.  
The setup was tested and verified for **internal communication** and **external access** as per the configuration.

---

