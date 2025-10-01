# 🏅 Postman Badge Portfolio

This repository showcases my **Postman API testing & automation** skills, anchored by the **Postman-issued badge** I earned.  
(http[s]://badgr.com assertion link embedded below)

---

## 📌 Badge

You can view my credential here:

[![Postman Badge](https://api.badgr.io/public/assertions/TJmPvjTgSHG5PnZDwEhU6w/image)](https://badgr.com/public/assertions/TJmPvjTgSHG5PnZDwEhU6w?identity__email=nickroutsis%40gmail.com)

Or click here:  
https://badgr.com/public/assertions/TJmPvjTgSHG5PnZDwEhU6w?identity__email=nickroutsis%40gmail.com  

This badge represents validated skills in Postman — API design, testing, collections, automation, and more.

---

## 📂 Collections & APIs Demonstrated

| Project | Description | Highlights |
|:--|:--|:--|
| **Grocery Store API** | Simple CRUD on “products” | Chained requests, assertions, negative tests |
| **JWT Auth API** | Login / protected route | Token handling, refresh logic, error flows |
| **Payment Flow API** | Simulated payment or order | Multi-step flows, authentication, error scenarios |

Each collection is available in the [`collections/`](./collections) folder. Use the corresponding environment from [`environments/`](./environments) to run.

---

## ▶️ Running Tests & Reports

Install dependencies:

```bash
npm install -g newman newman-reporter-htmlextra
```
```bash
newman run collections/grocery-store.postman_collection.json \
  -e environments/dev.postman_environment.json \
  -r htmlextra \
  --reporter-htmlextra-export tests/grocery-report.html

🧰 Tools Used

🧪 Postman – API testing & scripting
⚙️ Newman – CLI automation
📈 htmlextra – HTML visual reports
🐙 GitHub – Version control & portfolio hosting

