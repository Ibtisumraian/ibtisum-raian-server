# 🖥 Ibtisum Raian — Portfolio Server

This is the backend server for my personal portfolio site. It handles secure email sending from the contact form using `nodemailer` and integrates with a Gmail App Password setup.

---

## 🔗 Live Site & Server

- 🌍 **Live Client Site**: [https://ibtisum-raian.web.app/](https://ibtisum-raian.web.app/)  
- 🖥 **Client Repo**: [https://github.com/Ibtisumraian/ibtisum-raian-server](https://github.com/Ibtisumraian/ibtisum-raian-server)

---

## 🚀 Features

- ✉️ Email handling with `nodemailer`
- 🔐 Secure with Gmail App Password and `dotenv`
- 🌐 API endpoint for contact form submission
- 🛠 Built with `Express.js` and hosted on **Vercel**

---

## ⚙️ Technologies Used

- **Node.js**
- **Express.js**
- **Nodemailer**
- **CORS**
- **Dotenv**

---

## 📬 API Endpoint

### `POST /api/send-email`

Sends an email from the contact form.

#### 📥 Request Body:

```json Example :
{
  "name": "John Doe",
  "email": "john@example.com",
  "message": "Hello, this is a test message."
}


