# iOS Bypass Cron Job

This repository runs automated cleanup for the iOS Activation Bypass backend.

## Configuration

- **Endpoint:** `https://1osbr3aker.rf.gd/cron/cleanup.php`
- **Schedule:** Every 5 minutes
- **Timeout:** 10 minutes

## Manual Trigger

To run manually:
1. Go to **Actions** tab
2. Select **"Cleanup Cron Job"**
3. Click **"Run workflow"**

## Logs

View execution logs in:
1. GitHub Actions → Cleanup Cron Job → Latest run
2. InfinityFree logs: `/htdocs/logs/cleanup.log`

## Troubleshooting

If cron fails:
1. Check if endpoint is accessible
2. Verify .htaccess allows cron access
3. Check server error logs"# ios-bypass-cron" 
