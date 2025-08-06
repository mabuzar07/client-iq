# ClientIQ Backend

This is the backend API for **ClientIQ**, an AI-powered B2B company research platform.

## 🚀 Features

- User authentication (JWT-based)
- OpenAI integration for research responses
- Vector similarity search (pgvector + PostgreSQL)
- MongoDB for document storage
- Secure and scalable Express API
- Environment config via dotenv
- API validation and security middleware

## 🛠 Tech Stack

- **Node.js** + **Express**
- **MongoDB** + **Mongoose**
- **PostgreSQL** + **pgvector**
- **OpenAI API**
- **JWT**, **Helmet**, **Rate Limiting**, **CORS**

## 📦 Setup Instructions

### 1. Clone the Repository
```bash
git clone <repo-url>
cd clientiq-backend-main
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Create `.env` File
```bash
cp .env.example .env
```
Update your `.env` with:
```env
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
OPENAI_API_KEY=your_openai_key
POSTGRES_URL=your_pg_url
```

### 4. Start the Server
```bash
npm run dev
```

API will run at: `http://localhost:5000`

---

## 📁 Folder Structure

```
src/
├── controllers/
├── middleware/
├── models/
├── routes/
├── services/
├── utils/
└── server.js
```

---

## 🔐 Auth

- JWT-based auth for protected routes
- Middleware: `auth.js`
- Token validation and user lookup

---

## 🧠 AI Research

- Uses OpenAI via `/api/company` endpoints
- AI summarization and business insight generation
- Optional use of pgvector for similarity lookup

---

## 🧪 Testing

You can test APIs with tools like:
- Postman
- Swagger (coming soon)

---

## 📝 License

MIT License.