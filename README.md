# Instacart Work Tracker 4.3

A simple mobile-first tracker for Instacart work days, mileage, receipts, screenshots, CSV exports, and reliable share-based backup.

## Live app

The app should publish at:

```text
https://mypioneeringlife.github.io/Instacart-work-tracker/
```

## Backup system

Version 4.3 removes the Google Cloud / Google Drive API requirement.

Instead, open the app and go to:

```text
Backup → Share Backup
```

Then choose Google Drive, Files, OneDrive, Dropbox, email, or any other destination from your phone or computer share menu.

This creates a full JSON backup file that includes:

- saved work days
- mileage
- earnings
- tips
- receipt photo data
- screenshot proof data
- settings

## Restore

To restore a previous backup:

```text
Backup → Restore Backup
```

Select the JSON backup file you saved earlier.

## Year-end export

The Backup tab also includes:

- Download Work CSV
- Download Expenses CSV
- Download Year Package

The CSV exports are intended for year-end review, tax prep, and recordkeeping.

## Colors

The app uses an Instacart-inspired palette:

```text
Green: #43B02A
Carrot orange: #FF8200
Dark background: #112019
```

## GitHub Pages setup

If Pages is not already active:

1. Open this repository on GitHub.
2. Go to **Settings**.
3. Go to **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Branch: **main**.
6. Folder: **/root**.
7. Save.
