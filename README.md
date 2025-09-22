Absolutely! Here’s **one complete message** you can copy and paste directly as your README.md:

````markdown
# Day 1 – Express + PostgreSQL CRUD API

## 📌 Project Overview
A simple Node.js + Express server connected to PostgreSQL, implementing CRUD APIs for `items`. Tested with Postman.

---

## ⚡ Tech Stack
- Node.js
- Express
- PostgreSQL
- pg (node-postgres)
- dotenv
- cors
- nodemon (dev)

---

## 🚀 Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/gautamvmahle/day1-express-postgres.git
cd day1-express-postgres
````

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file in the project root:

```env
PORT=3000
DB_USER=your_user
DB_PASSWORD=your_password
DB_HOST=localhost
DB_PORT=5432
DB_DATABASE=day1db
```

> Use `.env.example` as a reference for your environment variables.

### 4. Run the server

```bash
npm run dev
```

Server runs at → `http://localhost:3000`

---

## 🔑 API Endpoints

### Root

* `GET /` → API is running 🚀

### Items

* `POST /api/items` → create new item
* `GET /api/items` → get all items
* `GET /api/items/:id` → get item by ID
* `PUT /api/items/:id` → update item by ID
* `DELETE /api/items/:id` → delete item by ID

---

## 🧪 Testing with Postman

1. Open Postman
2. Create a Collection → **Day1 API**
3. Add requests:

* `GET /`
* `POST /api/items` (Body → raw → JSON: `{ "name": "Pen", "description": "Blue ink" }`)
* `GET /api/items`
* `GET /api/items/:id`
* `PUT /api/items/:id` (Body → raw → JSON: `{ "name": "Updated Pen", "description": "Black ink" }`)
* `DELETE /api/items/:id`

---

## ✅ Deliverables

* CRUD API working locally
* `.env.example` included
* Public GitHub repo
* Postman screenshots

---

## 🧪 Postman Screenshots

### GET /

<img width="1272" height="1017" alt="ss1" src="https://github.com/user-attachments/assets/23a79951-7f0c-4d7e-aad5-7835440b2c8b" />


### POST /api/items
<img width="1272" height="1015" alt="ss2" src="https://github.com/user-attachments/assets/7ac99b51-1c4d-4791-ba01-ed7f32c0049e" />


### GET /api/items/1

<img width="1919" height="999" alt="ss3" src="https://github.com/user-attachments/assets/a73c1099-7bee-4e9c-9332-21c229a5f51e" />


### PUT /api/items/1
<img width="1919" height="989" alt="ss4" src="https://github.com/user-attachments/assets/584a664e-56a1-4353-90c6-118aa90c871f" />



### DELETE /api/items/1


<img width="1918" height="1008" alt="ss5" src="https://github.com/user-attachments/assets/70ab4233-3a90-4eca-86f2-d337b8bc50a5" />

```


---








