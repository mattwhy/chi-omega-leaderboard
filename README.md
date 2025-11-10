# Chi Omega Make-A-Wish Leaderboard (GitHub Version)

## What This Does

At **8:30 PM ET on November 10, 2025**, GitHub will automatically:
1. Fetch team data from Blackbaud API
2. Save it to a file in your repository
3. Your webpage will show this frozen snapshot forever after

## Step-by-Step Setup (I'll walk you through each step)

### Step 1: Create a GitHub Account (2 minutes)
1. Go to https://github.com
2. Click "Sign up"
3. Enter email, create password
4. Choose a username (anything is fine)
5. Verify your email

### Step 2: Install GitHub Desktop (Optional but easier)
1. Go to https://desktop.github.com
2. Download and install
3. Sign in with your GitHub account
4. **OR** skip this and use the website only

### Step 3: Upload This Project

#### Option A: Using GitHub Desktop (Easier)
1. Open GitHub Desktop
2. Click "Create a New Repository"
   - Name: `chi-omega-leaderboard`
   - Local Path: Choose `e:\Desktop\leaderboard-github`
   - Check "Initialize with README" = NO (we already have files)
3. Click "Publish repository"
   - Uncheck "Keep this code private" (must be public for free GitHub Pages)
4. Click "Publish repository"

#### Option B: Using GitHub Website (No software needed)
1. Go to https://github.com/new
2. Repository name: `chi-omega-leaderboard`
3. Select "Public"
4. DON'T check "Add a README"
5. Click "Create repository"
6. On the next page, you'll see options - choose "uploading an existing file"
7. Drag ALL files from `e:\Desktop\leaderboard-github` folder
8. Click "Commit changes"

### Step 4: Enable GitHub Pages (1 minute)
1. In your repository, click "Settings" (top menu)
2. Click "Pages" (left sidebar)
3. Under "Source", select "Deploy from a branch"
4. Under "Branch", select "main" and "/ (root)"
5. Click "Save"
6. Wait 2 minutes, refresh - you'll see your URL: `https://yourusername.github.io/chi-omega-leaderboard`

### Step 5: Enable GitHub Actions (1 minute)
1. In your repository, click "Actions" (top menu)
2. If you see "Enable Actions", click it
3. You should see the workflow "Capture 8:30 PM Snapshot"
4. It will run automatically at 8:30 PM ET

## How to Test It NOW (before 8:30 PM)

1. In your repository, click "Actions"
2. Click "Capture 8:30 PM Snapshot" (left sidebar)
3. Click "Run workflow" button (right side)
4. Click green "Run workflow"
5. Wait 30 seconds, refresh - you'll see it running
6. Check `snapshots/2025-11-10.json` - it should exist!

## What Happens Tonight

**8:30 PM ET:**
- GitHub runs the script automatically
- Fetches data from Blackbaud
- Saves `snapshots/2025-11-10.json`
- Commits it to your repository

**8:31 PM onwards:**
- Your webpage loads the snapshot
- Shows frozen 8:30 PM data
- Winner is locked

## Your Leaderboard URL

After Step 4, your leaderboard will be at:
```
https://YOUR-GITHUB-USERNAME.github.io/chi-omega-leaderboard
```

## Cost

**$0 forever** - GitHub Pages and Actions are free for public repositories

## Troubleshooting

**"Actions didn't run"**
→ Check Settings → Actions → Allow all actions

**"Page not loading"**
→ Wait 5 minutes after enabling Pages, GitHub needs time to build

**"Snapshot file not created"**
→ Go to Actions tab, click the failed run, see error message

---

## I'll Help You With Each Step

Just tell me which step you're on and I'll guide you through it!
