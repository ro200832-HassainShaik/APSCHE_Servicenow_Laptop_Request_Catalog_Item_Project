# 💻 Laptop Request Catalog Item – ServiceNow Project

## 📜 Project Description
This project is a ServiceNow **Service Catalog Item** designed to streamline the process of requesting laptops within an organization. It allows employees to easily submit a laptop request with required details, dynamic form behavior, and clear guidance. It also includes update sets for deployment and governance.

--- 

## ❗ Problem Statement
Employees in the organization need a quick and efficient way to request laptops for work.  
The current process is manual and prone to delays, with no dynamic form behavior to guide users or ensure accurate data collection.  

**Solution:**  
A Service Catalog item was created in ServiceNow to:
- Allow users to request a laptop easily.
- Provide dynamic fields that appear based on user input.
- Give clear instructions for each variable.
- Include a “Reset Form” button for convenience.
- Ensure all changes are tracked via update sets for deployment and governance.

---

## 📌 Key Features
- Catalog Item: **Laptop Request**
- Variables:
  - Laptop Model
  - Justification
  - Additional Accessories
  - Accessories Details
- UI Policy for dynamic field visibility.
- UI Action: **Reset Form**
- Category: **Hardware**
- Added to: **Service Catalog**

---

## 📂 Files in This Repository
- `LaptopRequest_LocalUpdateSet.xml` – Local update set (importable to ServiceNow)
- `LaptopRequest_RemoteUpdateSet.xml` – Remote update set
- `LaptopRequest_UpdateSetSummary.pdf` – Summary of changes
- `LaptopRequest_RemoteUpdateSummary.pdf` – Detailed update actions

---

## ⚙️ How to Import and Test
1. Download the `.xml` update set files.
2. Go to your ServiceNow instance.
3. Navigate to: **System Update Sets → Retrieved Update Sets**
4. Click **Import XML** and upload the update set.
5. Preview → Commit.
6. Test via: **Service Catalog → Hardware → Laptop Request**.

---
