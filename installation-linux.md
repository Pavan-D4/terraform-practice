To install **Terraform** on Ubuntu, follow these steps:

---

### **Step 1: Update System Packages**
Open a terminal and update your package list to ensure all packages are up-to-date:
```bash
sudo apt update && sudo apt upgrade -y
```

---

### **Step 2: Install Required Dependencies**
Install the necessary dependencies:
```bash
sudo apt install -y wget unzip
```

---

### **Step 3: Download Terraform**
1. Visit the Terraform Downloads page: [https://developer.hashicorp.com/terraform/downloads](https://developer.hashicorp.com/terraform/downloads) and find the latest version link for Linux.
2. Alternatively, use the following command to download the latest version directly (replace `VERSION` with the desired version):
   ```bash
   wget https://releases.hashicorp.com/terraform/<VERSION>/terraform_<VERSION>_linux_amd64.zip
   ```
   For example:
   ```bash
   wget https://releases.hashicorp.com/terraform/1.6.0/terraform_1.6.0_linux_amd64.zip
   ```

---

### **Step 4: Extract the Terraform Binary**
Extract the downloaded ZIP file:
```bash
unzip terraform_<VERSION>_linux_amd64.zip
```

---

### **Step 5: Move Terraform Binary to System Path**
Move the `terraform` binary to a directory in your system's PATH (e.g., `/usr/local/bin`):
```bash
sudo mv terraform /usr/local/bin/
```

---

### **Step 6: Verify Installation**
Check if Terraform is installed and working:
```bash
terraform -v
```
You should see the Terraform version displayed.

---

### **Step 7: (Optional) Clean Up**
Remove the ZIP file to clean up your system:
```bash
rm terraform_<VERSION>_linux_amd64.zip
```

---

### **Step 8: (Optional) Use a Text Editor**
Install a text editor like **Visual Studio Code** with the Terraform extension for easier editing of configuration files.

---

Terraform is now installed on your Ubuntu system! Let me know if you need further assistance. 😊