# Deployment Guide

## GitHub Repository
- **Repo**: https://github.com/brandoncheema-ops/compliance-dashboard
- **Branch**: main

## Render.com Static Site

### Setup
1. Go to [Render Dashboard](https://dashboard.render.com)
2. Click **New** â **Static Site**
3. Connect your GitHub account and select `brandoncheema-ops/compliance-dashboard`
4. Configure:
   - **Name**: compliance-dashboard
   - **Branch**: main
   - **Build Command**: *(leave blank)*
   - **Publish Directory**: `.`
5. Click **Create Static Site**

### Live URL
Once deployed: `https://compliance-dashboard.onrender.com`

### Auto-Deploy
Render auto-deploys on every push to `main`. Just push changes and the site updates automatically.
