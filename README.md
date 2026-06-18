# Instacart Work Tracker 4.2

A simple mobile-first tracker for Instacart work days, mileage, receipts, screenshots, year-end export, and Google Drive backup.

## GitHub Pages

After files are committed, turn on GitHub Pages:

1. Open this repository on GitHub.
2. Go to **Settings**.
3. Go to **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Branch: **main**.
6. Folder: **/root**.
7. Save.

The app should publish at:

```text
https://mypioneeringlife.github.io/Instacart-work-tracker/
```

## Google Cloud origin

In Google Cloud, add this as the Authorized JavaScript origin:

```text
https://mypioneeringlife.github.io
```

Do not include the `/Instacart-work-tracker/` path in the authorized origin.

## Google Drive backup

Inside the app:

1. Go to **Export**.
2. Paste your OAuth Client ID.
3. Tap **Save Client ID**.
4. Tap **Connect Google Drive**.
5. Approve access.
6. Tap **Backup Now to Drive**.

The app creates/uses a Google Drive folder named:

```text
Instacart Work Tracker Backups
```

It updates:

```text
latest-backup.json
```

It also creates dated snapshots like:

```text
backup-2026-06-17.json
```

The app does not delete old backups automatically.
