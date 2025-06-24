# Task-2-Phishing-
## Analyze a Phishing Email Sample
### Sample phishing email
<br>

![image](https://github.com/user-attachments/assets/327d4be8-09e8-4e45-912b-87a923eb26a5)

<br>

### Analyze Header
![image](https://github.com/user-attachments/assets/97ef362b-75df-428a-8707-f20b1a4418d3)

### After analyzing the header information, it was found that the email contains phishing indicators.
![Result](https://github.com/user-attachments/assets/40f40469-6899-4191-871e-8baaf8939f6a)

### By using another tool 
![result1](https://github.com/user-attachments/assets/d5ab72c3-72e0-41f3-96a4-f7b362f097be)
<br>

### The spoofed sender email address was identified using the analysis tool.
support@paypalsecure-alert.com

### The email headers for discrepancies using Google Header Analyzer is
<br>
SPF: fail with IP Unknown!

DKIM: None

DMARC: Fail

### Suspicious links or attachments 
"Confirm Your Information"

### The threatening language in the email body is 

"Your PalPay account is limited. You have 24 hours to solve the problem or your account will be permanetly disabled."

Real URL: http://paypal-verification-alert123.com

Domain Name: http://paypalsecure-alert.com

#### Mismatch is Found

In this sample email spelling or grammar errors not found.

### Summary
This email is a phishing attempt. 
It attempts to steal user credentials through fear tactics, spoofed sender, and a fake link designed to look like a PayPal login page.
It fails basic authenticity checks (SPF, DKIM, DMARC).
