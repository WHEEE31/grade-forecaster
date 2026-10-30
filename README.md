# CMU 15-122 Grade Forecaster

Replacement for the 15-122 grade forecaster that went down due to php vulnerability
RIP illiano's grade forecaster, will be missed.

This one can't read your gradescope or autolab but it can still forecast :D
Runs in browser - a single static page.

## BANG:


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
