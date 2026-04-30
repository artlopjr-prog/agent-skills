---
name: vercel-deploy
description: Deploy web apps and static sites to Vercel from the conversation. Use when user says "deploy my app", "push this live", "give me a live URL", or "deploy and give me the link". Supports 40+ frameworks. Deployments are claimable.
---

# Vercel Deploy

Auto-detects 40+ frameworks from package.json. Returns preview URL + claim URL.

## Steps
1. npm run build
2. tar -czf deploy.tar.gz --exclude=node_modules --exclude=.git .
3. POST to https://api.vercel.com/v13/deployments
4. Poll until state=READY, return url and claimUrl