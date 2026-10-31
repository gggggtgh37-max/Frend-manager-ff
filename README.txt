Friend API - Vercel deployment

1. Extract this ZIP.
2. Upload all files at the ZIP root to a GitHub repository (app.py and vercel.json must be in the repository root).
3. Import that repository into Vercel.
4. In Vercel Project Settings, set Root Directory to ./ (repository root).
5. Deploy. When deployment status is Ready, open https://YOUR-PROJECT.vercel.app/health

Expected health response: {"service":"FreeFire-API","status":"healthy"}

Routes in this project include /, /health, /add_friend, and /remove_friend.
Use only accounts and APIs you are authorized to use. Avoid sharing credentials in URLs or screenshots.
