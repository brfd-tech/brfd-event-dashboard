# BRFD Event Dashboard

Passcode-protected event dashboard for Baton Rouge Fire Department event personnel.

The page content is encrypted with [StatiCrypt](https://github.com/robinmoisson/staticrypt). Viewers enter the passcode provided by BRFD to open it. The passcode is not stored in this repository.

## Updating the dashboard

1. Re-encrypt the updated dashboard with StatiCrypt.
2. Replace `index.html` with the new encrypted file.
3. Commit and push. GitHub Pages republishes automatically.
