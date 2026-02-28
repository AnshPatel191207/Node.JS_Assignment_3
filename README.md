# State Statistics Management API

## 📌 Objective

A full REST API built using Express.js to manage statistical data of Indian states using an in-memory JSON array.

This project demonstrates:

* REST architecture
* GET, POST, PUT, PATCH, DELETE operations
* Dynamic routing
* Resource manipulation
* Proper HTTP status codes

---

## 🛠 Tech Stack

* Node.js
* Express.js
* CORS
* Postman
* Render Deployment

---

## 📊 Data Structure

Each state follows:

```json
{
  "id": 1,
  "name": "Gujarat",
  "population": 63872399,
  "literacyRate": 78.03,
  "annualBudget": 243965,
  "gdp": 21000000
}
```

---

# 🚀 API Routes

## ✅ GET Routes

* GET `/states` → All states
* GET `/states/:id` → State by ID
* GET `/states/highest-gdp` → State with highest GDP

---

## ✅ POST Route

* POST `/states` → Add new state

---

## ✅ PUT Routes

* PUT `/states/:id` → Replace full state
* PUT `/states/:id/budget` → Update budget
* PUT `/states/:id/population` → Update population

---

## ✅ PATCH Routes

* PATCH `/states/:id/literacy` → Update literacy rate
* PATCH `/states/:id/gdp` → Update GDP
* PATCH `/states/:id` → Partial update

---

## ✅ DELETE Routes

* DELETE `/states/:id` → Delete by ID
* DELETE `/states/name/:stateName` → Delete by name
* DELETE `/states/low-literacy/:percentage` → Delete states below literacy rate

---

# 💻 Run Locally

```bash
git clone https://github.com/yourusername/state-statistics-api.git
cd state-statistics-api
npm install
npm run dev
```

Server:

```
http://localhost:5000
```

---

# 🌐 Deployment

https://node-js-assignment-3-tekf.onrender.com/

---

# 📬 Postman Documentation

https://documenter.getpostman.com/view/50841281/2sBXcHhyte
