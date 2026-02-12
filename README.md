# Task-1---FUTURE_CS_01

Vulnerability Assessment – Acunetix Test Website

Target
http://testphp.vulnweb.com

Step 1. Reconnaissance

Opened the website in browser.

Identified input points.

Found sign-in form and search box.

Step 2. Browser Inspection

Opened Developer Tools.

Used Network tab.

Reloaded the page.

Checked Response Headers.

Identified missing security headers.

Observed server and PHP version.

Step 3. Network Verification

Used Kali Linux inside Oracle VM.

Verified connectivity using ping.

Confirmed host response.

Step 4. Nmap Scan
Command used:
nmap testphp.vulnweb.com

Identified open port 80.

Detected HTTP service running.

Recorded results as evidence.

Step 5. Risk Classification

Classified findings as Low, Medium, High.

Outdated PHP marked High.

Missing headers marked Medium.

Open HTTP port marked Medium.

Step 6. Report Creation

Designed report in Canva.

Added screenshots as evidence.

Exported as PDF.

Compressed file to meet GitHub limit.

Uploaded to public repository.
