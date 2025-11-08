This project demonstrates common security flaws in web applications and provides mitigation strategies for each. Conducted in a controlled Azure VM environment running IIS with PfSense as the network firewall, the lab explores four major vulnerabilities:
Cross-Site Scripting (XSS) – Exploiting unsanitized user input to execute malicious scripts.
Cross-Site Request Forgery (CSRF) – Forcing authenticated users to perform unintended actions.
Session Hijacking – Stealing or reusing session tokens to impersonate users.
Unrestricted File Upload – Uploading malicious files to gain remote code execution or persistence.
Each section details the vulnerability’s impact, detection methods, and secure coding practices such as input/output validation, enforcing strong session management, and implementing anti-CSRF tokens.
The project highlights how insecure configurations and weak validation can lead to severe exploitation scenarios, reinforcing the importance of secure web development and continuous monitoring.
