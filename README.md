# WayStation website

Public site for WayStation, the sandboxed email app for Android:
https://waystationsecurity-app.github.io

## Verifying the download

Every WayStation APK is signed with the same key. The download page lists
the SHA-256 hash of the APK file itself — that catches a corrupted download.
As a cross-check against a tampered file, verify the APK's signing
certificate matches this fingerprint:

SHA-256: 5E:22:FD:9C:49:ED:B5:CA:51:8A:23:6D:16:BF:56:9A:C3:5C:2B:65:BB:3A:90:50:B4:75:FD:7F:E9:F2:D1:BE

Certificate subject: C = US, O = Android, CN = Android Debug

A swapped APK signed with a different key will not match this fingerprint.

## What WayStation is

WayStation opens email in a sealed sandbox on your phone: scripts don't run,
trackers don't load, and links can't be tapped by accident. It connects
directly from your phone to your email provider — no WayStation mail server
ever sees your mail. Pro threat checks (sender authentication, look-alike
domains, deceptive links, risky attachment file types) run on the phone.
Attachment contents are never scanned.

Works with Outlook, Hotmail, MSN, and Microsoft 365 today. iCloud and other
IMAP accounts are coming soon. Gmail is coming after a Google security
review.

See `privacy.html` on the site for the full privacy policy.
