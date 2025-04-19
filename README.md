# 🌐 Azure VNet, Subnet & Custom DNS Lab

This project demonstrates how to create a virtual network (VNet) with a subnet, deploy a Windows Server 2019 VM into it, and apply custom DNS settings. This simulates a typical enterprise networking setup and teaches Azure network configuration.

---

## 🧰 Technologies Used

- Microsoft Azure
- Azure Virtual Networks (VNets)
- Subnets
- Windows Server 2019 Datacenter (Gen 1)
- Custom DNS
- RDP (Remote Desktop)

---

## ✅ What Was Done

- Created a new VNet `VNet-Lab` with CIDR block `10.0.0.0/16`
- Added a subnet `Subnet-1` with `10.0.1.0/24`
- Deployed a B1s Windows Server VM `NetTestVM` inside the subnet
- Enabled RDP for remote access
- Configured custom DNS (`1.1.1.1`) at the VNet level
- Restarted NIC to apply DNS and confirmed via `ipconfig /all`

---

## 🖼️ Screenshots

All screenshots are located in the `/screenshots/` folder:
- VNet and Subnet Overview
- VM Network Configuration
- DNS Setting in VNet
- `ipconfig /all` output showing custom DNS

---

## 📁 Folder Structure

azure-vnet-dns-lab/ ├── README.md ├── notes.txt └── screenshots/ ├── vnet-subnet-overview.png ├── vm-network-tab.png ├── dns-setting-vnet.png └── ipconfig-custom-dns.png


---

## 📝 Notes

This project simulates real-world enterprise network isolation and demonstrates the application of DNS customization for internal name resolution.

---

## 📬 Author

**Sargun Kaur**  
[GitHub](https://github.com/sargunsk)

---
