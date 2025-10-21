# Aptosi Invoice Agent Privacy Policy

**Document Creation** 2025-07-01
**Last Updated:** 2025-10-20

This privacy policy ("Policy") explains how Aptosi, Inc. ("we," "us," or "our") collects, uses, and protects your information when you use the Aptosi Invoice Agent Chrome Extension (the "Service").

## Information We Collect

When you use the Service, we collect the following information:

1.  **Google User Info:** When you authenticate using your Google account, we collect your name, email address, and profile picture. This is used to identify you and personalize your experience.
2.  **User-Uploaded Data:** We collect and store the vendor master file (e.g., `vendors.csv`) that you explicitly upload through the extension's options page. This file is stored in your browser's local storage and is also sent to our secure backend to perform matching.
3.  **Email & Attachment Data:** To perform its core function, the Service scans your emails. This includes:
    * **Email Metadata:** Subject, sender, date, and email ID of emails identified as potential invoices.
    * **Extracted Text:** When you open an email, we scan the email body and the text content of attachments (such as PDFs, DOCX, and CSVs) to find payment-related information (e.g., IBAN, SWIFT, Beneficiary Name, Account Numbers).
4.  **Analytics Data:** We automatically collect anonymized usage data. See the "Analytics" section below for details.

## How We Use Your Information

We use the information we collect solely to provide and improve the Service:

* **To Authenticate You:** Your Google User Info is used to log you in and secure your account.
* **To Verify Invoices:** Your **Uploaded Data** is used as the "source of truth." We compare the **Extracted Text** from your emails against this data to check for matches or mismatches.
* **To Organize Your Inbox:** The Service uses the `gmail.modify` and `gmail.labels` permissions to create and apply labels (e.g., "Aptosi/Match", "Aptosi/Mismatch") to your emails based on the scan results.
* **To Provide Scan History:** We send your **Email & Attachment Data** (metadata and extracted text) and the resulting scan status to our secure backend servers (hosted on Google Firestore at `firestore.googleapis.com` and our servers at `preprod.aptosi.com`). This allows us to provide you with a history of your scan results.
* **To Improve the Service:** We use anonymized analytics to understand how the Service is used, identify bugs, and improve features.

## Data Storage and Sharing

We are committed to protecting your data.

* **We do not share or sell your personal information or email data with any third parties** for marketing or advertising purposes.
* Your OAuth tokens and vendor master file are stored locally and securely using the `chrome.storage` API.
* Data sent to our backend (as described above) is transmitted securely over HTTPS and stored in a private, access-controlled database.

## Analytics

We use Google Analytics to collect anonymized data about how you interact with the Service. This includes events like "extension installed," "invoice scanned," or "match found." We **do not** send any part of your email content, attachment data, or personal information to Google Analytics. This data is used only to help us understand extension usage and improve performance. You may opt-out of this data collection by disabling or uninstalling the extension.

## Limited Use Policy

Aptosi Invoice Agent's use and transfer of information received from Google APIs will adhere to the **Google API Services User Data Policy**, including the **Limited Use requirements**.

Information received from Google APIs (such as your email content) is:
* Only used to provide or improve the user-facing features of the extension (i.e., scanning for invoice data and applying organizational labels).
* Not transferred to others unless necessary to provide or improve these features, comply with applicable laws, or as part of a merger/acquisition.
* Not used for serving advertisements.
* Not read by humans, unless we have your affirmative agreement for specific messages, it is necessary for security purposes (like investigating abuse), to comply with applicable laws, or for internal operations (and even then, the data will be aggregated and anonymized).

## Changes to This Policy

We may update this Policy from time to time. We will notify you of any changes by posting the new Policy on this page.

## Contact Us

If you have any questions about this Privacy Policy, please contact us at [Your Support Email Address].
