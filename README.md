# 🧠 Multimodal AI – Mistral + SDXL Playground

This repo contains:
- **backend/** → Hugging Face Spaces (Gradio app running Mistral for text + SDXL for images)
- **frontend/** → Next.js app deployed on Vercel (embeds the Hugging Face app)

---

## 🚀 Deployment

### 1️⃣ Backend (Hugging Face Spaces)
1. Go to [Hugging Face Spaces](https://huggingface.co/spaces) → Create New Space.
2. Select **Gradio** as SDK.
3. Upload contents of `backend/` folder.
4. Set hardware to **GPU** (T4/A10 for free/Pro users).

### 2️⃣ Frontend (Vercel)
1. `cd frontend`
2. `npm install`
3. Push to **GitHub**.
4. Go to [Vercel](https://vercel.com) → Import GitHub repo.
5. Vercel will deploy automatically.

✅ Done! Your Vercel site will load the Hugging Face app inside an iframe.
