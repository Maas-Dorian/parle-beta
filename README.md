# Parle Rider - Vercel build

This folder is ready to deploy as a static Vercel site.

## Deploy with Vercel CLI

```bash
npm i -g vercel
vercel
```

Run the command from this folder and follow the prompts.

## Deploy with GitHub + Vercel

1. Put the contents of this folder in a GitHub repository.
2. In Vercel, choose **Add New > Project**.
3. Import the repository.
4. Leave Framework Preset as **Other**.
5. Leave Build Command and Output Directory empty.
6. Deploy.

There is no build step. `index.html` is the complete Parle Rider web app.
