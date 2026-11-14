<h1 align="center">Hi, I'm Samin 👋</h1>
<h3 align="center">AI Automation Engineer · LLM pipelines · Computer Vision · Workflow automation</h3>

<p align="center">
I build AI systems that run in production for real businesses in Bangladesh —<br/>
from reading Bangla/Banglish customer comments to recognising faces on factory CCTV.
</p>

---

### 🚀 Featured work

#### 🎯 [Lead Collector](https://github.com/samin2005/lead-collector) — AI lead detection for Facebook sellers
Detects buying intent in **Bangla and Banglish** Facebook Page comments and gets the seller
to the buyer first: instant alert, guarded AI auto-reply, lead pipeline. Running in production.
- **Cost-aware layered classifier:** noise filter → keyword matcher → LLM only as a last resort
- **Safe public AI replies:** the model never sees prices; its output is checked before posting
- **Provider-agnostic LLM layer:** Gemini and Claude behind one interface
- `Next.js` `TypeScript` `Supabase` `Facebook Graph API` `Gemini` `Claude` `Vercel`

#### 🎥 [Factory Face Recognition](https://github.com/samin2005/factory-face-recognition) — CCTV attendance for ~19,000 employees
Real-time face recognition on existing factory CCTV, writing attendance straight to the ERP.
- YOLOv8-face → ByteTrack → quality gate → ArcFace embeddings → FAISS matching
- **Temporal voting** recognises people whose individual crops are all too poor to match
- Disk-backed queue handles **200–280 people at shift change** without dropping a face
- `Python` `FastAPI` `InsightFace` `FAISS` `OpenCV` `React` `Oracle` `Docker`

#### 📦 Reels Uploader — desktop automation product *(private)*
A licensed desktop app that automates Reels uploading, sold to customers.
- **Cloudflare Workers** license server with an owner dashboard
- **Signed auto-updates** delivered through GitHub Releases

#### 🏗️ Sand Trading ERP — business management system *(private)*
Bilingual (বাংলা / English) ERP for a sand-trading business: barcode challans, vouchers,
stock, dues, ledgers, P&L, Excel reports, automatic SMS and WhatsApp messages. One-click install on any Windows PC.
- `Next.js 15` `TypeScript` `Prisma` `Tailwind`

---

### 🧰 Tech stack

**AI / ML**<br/>
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![PyTorch](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)

**Languages & frameworks**<br/>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

**Data, infra & integrations**<br/>
![PostgreSQL](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Meta](https://img.shields.io/badge/Facebook_Graph_API-0866FF?style=flat-square&logo=meta&logoColor=white)
![Webhooks](https://img.shields.io/badge/Webhooks-555555?style=flat-square&logo=webhooks&logoColor=white)

---

### 💡 How I work
- **Production first.** Each featured project above runs for a real business, not just as a demo.
- **Cost is a design constraint.** Cheap deterministic layers handle the bulk of the work, and the LLM only gets what they can't resolve.
- **AI output gets checked before it acts.** Models are guarded and their output is validated before it reaches customers.
- **I write down what broke.** Incidents become design rules and documentation.

---

<p align="center"><i>Open to AI Automation Engineer roles · Remote or Bangladesh</i></p>
