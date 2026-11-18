# BM FUTUROMIND AI — Data, HR Analytics & Python Academy (150 Modules)

## Option 1: Free Static Hosting (GitHub Pages / Netlify / Vercel)
1. Unzip and push all files to a GitHub repository.
2. In GitHub: **Settings -> Pages -> Deploy from branch (`main` / root)**.
3. GitHub Pages serves `index.html` automatically for free.

## Option 2: Free Python Server Hosting (Render.com)
1. Push this repo to GitHub.
2. Create a free **Web Service** on Render connected to your repo:
   - Build Command: `pip install -r requirements.txt`
   - Start Command: `gunicorn app:app`

## Run Locally
```bash
pip install -r requirements.txt
python app.py
```
Open http://127.0.0.1:5000 in your browser.
