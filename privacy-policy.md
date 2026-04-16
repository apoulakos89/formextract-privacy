# FormExtract — Privacy Policy

**Last updated:** 2026-04-16

## 1. Who we are

FormExtract ("the App", "we", "us") is operated by **Angelos Poulakos**
(sole developer), based in **Athens, Greece**. You can contact us at
**apoulakos89@gmail.com**.

## 2. What this policy covers

This policy explains what personal data the FormExtract mobile app collects,
why, where it goes, and what rights you have over it. It applies to the
Android app distributed via Google Play and any web build listed on the
same store page.

## 3. Data we collect

| Category | Examples | Source | Purpose |
|---|---|---|---|
| **Account data** | Email address, display name, profile photo URL | You (sign-up) or your Google / Apple sign-in | Authentication, identifying you to collaborators |
| **Project data** | Project names, field definitions, member lists | You | Core app functionality |
| **Document content** | Files you upload (PDFs, images), extracted text, structured field values | You | AI extraction and storage so you can review it |
| **Chat & collaboration data** | Messages, typing indicators, online presence | You and other project members | In-app collaboration |
| **Device & diagnostic data** | App version, OS version, anonymous device identifier, crash stack traces | Automatic | Stability monitoring (Firebase Crashlytics) |
| **Authentication tokens** | Firebase ID tokens, refresh tokens | Firebase Auth | Keeping you signed in |
| **Biometric secrets** | Local biometric hash (fingerprint/face) | Your device's secure enclave | Optional in-app lock — never leaves the device |

We **do not** collect: precise location, contacts, advertising identifiers,
microphone audio, or call data.

## 4. Where your data goes

### 4.1 Firebase (Google LLC)
We use Firebase as our backend:
- **Firebase Authentication** — stores your email, hashed password, and
  social-login linkage.
- **Cloud Firestore** — stores projects, fields, records, chat messages and
  member lists. Located in **europe-west1 (Belgium)**.
- **Firebase Crashlytics** — receives crash reports (no personally identifying
  data attached by us).
- **Firebase App Check** — verifies that requests come from a genuine,
  unmodified install of the app.

Google's privacy practices: https://policies.google.com/privacy

### 4.2 Anthropic (Anthropic, PBC)
When you upload a document for extraction, the file content (image or PDF) and
the structured prompt we build are sent to **Anthropic's Claude API** for
analysis. Anthropic processes the content solely to return the extracted
fields back to us; per Anthropic's API terms they do not use API content to
train their models.

Anthropic's privacy policy: https://www.anthropic.com/legal/privacy

### 4.3 OpenAI (OpenAI OpCo, LLC) — in-app support chat
If you use the in-app AI support chat to ask questions about the app, the
messages you type are sent to **OpenAI's Chat Completions API** to generate
a reply. OpenAI processes these messages only to return the response; per
OpenAI's API terms they do not use API content to train their models.

OpenAI's privacy policy: https://openai.com/policies/privacy-policy

### 4.4 No advertising or analytics SDKs
We do not embed third-party advertising networks, marketing trackers, or
behavioural analytics SDKs.

## 5. Legal basis (GDPR)

For users in the EEA / UK we rely on:
- **Performance of a contract** (Art. 6(1)(b)) — to operate the app you signed
  up for: account, projects, document processing.
- **Legitimate interest** (Art. 6(1)(f)) — crash reports and abuse prevention
  (App Check).
- **Consent** (Art. 6(1)(a)) — for any optional feature explicitly opted into.

## 6. How long we keep data

| Data | Retention |
|---|---|
| Account data | Until you delete your account |
| Project / document data | Until you delete the project, or your account |
| Crash reports | 90 days (Firebase Crashlytics default) |
| Authentication tokens | Refreshed regularly; revoked on logout |

If you delete your account we erase your account record and all projects you
own within 30 days. Projects where you are only a member remain owned by their
creator; you are removed from them.

## 7. Data sharing

We do not sell your data. We share it only with:
- Service providers above (Google, Anthropic, OpenAI) under contracts that
  require them to protect it.
- Other members of projects you join (they see project content you upload).
- Authorities, when legally compelled by valid court order.

## 8. Your rights

Under GDPR / CCPA / similar laws you may:
- Access the personal data we hold about you
- Correct inaccurate data
- Delete your account and associated data (in-app: Settings → Security →
  Delete Account)
- Export your data (in-app: Settings → Security → Delete Account → Step 1)
- Object to or restrict processing
- Lodge a complaint with your local supervisory authority (in Greece: the
  Hellenic Data Protection Authority, https://www.dpa.gr/)

To exercise these rights, email **apoulakos89@gmail.com**. We respond within
30 days.

## 9. Children

FormExtract is not intended for children under 16. We do not knowingly collect
personal data from children. If you believe a child has used the app, contact
us and we will delete the account.

## 10. Security

- All traffic between the app and Firebase / our proxy is TLS-encrypted.
- Firestore access is gated by per-project membership rules.
- Optional biometric lock at the OS level.
- Sensitive credentials (API keys) are stored server-side — they are **not**
  embedded in the app.

No system is ever 100% secure. Report suspected vulnerabilities to
**apoulakos89@gmail.com** with subject line "Security".

## 11. International transfers

Data may be processed in regions outside your country (e.g. Anthropic and
OpenAI in the United States). Where required, we rely on Standard Contractual
Clauses or equivalent safeguards.

## 12. Changes to this policy

We will update this page when we change how we process data and notify you
in-app or by email for material changes.

## 13. Contact

**Angelos Poulakos**
Athens, Greece
Postal address available upon written request to the contact email below.
**apoulakos89@gmail.com**
