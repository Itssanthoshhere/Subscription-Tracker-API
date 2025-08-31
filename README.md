
<div align="center">
  <br />
    <a href="https://github.com/Itssanthoshhere/Subscription-Tracker-Api" target="_blank">
      <img src="https://i.ibb.co/xtTbHkfs/Readme-Thumbnail.png" alt="Project Banner">
    </a>
  <br />
  
  <div>
    <img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white" alt="node.js" />
    <img src="https://img.shields.io/badge/express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="express.js" />
    <img src="https://img.shields.io/badge/-MongoDB-13aa52?style=for-the-badge&logo=mongodb&logoColor=white" alt="mongodb" />
    <img src="https://img.shields.io/badge/-Arcjet-1E1E1E?style=for-the-badge&logo=shield&logoColor=white" alt="arcjet" />
    <img src="https://img.shields.io/badge/-Upstash-00E9A3?style=for-the-badge&logo=upstash&logoColor=white" alt="upstash" />
  </div>

  <h3 align="center">📦 SubDub: Subscription Tracker API</h3>
  <p align="center">A production-ready <b>Subscription Management System API</b> with <b>rate limiting, JWT authentication, email reminders,</b> and <b>workflow automation</b>.</p>

  <a href="https://drive.google.com/file/d/1WfEcDGi2eUFaO_i9TFlUJ86wObelhISn/view?usp=sharing" target="_blank">
    <img src="https://img.shields.io/badge/%20Backend%20Handbook-informational?style=for-the-badge&logo=swagger&logoColor=white" alt="Docs" />
  </a>
</div>

---

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)  
2. ⚙️ [Tech Stack](#tech-stack)  
3. 🔋 [Features](#features)  
4. 🤸 [Quick Start](#quick-start)  
5. 🕸️ [Snippets](#snippets)  
6. 🔗 [Assets](#links)  
7. 📞 [Contacts](#contacts)  

---

### <a name="introduction">🤖 Introduction</a>

SubDub is a **Subscription Management System API** designed to help users track, manage, and get notified about upcoming subscription renewals.  

It comes with:  
- **JWT authentication** for secure user sessions  
- **MongoDB & Mongoose models** for subscriptions and users  
- **Arcjet middleware** for bot detection and rate limiting  
- **Upstash Workflows** to schedule email reminders before renewals  
- **Nodemailer templates** for beautiful, responsive reminder emails  

---

### <a name="tech-stack">⚙️ Tech Stack</a>

- **[Node.js](https://nodejs.org/)** – runtime environment  
- **[Express.js](https://expressjs.com/)** – web framework  
- **[MongoDB](https://www.mongodb.com/)** – NoSQL database  
- **[Arcjet](https://arcjet.com/)** – security & rate-limiting middleware  
- **[Upstash QStash](https://upstash.com/)** – workflows for scheduling reminders  
- **[Nodemailer](https://nodemailer.com/)** – email delivery service  

---

### <a name="features">🔋 Features</a>

→ **Advanced Rate Limiting and Bot Protection**: with Arcjet that helps you secure the whole app.

→ **Database Modeling**: Models and relationships using MongoDB & Mongoose.

→ **JWT Authentication**: User CRUD operations and subscription management.

→ **Global Error Handling**: Input validation and middleware integration.

→ **Logging Mechanisms**: For better debugging and monitoring.

→ **Email Reminders**: Automating smart email reminders with workflows using Upstash.

and many more, including code architecture and reusability

---

### <a name="quick-start">🤸 Quick Start</a>

#### **Prerequisites**
- [Git](https://git-scm.com/)  
- [Node.js](https://nodejs.org/)  
- [npm](https://www.npmjs.com/)  

#### **Clone the Repository**
```bash
git clone https://github.com/Itssanthoshhere/Subscription-Tracker-Api.git
cd Subscription-Tracker-Api
````

#### **Install Dependencies**

```bash
npm install
```

#### **Setup Environment Variables**

Create `.env.development.local`:

```env
# PORT
PORT=5500
SERVER_URL="http://localhost:5500"

# ENVIRONMENT
NODE_ENV=development

# DATABASE
DB_URI=

# JWT AUTH
JWT_SECRET=
JWT_EXPIRES_IN="1d"

# ARCJET
ARCJET_KEY=
ARCJET_ENV="development"

# UPSTASH
QSTASH_URL=http://127.0.0.1:8080
QSTASH_TOKEN=

# NODEMAILER
EMAIL_PASSWORD=
```

#### **Run the Project**

```bash
npm run dev
```

API will be running at:
👉 [http://localhost:5500](http://localhost:5500)

---

## <a name="snippets">🕸️ Snippets</a>

<details>
<summary><code>Sample Subscription JSON</code></summary>

```json
{
  "name": "Netflix Premium",
  "price": 15.99,
  "currency": "USD",
  "frequency": "monthly",
  "category": "Entertainment",
  "startDate": "2025-01-20T00:00:00.000Z",
  "paymentMethod": "Credit Card"
}
```

</details>

---

## <a name="links">🔗 Links</a>

* **Arcjet** → [https://arcjet.com](https://arcjet.com)
* **Upstash QStash** → [https://upstash.com](https://upstash.com)
* **MongoDB Atlas** → [https://www.mongodb.com/atlas](https://www.mongodb.com/atlas)
* **Nodemailer** → [https://nodemailer.com](https://nodemailer.com)

---

### <a name="contacts">🔗 Contacts</a>

👤 **Santhosh VS**

* GitHub: [Itssanthoshhere](https://github.com/Itssanthoshhere)
* LinkedIn: [Santhosh VS](https://www.linkedin.com/in/thesanthoshvs/)

---

#### ⭐️ Show Your Support

If you liked this project, **give it a ⭐** and share it with others!

---
