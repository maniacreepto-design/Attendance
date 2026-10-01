# Attendance QR

Create unlimited, non-expiring QR codes for students (name, gender, parent phone) and scan them to text the parent.

**Live site:** https://YOUR-USERNAME.github.io/attendance-qr/

## Deploy on GitHub Pages
1. Create a new public repository named `attendance-qr`.
2. Upload `index.html`, `README.md` and `.nojekyll`.
3. Go to Settings > Pages. Under "Build and deployment", choose Branch: `main`, folder `/ (root)`, then Save.
4. Wait about a minute. Your site is at `https://YOUR-USERNAME.github.io/attendance-qr/`.

## Notes
- Runs fully in the browser. No server, database or account. Student data lives only inside each QR code.
- Settings and the scan log are saved in the browser of the device you use.
- The camera needs HTTPS, which GitHub Pages provides.
- Free SMS websites (e-FreeSMS, aFreeSMS) have no API, so the app copies the message and opens the site for you to press Send.
