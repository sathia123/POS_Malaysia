# POS_Malaysia
# Postman Collection

This repository contains a Postman collection for API testing.

## How to Import the Collection
1. Download the `postman_collection.json` file.
2. Open **Postman**.
3. Click **Import** and select the JSON file.
4. Start testing the APIs!

---

## How to Run the Collection

### **1️⃣ Run in Postman Manually**
- Open **Postman**.
- Go to **Collections** → Select the imported collection.
- Click **Run Collection** to execute all requests.

### **2️⃣ Run via CLI using Newman**
[Newman](https://www.npmjs.com/package/newman) is a command-line tool to run Postman collections.

#### **🔹 Install Newman (If Not Installed)**
Ensure you have **Node.js** installed, then run:
`npm install -g newman`


1. Navigate to the folder where postman_collection is imported
2. In visual code studio, open terminal
3. Execute `node test.js` (test script) to run test
4. Report will be generated in **newman** folder

### Notes
Uploaded test execution report for reference `POS_Malaysia-2025-03-23-13-31-42-106-0.html`
