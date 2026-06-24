# virtualbox-install-lab
Lab documenting installation and configuration of Oracle VirtualBox and a test VM

---

## 🖥 Creating a Virtual Machine

### 1. Start a New VM
- Clicked **New**  
- Entered VM name and selected OS type  

### 2. Configure Hardware
- Allocated RAM  
- Assigned CPU cores  
- Created a virtual hard disk (VDI recommended)  

### 3. Attach ISO
- Opened **Settings → Storage**  
- Attached the ISO file under the optical drive  

### 4. Start the VM
- Booted from the ISO  
- Installed the operating system  
- Verified successful boot into the OS  

---

## 📸 Screenshots
### Downloading VirtualBox
![Downloading VirtualBox](Downloading Virtual Box.png)

### Opening the VirtualBox Installer
![Open VirtualBox File](Open virtual box file.png)

### VirtualBox Installing
![VirtualBox Installing](virtual box installing.png)

### Downloading Windows Server 2025 ISO
![Downloading Windows Server 2025](Downloading Windows Server 2025.png)

### Configuring Windows Server 2025 VM
![Configuring Windows Server 2025](Configuring Windows Server 2025.png)

### VM Hardware Configuration
![Specify Hardware Disk](Specify Hardware Disk.png)

### Windows Server Booting
![Windows Server Boot](Screenshot 2026-06-24 170400.png)

### Windows Server Running in VirtualBox
![Windows Server Running](Screenshot 2026-06-24 170418.png)



---

## 🐞 Troubleshooting Notes
Some common issues and fixes:

- **Virtualization disabled:**  
  Enabled Intel VT‑x / AMD‑V in BIOS/UEFI.

- **Kernel driver error:**  
  Reinstalled VirtualBox or updated system drivers.

- **VM boot loop:**  
  Switched disk format to VDI or adjusted boot order.

(Add any issues you personally encountered.)

---

## 📚 What I Learned
- How hypervisors manage virtual hardware  
- How to install and configure VirtualBox  
- How to create and manage virtual machines  
- How to troubleshoot virtualization errors  
- Basics of OS installation inside a VM  

---

## ✔ Summary
This lab strengthened my understanding of virtualization, system setup, and VM management.  
It also demonstrates my ability to document technical work clearly and professionally.
