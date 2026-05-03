# Privacy Policy - Secure Sheet Password Manager

**Effective Date:** May 3, 2026

## 1. Introduction
This Privacy Policy explains how the **Secure Sheet Password Manager** ("the Extension") handles your information. Built on the values of transparency and the inherent dignity of the individual, this solution is designed to give you absolute control over your digital security.

## 2. Our Zero-Knowledge Philosophy
We operate under a "Zero-Knowledge" architecture. This means:
* We do **not** have servers that store your passwords.
* We do **not** have access to your Google Sheet.
* We do **not** see your Master Key.

## 3. Information Collection and Use
To provide the service, the Extension interacts with your Google Account in the following ways:

### A. Google User Data
The Extension uses the `chrome.identity` API to request authorization to access your Google Sheets. 
* **Scope:** We use the `https://www.googleapis.com/auth/drive.file` scope. 
* **Usage:** This permission is used *exclusively* to create and edit the specific Google Sheet used to store your encrypted data. We cannot see or access other files in your Google Drive.

### B. Encryption & Local Storage
Your passwords are encrypted locally on your machine using your Master Key before being sent to Google Sheets. 
* Only the **encrypted ciphertext** is stored in your Sheet.
* Your Master Key is never transmitted over the internet or stored in a way that we can access.

## 4. Data Disclosure
The Extension’s use and transfer of information received from Google APIs to any other app will adhere to [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.
* **No Sale of Data:** We never sell your personal data to third parties.
* **No Advertising:** Your data is never used for advertising purposes.

## 5. Security
While we use industry-standard encryption to protect your data, the security of your information also depends on the strength of your Master Key and the security of your Google Account. We recommend enabling Two-Factor Authentication (2FA) on your Google Account.

## 6. Contact
If you have questions about this policy or the ethical standards of this project, you can contact the developer via the GitHub repository issues page.
