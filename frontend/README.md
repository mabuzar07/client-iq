# ClientIQ Frontend

Frontend for **ClientIQ** — AI-powered B2B company research tool.

## 🌐 Tech Stack

- **React** (with CRA)
- **TypeScript**
- **Axios** for API requests
- **MUI** for UI components
- **Context API** for state management

## 🚀 Features

- User authentication and session management
- Company research UI powered by OpenAI backend
- Responsive and modern UI using Material UI
- Loading and error feedback states
- Environment-based API URLs

---

## 📦 Setup Instructions

### 1. Clone the Repository
```bash
git clone <repo-url>
cd clientiq-frontend-main
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Create `.env` File
```bash
cp .env.example .env
```
Update your `.env`:
```env
REACT_APP_API_URL=http://localhost:5000/api
```

### 4. Start the App
```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

---

## 🧠 AI-Powered Research

This frontend sends requests to OpenAI-powered backend routes like:
- `/api/company/research`
- `/api/company/summary`

---

## 📝 License

MIT License.