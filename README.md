A phishing email sample impersonating Microsoft Outlook was analyzed. The sender’s display name was “Outlook Support,” but the actual domain used was webberit.us, confirming spoofing.

Email headers were examined to trace the message path. The Received fields indicated the message originated from a non-Microsoft IP address (89.47.165.109). SPF and DKIM validation passed for webberit.us, but this domain is unrelated to Microsoft, showing misuse of authentication.

The email contained a link labeled “Verify your account,” which redirected to http://secure-outlook-login.webberit.us/login. This mismatch between the visible and actual URL indicated a phishing attempt. An attachment named Security_Update.zip was also included and identified as malicious.

The body text used urgent language (“Your account will be suspended within 24 hours”) and contained minor grammatical errors and a distorted Microsoft logo.

Phishing indicators identified:

Fake sender domain

Header inconsistencies

Mismatched URLs

Malicious attachment

Urgent and threatening tone

Grammar and formatting issues

Conclusion: The analyzed email is a phishing attempt intended for credential theft or malware distribution.
