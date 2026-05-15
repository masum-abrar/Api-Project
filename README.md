# 🏦 Dmoney API Testing

## Project Overview

This project contains a complete API integration test suite for the **Dmoney transaction System**. It covers the full transaction flow including user creation, admin activation, deposits, send money, and cashout — tested using **Postman** and automated via **Newman**.

---

## 🚀 Technology Used

- [Postman](https://www.postman.com/) — API Testing & Collection
- [Newman](https://www.npmjs.com/package/newman) — CLI Collection Runner
- [newman-reporter-htmlextra](https://www.npmjs.com/package/newman-reporter-htmlextra) — HTML Report Generator

---

## 📄 API Documentation

Full API documentation generated via Postman:

🔗 **API Documentation:** [Click Here to View API Docs](https://masum-abrar02-4805137.postman.co/workspace/1931_-Md.-Atahar-Masum's-Worksp~477cb38b-d3c2-4e79-8618-45f626672fa4/collection/51287658-4e5796c6-a803-4a39-a3d1-16541d398b1a?action=share&creator=51287658)

---


---

## 📁 Project Structure

```
📁 Dmoney-Api-Testing/
  ├── 📄 README.md
  ├── 📄 Dmoney_Api_Assignment.postman_collection.json
  ├── 📄 .gitignore
  ├── 📄 package.json
  └── 📁 Reports/
        └── 📄 newman-report.html
```

---



## ⚙️ How to Run

### Prerequisites

Make sure you have **Node.js** installed: [https://nodejs.org](https://nodejs.org)

### Step 1 — Install Newman

```bash
npm install -g newman
npm install -g newman-reporter-htmlextra
```

### Step 2 — Clone the Repository

```bash
git clone https://github.com/masum-abrar/Api-Project
cd Dmoney-Api-Testing
```

### Step 3 — Run the Collection

```bash
newman run Dmoney_Api_Assignment.postman_collection.json --delay-request 5000 -r htmlextra --reporter-htmlextra-export Reports/report.html
```

### Step 4 — View the Report

Open `Reports/report.html` in your browser.

---

## 📊 Newman Report Screenshot

> Newman report generated after running the full collection:

<img width="486" height="436" alt="image" src="https://github.com/user-attachments/assets/2552926b-3947-4d82-b3b8-da37d408e109" />


---

