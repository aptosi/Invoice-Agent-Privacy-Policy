# Invoice Agent privacy policy 

Privacy Policy for Aptosi Invoice Agent

Document Creation Date: July 1, 2025

Last Updated: October 14, 2025

Thank you for choosing the Aptosi Invoice Agent ("the Agent"). This Privacy Policy is designed to help you understand how we collect, use, and safeguard the information you provide when using our Chrome Browser Extension Agent. Your privacy is important to us, and we are committed to protecting it.

This policy specifically covers the Aptosi Invoice Agent and may differ from the privacy policy for our main website or other services.

Our Commitment to Your Privacy

The Aptosi Invoice Agent is designed with your privacy and security as a top priority. Our goal is to provide intelligent invoice verification with minimal data collection necessary to perform our service. We only access your data to provide and improve the service, and we do not sell your personal information to third parties.

What Information We Collect and Why

To provide our services, we need to access certain data from your Google account and your browser. We believe in transparency, so we have detailed what we collect and why in the table below.

```
+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+
| Data We Collect                                    | How We Collect It                                  | Why We Collect It (Purpose)                        | How We Use It                                      |
+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+
| Google User Information                            | When you authenticate the extension with your      | To identify you as a user, create your Aptosi      | We use this information to display your user       |
| (e.g., name, email address, profile picture)       | Google account via OAuth.                          | account, and associate your account with your      | profile within the extension and to securely       |
|                                                    |                                                    | Gmail data.                                        | link your account to the data we process.          |
+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+
| Gmail Data & Permissions                           | By requesting permissions to your Gmail account,   | Core Functionality: To find, read, and analyze     | We read email content to extract key invoice       |
| - Email content (headers, subjects, body,          | which you must grant. The extension automatically  | emails and attachments that are likely invoices.   | details (e.g., vendor name, invoice amount,        |
|   attachments)                                     | scans your inbox for emails identified as          |                                                    | due date, bank details). Metadata is used to       |
| - Email metadata (message IDs, thread IDs)         | invoices.                                          |                                                    | track processed emails and apply status labels.    |
+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+
| Gmail Label & Send Permissions                     | By requesting permissions to your Gmail account,   | To organize your invoices and allow you to take    | We use these permissions to create and apply       |
| (`gmail.labels`, `gmail.modify`, `gmail.send`)     | which you must grant.                              | action on them.                                    | labels (e.g., "Aptosi/Match", "Aptosi/Mismatch")   |
|                                                    |                                                    |                                                    | to your emails. The `gmail.send` permission is     |
|                                                    |                                                    |                                                    | used solely to allow you to forward processed      |
|                                                    |                                                    |                                                    | invoices or related data from within the extension.|
|                                                    |                                                    |                                                    | **We never send emails without your direct action.**|
+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+
| Extracted Invoice & Vendor Data                    | Automatically, by scanning the content of emails   | To verify invoice details against your list of     | This extracted data is compared against your       |
| (e.g., payment details, amounts, dates, vendor     | and attachments identified as invoices.            | approved vendors.                                  | vendor records to determine a "Match" or           |
| names)                                             |                                                    |                                                    | "Mismatch" status. This information is then        |
|                                                    |                                                    |                                                    | stored in our secure database (Firebase) to keep   |
|                                                    |                                                    |                                                    | a record of the verification.                      |
+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+
| Anonymous Usage & Analytics Data                   | Through integration with Google Analytics 4.       | To understand how users interact with the          | This data is aggregated and anonymized. We use     |
| (e.g., feature usage, button clicks, performance   |                                                    | extension, identify bugs, and improve our product. | it to make data-driven decisions about new         |
| metrics, IP address, browser type)                 |                                                    |                                                    | features, performance improvements, and user       |
|                                                    |                                                    |                                                    | experience enhancements.                           |
+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+
| Local Extension Data & Settings                    | Through the `chrome.storage` API, which stores     | To store your settings and cache data for faster   | We store verification results locally to instantly |
| (e.g., user preferences, cached results)           | data locally in your browser.                      | performance and to reduce redundant processing.    | display status badges when you view your inbox,    |
|                                                    |                                                    |                                                    | improving the user experience and minimizing API   |
|                                                    |                                                    |                                                    | calls.                                             |
+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+
```

Third-Party Services

We utilize the following third-party services to provide the functionality of the Agent:

** Google APIs (Gmail & OAuth): We use Google's APIs to authenticate you and access your Gmail data based on the permissions you grant. All data accessed via these APIs is handled in accordance with the Google API Services User Data Policy, including the Limited Use requirements. [https://developers.google.com/terms/api-services-user-data-policy]

** Firebase (by Google): We use Firebase for secure user authentication and as a cloud database (Firestore) to store information about processed invoices. You can learn more in the Firebase Privacy and Security documentation. [https://firebase.google.com/support/privacy]

**Google Analytics: We use Google Analytics to collect anonymous usage statistics to help us improve the Agent. For more information, please review Google's Privacy Policy. [https://policies.google.com/privacy]

Data Security

We implement a variety of security measures to maintain the safety of your personal information. Your data is transmitted over secure SSL channels, and our database is protected by Firebase security rules. We do not store your Google password. Access to your data is strictly limited to the permissions you grant.

Data Retention

We retain the data we collect for as long as necessary to provide the service and for legitimate business purposes. Anonymized usage data may be kept indefinitely for statistical analysis. You can request the deletion of your account and associated data by contacting us.

Your Rights and Choices

You can revoke the Agent's access to your Google Account at any time through your Google Account security settings. [https://myaccount.google.com/permissions] If you do so, the Agent will no longer be able to access your Gmail data. You can also uninstall the Agent from your browser at any time.

Changes to This Privacy Policy

We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Last Updated" date. By using the Aptosi Invoice Agent, you agree to the terms of this privacy policy.

Contact Us:

If you have any questions about this privacy policy, please contact us through dev@aptosi.com 

