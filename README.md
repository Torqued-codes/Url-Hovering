🛡️ Link Hover Scanner Extension
Hover over any link. Know instantly if it's safe. Free. No account needed.
📌 What is the Mailed It Extension?
The Mailed It Link Hover Scanner is a browser extension that protects you from malicious URLs in real time — without you having to click anything. Simply hover your mouse over any link on any webpage, and Mailed It instantly analyzes it and shows a popup telling you whether it's safe or dangerous.
No more clicking suspicious links. No more second-guessing URLs. Protection happens automatically, every time.
✨ Key Feature — Link Hover Scanner
🖱️ How it works
Install the extension on your browser
Browse the web as you normally would
Hover over any URL on any webpage
A popup instantly appears showing:
✅ Safe — the link is clean
⚠️ Suspicious — proceed with caution
🚨 Threat Detected — the link is malicious
⚡ What gets checked on hover
Every URL is scanned across 35 vulnerability checks in milliseconds:
Category
What it checks
SQL Injection
Malicious database query patterns
XSS
Cross-site scripting attempts
Fake Domains
Typosquatting & impersonation
Phishing Keywords
Words used to trick users
Suspicious TLDs
High-risk top-level domains
IP Address URLs
Raw IP instead of domain name
URL Shorteners
Hidden destination links
Data Theft Patterns
Password/card data in URLs
High URL Entropy
Randomly generated phishing URLs
Excessive Subdomains
Subdomain abuse to mimic real sites
Brand in Subdomain
Fake brand names as subdomains
Number-Letter Substitution
paypa1, g00gle style fakes
@ Symbol Trick
Browser URL redirection abuse
Hex/Encoded Characters
Disguised malicious characters
Suspicious File Extensions
.exe, .bat, .ps1 links
Free Hosting Abuse
Phishing pages on free hosts
Email Tracking Abuse
SendGrid/Mailchimp redirect abuse
Auto-Generated Domains
Bulk phishing campaign domains
Nested URLs
Hidden URLs inside parameters
Click Tracking Paths
Phishing redirect endpoints
Directory Traversal
File system attack patterns
Command Injection
System command patterns
Open Redirect
Redirect parameter abuse
Excessive URL Length
Abnormally long suspicious URLs
Deep URL Path
Hidden phishing pages in deep paths
Special Characters
@, %, # used to disguise URLs
Excessive Dots
Domain dot abuse
Long Query String
Hidden destinations in parameters
Multiple Redirects
Chained redirect abuse
SendGrid Redirect Abuse
Email service phishing routes
Encoded Hidden URLs
Masked malicious destinations
Urgency Words
"urgent", "suspended", "act-now"
Free Hosting Platforms
netlify, vercel, github.io abuse
Numeric Subdomains
Auto-generated phishing subdomains
HTTPS Check
Missing SSL/TLS on sensitive pages
🌐 Browser Compatibility
The Mailed It extension works across all major browsers:
Browser
Supported
🟡 Google Chrome
✅
🟠 Mozilla Firefox
✅
🔵 Microsoft Edge
✅
🔵 Opera
✅
🟣 Brave
✅
🔴 Safari
✅
Works on Windows, macOS, and Linux.
🚀 Installation
⚠️ Extension coming soon to browser web stores!
Chrome / Edge / Brave / Opera
Visit the Chrome Web Store (link coming soon)
Click Add to Chrome
The extension activates immediately — no setup, no account needed
Start hovering over links for instant protection
Firefox
Visit Firefox Add-ons (link coming soon)
Click Add to Firefox
Done — protection starts instantly
Manual Installation (Developer Mode)
1. Download the extension ZIP from this repo
2. Unzip the folder
3. Open Chrome → chrome://extensions
4. Enable "Developer Mode" (top right)
5. Click "Load unpacked"
6. Select the unzipped folder
7. Extension is now active!
🔒 Privacy & Permissions
Permission
Why it's needed
activeTab
To scan links on the current page
scripting
To inject the hover detection script
No account required
Works completely anonymously
No data stored
URLs are analyzed locally, never saved
No tracking
We don't collect your browsing data
⚙️ Technical Details
Manifest Version: V3 (latest Chrome standard)
Language: JavaScript
Analysis: 35 client-side pattern checks
Response Time: < 80ms per URL
Data sent externally: None — all checks run locally in your browser
📁 File Structure
extension/
  manifest.json       ← Extension config (Manifest V3)
  content.js          ← Hover detection + 35 security checks
  popup.css           ← Popup styling
  icons/              ← Extension icons
🛠️ Built With
Chrome Extension Manifest V3
Vanilla JavaScript
CSS3
 
📬 Contact
For queries or support: ruasthon@gmail.com
© 2026 Mailed It. All rights reserved. Built to protect people, not profit from fear.
