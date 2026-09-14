# GitHub Setup & Sharing Guide

## Step 1: Create a GitHub Repository

1. Go to **https://github.com/new**
2. Fill in:
   - **Repository name**: `earn-it-app` (or your preferred name)
   - **Description**: Multi-kid chore tracker with individual wheels and parent approvals
   - **Public** (so others can see it for feedback)
   - ✅ Add a README (we already have one, so you can skip this)
3. Click **Create repository**

## Step 2: Push Your Code to GitHub

Open your terminal and run these commands:

```bash
# Navigate to your project folder
cd earn-it-repo

# Initialize git (if not already done)
git init

# Add all files
git add .

# Create first commit
git commit -m "Initial commit: Multi-kid Earn It app with wheels, approvals, and reward bank"

# Add your GitHub repo as remote (replace USERNAME/earn-it-app with yours)
git remote add origin https://github.com/USERNAME/earn-it-app.git

# Push to GitHub
git branch -M main
git push -u origin main
```

## Step 3: Enable GitHub Pages (for live hosting)

1. Go to your GitHub repo
2. Click **Settings** (top right)
3. Scroll down to **Pages** section
4. Under **Source**, select `main` branch
5. Click **Save**
6. Your app will be live at: `https://USERNAME.github.io/earn-it-app/`

Wait 1-2 minutes for it to deploy.

## Step 4: Share for Feedback

### Option A: Share the GitHub Pages Link
Send people this link:
```
https://USERNAME.github.io/earn-it-app/
```
They can test the app directly in their browser.

### Option B: Invite Collaborators (for code feedback)
1. Go to your repo **Settings** → **Collaborators**
2. Click **Add people**
3. Enter their GitHub username
4. They'll get an invite and can review code, comment, or suggest changes

### Option C: Get Feedback via Issues
1. Ask people to test the app
2. They can click **Issues** tab and create an issue for:
   - Bug reports ("The spin button doesn't work on mobile")
   - Feature requests ("Can we add more than 2 kids?")
   - Feedback ("Love the design, but the timer is too fast")

## Step 5: Make Updates

When you want to make changes:

```bash
# Make your edits to index.html or other files

# Stage changes
git add .

# Commit with a message
git commit -m "Fix: cooldown timer display on mobile"

# Push to GitHub
git push
```

GitHub Pages will auto-update within a few seconds!

## Tips for Sharing

### In a Slack message:
> Hey! Check out the new Earn It app I built for the kids: https://USERNAME.github.io/earn-it-app/ 
> 
> Try it out and let me know what you think! You can:
> - Test the app at the link above
> - Leave feedback in the GitHub Issues tab
> - Suggest changes or improvements

### In an email:
> I've built a new chore tracker app for the kids. Would love your feedback!
> 
> **Live app**: https://USERNAME.github.io/earn-it-app/
> **GitHub repo**: https://github.com/USERNAME/earn-it-app
> 
> Feel free to:
> - Try it out
> - Open an issue if you see bugs
> - Suggest features
> - Fork it if you want your own version

## Need Help?

- **GitHub docs**: https://docs.github.com
- **GitHub Pages help**: https://docs.github.com/en/pages
- **Git commands**: https://git-scm.com/book/en/v2

---

**Questions?** Feel free to ask me for help with any step!
