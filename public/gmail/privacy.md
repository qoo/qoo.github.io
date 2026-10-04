---
title: Privacy Policy – Gmail Storage Cleaner
permalink: /public/gmail/privacy.html
---

<img src="logo.png" alt="Gmail Storage Cleaner logo" width="120" height="120">

# Privacy Policy

**Application:** Gmail Storage Cleaner
**Developer:** Cheng-Hung Yeh
**Contact:** [yehchenghung@gmail.com](mailto:yehchenghung@gmail.com)
**Last updated:** October 4, 2026

This Privacy Policy explains how Gmail Storage Cleaner ("the App", "we") accesses,
uses, stores, and shares Google user data. By using the App you agree to this policy.

## 1. Data we access

When you sign in with Google and grant permission, the App requests the following scopes:

| Scope | Why it is needed |
| :--- | :--- |
| `https://mail.google.com/` | To search your messages, read message metadata (sender, subject, date, size, labels), move messages to Trash, and permanently delete messages that you explicitly choose. |
| `https://www.googleapis.com/auth/spreadsheets` | To read Google Sheets spreadsheets that you point the App to, and to write values (for example, numbers into specific cells) **only when you ask it to**. |

For cleanup features, the App reads only the data needed to show you a preview of
matching emails (for example: sender, subject, date, and size). When you ask the App
to read a specific email or spreadsheet, it reads that content so it can show it to
you or act on it. The App does not browse your Drive and only opens spreadsheets you
specify by link or ID.

## 2. How we use the data

Google user data is used **only** to provide the App's user-facing features:

- Running the search filters you select;
- Displaying a preview of matching emails and their estimated storage size;
- Moving to Trash or permanently deleting emails **after you explicitly confirm**;
- Reading the content of emails or spreadsheets you ask about;
- Updating cells in a spreadsheet you specify, **only at your request**.

We do **not** use Google user data for advertising, marketing, profiling, credit
decisions, or any purpose unrelated to the features above.

## 3. Data storage

- The App runs locally on your own computer. There is no developer-operated server.
- Your OAuth access/refresh token is saved only on your computer (in a local
  `token.json` / `token_<name>.json` file, one per Google account) so you do not
  have to sign in every time. You can delete
  this file at any time.
- Email and spreadsheet data retrieved from Google APIs is held in memory while the App
  is running. Attachments are saved to your computer only if you ask the App to save them.
- The developer does not operate any server and does not receive or store your data.

## 4. Data sharing

We do **not** sell, rent, or trade Google user data, and we do not share it with any
third party for advertising or any purpose other than the user-facing features you request.

**Optional AI assistant.** If you choose to operate the App through an AI assistant that
you run yourself (for example, Anthropic's Claude), the specific email or spreadsheet
content involved in your request is sent to that AI provider so it can carry out the task
you asked for, under that provider's own terms and privacy policy. This happens only at
your direction. Otherwise, data is transmitted only between your computer and Google's
servers over HTTPS.

## 5. Use of AI / machine learning

Google user data obtained through Google Workspace APIs is **not** used to develop,
improve, or train generalized or non-personalized AI and/or machine-learning models.
When you use an optional AI assistant as described in Section 4, data is used only to
complete your request, not to train models.

## 6. Google API Services User Data Policy

The App's use and transfer of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

## 7. Security

- All communication with Google uses encrypted HTTPS connections.
- OAuth credentials are kept on your device and are never sent to the developer.
- Destructive actions (Trash / permanent delete) always require your confirmation.
- Spreadsheet changes are made only to the spreadsheet and cells you specify.

## 8. Your choices and data deletion

- **Revoke access:** You can remove the App's access at any time at
  [Google Account › Security › Third-party apps](https://myaccount.google.com/permissions).
- **Delete local data:** Delete the `token.json` / `token_<name>.json` files on your computer to remove the
  saved credentials.
- Because the developer stores no user data, there is nothing for us to delete on our
  side; if you have any request, contact us at the email above.

## 9. Children's privacy

The App is not directed at children under 13 and does not knowingly collect data from them.

## 10. Changes to this policy

We may update this policy from time to time. Changes will be posted on this page
with an updated "Last updated" date.

## 11. Contact

Questions about this policy: [yehchenghung@gmail.com](mailto:yehchenghung@gmail.com)

---

[← Back to Gmail Storage Cleaner](./)
