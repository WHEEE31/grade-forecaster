# CMU 15-122 Grade Forecaster

A single static page. No build step, no server, no dependencies.
Everything (PDF parsing, projection) runs in the browser; nothing is uploaded.

## Run it locally

Open `public/index.html` in a browser. That's it.

## Deploy on Render

1. Push this folder to a GitHub repo.
2. In the Render dashboard: **New → Static Site**, pick the repo.
3. Settings:
   - **Build Command:** leave empty
   - **Publish Directory:** `public`
4. Create. Render serves it at `https://<name>.onrender.com`.

`render.yaml` is included, so **New → Blueprint** pointed at the repo also works
and fills those settings in for you.
