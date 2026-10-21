# ops-backup-sync

A personal backup configuration that uses rclone to upload already-encrypted backup files to the user's own Google Drive. It is not a public service; only the owner and a few authorized collaborators use it.

## Privacy Policy

- The app accesses only files in the authorizing user's own Google Drive via the Google Drive API, to upload and download backups.
- No user data is collected, stored, or shared with any third party. OAuth tokens are kept only in the local rclone configuration on the user's machine.
- Files unrelated to backups are not read; nothing is used for advertising or analytics.
- Access can be revoked at any time at https://myaccount.google.com/permissions.
