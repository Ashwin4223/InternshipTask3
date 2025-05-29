# InternshipTask3
ElevateLabs Internship Task13
# 🔒 Vulnerability Scan Report using OpenVAS / Nessus Essentials

This README provides detailed steps and documentation for conducting a basic vulnerability scan on your local machine using **Nessus Essentials**. The process includes setting up the scan, identifying vulnerabilities, and documenting the results.

---

## 📌 Prerequisites

- Installed vulnerability scanner: **Nessus Essentials**
- Administrative access
- Internet connection for plugin updates

---

## ✅ Scan Steps

1. **Install Nessus Essentials**  
   Download and install the preferred vulnerability scanner.

   ![image](https://github.com/user-attachments/assets/69878cf0-cbfd-4116-8f4a-67810b4c0452)
   ![image](https://github.com/user-attachments/assets/5a46f79d-dad3-492b-820c-d146ec2b496e)
   ![image](https://github.com/user-attachments/assets/cc79f958-5ed9-4fae-8a64-98945fe8399a)

2. **Set Scan Target**  
   Set your local machine’s IP address or `localhost` as the target.

   ![image](https://github.com/user-attachments/assets/92ea8567-3ed8-4c2c-a4c6-9ff5688c7021)

3. **Start a Full Vulnerability Scan**  
   Run a full scan on the selected target to identify potential security issues.

4. **Wait for Completion**  
   The scan may take **30 to 60 minutes** to complete depending on your system specs.

   ![image](https://github.com/user-attachments/assets/f5c3eab0-a0bb-494f-9693-b59b62e4eece)

5. **Review the Report**  
   Examine the vulnerability report and note severity ratings (Low, Medium, High, Critical).
   
   ![image](https://github.com/user-attachments/assets/baadb9bc-abbf-4a1d-9225-aa4a3e1bb539)
   
6. **Research Mitigations**  
   Search for simple fixes or recommended mitigations for identified vulnerabilities.

7. **Document Critical Vulnerabilities**  
   Focus on vulnerabilities with **High** or **Critical** severity.

   ![image](https://github.com/user-attachments/assets/0ea66e6a-a6ad-47ff-9606-325e60ee90c3)
   ![image](https://github.com/user-attachments/assets/8fd127be-ab39-46a0-acf0-99f5422a0fac)
   ![image](https://github.com/user-attachments/assets/212070c7-cac6-4748-b7ad-af4531dfa2f8)

8. **Take Screenshots of Results**  
   Capture relevant parts of the scan report for documentation.

---

## 🔍 Key Vulnerability Highlight

Vulnerability: Outdated version of Dropbear SSH Server
Severity: Critical Description: Known exploits in older versions can allow arbitrary code execution or security bypass.
Fix Applied: Updated to the latest version of Dropbear SSH Serverto the latest version

---

## 📌 Notes

- Always test fixes in a controlled environment.
- Keep scanners and plugins updated.
- Avoid running scans during high-use periods.

---

