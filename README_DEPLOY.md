# Deployment Instructions

Your site is ready for deployment! Follow these steps to push to GitHub and deploy to Vercel.

## Prerequisites
- GitHub account
- Vercel account (linked to GitHub recommended)
- `git` installed
- `gh` CLI installed (optional, but recommended)
- `vercel` CLI installed (optional)

## Step 1: Push to GitHub

1. Open your terminal in this folder:
   `cd "C:\Users\Sachin\Desktop\Agency\victorious-fitness-deploy"`

2. Create a new repository on GitHub:
   - Go to https://github.net/new
   - Name it `victorious-fitness-showcase`
   - Do NOT initialize with README, .gitignore, or license (we have them)

3. Push the code:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/victorious-fitness-showcase.git
   git branch -M main
   git push -u origin main
   ```

## Step 2: Deploy to Vercel

### Option A: Via Vercel Dashboard (Easiest)
1. Go to https://vercel.com/new
2. Import the `victorious-fitness-showcase` repository you just created.
3. Click **Deploy**. Vercel will auto-detect the HTML file.

### Option B: Via Vercel CLI
1. Run:
   ```bash
   vercel
   ```
2. Follow the prompts to log in and deploy.
