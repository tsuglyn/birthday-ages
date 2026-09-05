BIRTHDAY AGES — PWA
====================

This is a static Progressive Web App. It can be hosted from any HTTPS web host.

Features
--------
• First name / last name / date of birth in DD/MM/YYYY.
• Automatic current age.
• Next birthday, age at next birthday and days remaining.
• Automatic sorting by next birthday.
• Edit and delete.
• Local browser storage; no account/server database.
• Add to Calendar creates an .ics calendar file with:
    - an all-day birthday event
    - yearly recurrence
    - a display alarm 7 days before the event

Important calendar note
-----------------------
A website cannot silently write directly into the iPhone Calendar. "Add to Calendar"
downloads a standards-based .ics file. On the iPhone, open/import that file and confirm
adding the event. After it has been added, the iPhone Calendar is responsible for the
annual reminder.

Hosting from Windows
--------------------
For a quick computer-only test, run a local web server in this folder, e.g.:
    py -m http.server 8000
Then browse to http://localhost:8000 on the PC.

For the iPhone Home Screen version, put these files on an HTTPS host. Examples include
GitHub Pages, Cloudflare Pages or Netlify. Once the public HTTPS address is available:
1. Open it in Safari on iPhone.
2. Use Safari's Share/Page menu and choose Add to Home Screen.
3. Keep "Open as Web App" enabled if that option appears.
4. Launch Birthday Ages from its Home Screen icon.

Backup note
-----------
Entries are stored locally in the web app/browser on that iPhone. Clearing website data
can remove them. A later version can add Export/Import backup.
