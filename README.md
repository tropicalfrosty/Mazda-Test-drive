# Mazda Test Drive (Frontend + Backend)

Live-test this on free tiers (no credit card):
- Backend: **Render** (Node/Express)
- Frontend: **Vercel** (React + Vite)

## 🚀 One‑Click Deploy

### Backend (Render)
[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/your-username/mazda-test-drive)

### Frontend (Vercel)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/your-username/mazda-test-drive)

---

## Manual Deploy

### Backend (Render)
1. Create a Render account.
2. Create a **Web Service** from this repo, with root `/backend`.
3. Set `Build Command`: `npm i`
4. Set `Start Command`: `npm start`
5. Ensure your PDF exists at `backend/templates/TEST DRIVE AGREEMENT.pdf` (already placed).
6. Deploy → take the URL (e.g., `https://mazda-backend.onrender.com`).

### Frontend (Vercel)
1. Import the repo into Vercel with root `/frontend`.
2. Add an Environment Variable: `VITE_API_URL` = your Render backend URL.
3. Deploy → open the URL (works on iPhone).

---

## Local Dev (optional)
- Backend:
  ```bash
  cd backend
  npm i
  npm start
  ```
- Frontend:
  ```bash
  cd frontend
  npm i
  npm run dev
  ```
  Visit http://localhost:5173 (ensure `VITE_API_URL=http://localhost:4000`).

