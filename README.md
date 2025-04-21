# 🧠 Directus Backend

This is the backend project for a headless CMS built with [Directus](https://directus.io), powered by PostgreSQL (NeonDB) and integrated with Cloudinary for file storage.

## 🛠️ Tech Stack

- **Directus** (Self-hosted)
- **PostgreSQL** (Neon)
- **Cloudinary** (File storage)
- **Node.js** for runtime
- Deployed on **Koyeb**

## 📁 Structure

- `.env` – Not committed, used for DB/API secrets
- `.gitignore` – Ignores `node_modules`, `.env`, and `uploads`
- `uploads/` – Default storage if Cloudinary isn’t used

## 🚀 Quick Start

```bash
npm install
npx directus start
