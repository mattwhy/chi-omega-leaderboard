# Chi Omega Leaderboard - Snapshot Service

This repository provides automated snapshot capture for the Make-A-Wish Chi Omega Fall 2025 fundraising leaderboard.

## What This Does

A GitHub Actions workflow automatically captures team fundraising totals at exactly **8:30 PM ET on November 10, 2025** and saves them to `snapshots/2025-11-10.json`.

Your Luminate Online leaderboard page fetches this snapshot after the cutoff time to display frozen standings.

## Files

- `.github/workflows/snapshot.yml` - Automated workflow that runs at 8:30 PM ET
- `snapshots/2025-11-10.json` - Frozen snapshot (created automatically)
- `snapshots/README.md` - Placeholder file

## How It Works

1. **Before 8:30 PM ET**: Your leaderboard shows live data from Blackbaud API
2. **At 8:30 PM ET**: GitHub Actions workflow runs and captures snapshot
3. **After 8:30 PM ET**: Your leaderboard fetches frozen data from this repository

## Access the Snapshot

Once captured, the snapshot is publicly accessible at:
```
https://mattwhy.github.io/chi-omega-leaderboard/snapshots/2025-11-10.json
```

## Manual Testing

You can manually trigger the workflow:
1. Go to the **Actions** tab
2. Click **Capture 8:30 PM Snapshot**
3. Click **Run workflow** → **Run workflow**

This will create/update the snapshot file for testing purposes.
