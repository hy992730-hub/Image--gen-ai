# Image--gen-ai
# AI Image Generator (FastAPI + Next.js)

## Backend (FastAPI)
- Located in `backend/`
- Main API: `/generate/stream`
- Health check: `/health`

## Frontend (Next.js)
- Located in `frontend/`
- Calls backend API to generate images

## Deployment
- Backend → Render (Python Web Service)
- Frontend → Vercel (Next.js Project)

## Usage
1. Deploy backend to Render.
2. Copy Render URL and replace inside `frontend/app/page.tsx`.
3. Deploy frontend to Vercel.
4. Open your Vercel link on Chrome mobile!
