# 🧠 NEXUS
### Your brain, connected.

NEXUS is a personal knowledge workspace built to capture thoughts, organize ideas, and connect your projects in one sleek, dark-themed dashboard.

> Your second brain. Your ideas. Your universe.

## ✨ Features

- 📝 **Quick Capture** — Save thoughts before they disappear.
- 💡 **Ideas & Projects** — Keep your brain organized.
- 🔎 **Instant Search** — Find anything in seconds.
- 📌 **Pinned Notes** — Keep important thoughts close.
- 🔄 **Idea Resurfacer** — Rediscover forgotten ideas.
- ☁️ **Cloud Sync** — Sync your notes with Supabase.
- 💾 **Import & Export** — Keep backups of your knowledge.
- 🌑 **Dark Dashboard** — A clean, developer-inspired interface.

## 🚀 Getting Started

### Run Locally

1. Download or clone this repository.
2. Open `index.html` in your browser.

For authentication and cloud sync, hosting through HTTPS (such as GitHub Pages) is recommended.

### Deploy with GitHub Pages

1. Put the app in the repository root as `index.html`.
2. Open **Settings → Pages**.
3. Select **Deploy from a branch**.
4. Choose `main` and `/(root)`.
5. Save and wait for deployment.

## ☁️ Cloud Backend

NEXUS uses **Supabase** for authentication and cloud note storage.

To configure your own instance:

1. Create a Supabase project.
2. Set up the `public.notes` table.
3. Enable Row Level Security (RLS).
4. Configure policies so users can access only their own notes.
5. Set your Site URL and Redirect URLs to your deployed site.
6. Configure the app with your Supabase project URL and publishable key.

**Security:** Never expose a Supabase `service_role` key or other secret keys in browser code. Keep RLS enabled.

## 🛠️ Built With

- HTML5
- CSS3
- JavaScript
- Supabase

## 📍 Project Status

NEXUS is under active development. More features and improvements are planned.

---

**NEXUS — Your brain, connected.** 🧠
