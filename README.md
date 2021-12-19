# Bludit 3.13.1 - About Plugin Stored Cross Site Scripting (XSS)
Bludit 3.13.1 - About Plugin Stored Cross Site Scripting (XSS)

### Exploit Title: Bludit 3.13.1 - About Plugin Stored Cross Site Scripting (XSS)
### Date: 20/12/2021
### Exploit Author: P.L.Sanu
### Exploit Author Website: https://www.plsanu.com
### Vendor Homepage: https://www.bludit.com
### Software Link: https://www.bludit.com/releases/bludit-3-13-1.zip
### Version: <= 3.13.1
### Tested on: Windows 10
### CVE : 
### Google Dork: N/A
### Reference: 

### Steps to Reproduce:
1. Login to the admin panel http://localhost/admin
2. Navigate to Themes section.
3. Activate the Blog X theme.
4. Navigate to plugins section.
5. In About plugin click the Settings button.
5. Inject the payload "><script>alert("XSS")</script> in About section.
6. Click on Save button.
7. Visit the site.
8. Malicious javascript code triggered.
