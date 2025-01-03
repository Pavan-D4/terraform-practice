To install **Terraform** on a Windows system, follow these steps:

---

### **Step 1: Download Terraform**
1. Visit the official Terraform website: [https://developer.hashicorp.com/terraform/downloads](https://developer.hashicorp.com/terraform/downloads).
2. Select the appropriate version for Windows.
3. Download the ZIP file.

---

### **Step 2: Extract Terraform**
1. Once the ZIP file is downloaded, extract its contents using a tool like **WinRAR** or **7-Zip**.
2. The extracted folder will contain the `terraform.exe` file.

---

### **Step 3: Add Terraform to System PATH**
1. Move the `terraform.exe` file to a directory of your choice (e.g., `C:\Terraform`).
2. Add this directory to your system's PATH:
   - Right-click on **This PC** or **My Computer** and select **Properties**.
   - Click on **Advanced system settings** > **Environment Variables**.
   - Under **System Variables**, find and select the `Path` variable, then click **Edit**.
   - Add the path to the folder where `terraform.exe` is located (e.g., `C:\Terraform`).
   - Click **OK** to save changes.

---

### **Step 4: Verify Installation**
1. Open a **Command Prompt** or **PowerShell** window.
2. Type the following command and press Enter:
   ```bash
   terraform -v
   ```
3. You should see the installed Terraform version displayed.

---

### **Step 5: (Optional) Install a Text Editor**
Install a text editor like **Visual Studio Code** and add the **HashiCorp Terraform Extension** for syntax highlighting and support.

---

Terraform is now installed and ready to use. Let me know if you encounter any issues! 🚀