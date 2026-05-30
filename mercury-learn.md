# PRIVACY POLICY & TERMS OF SERVICE

**App:** MercuryLearn  
**Publisher:** Mercury Labs Studio  
**Package:** com.mercurylearn.app  
**Effective Date:** May 10, 2026  

---

## 🇺🇸 ENGLISH

This document outlines how **MercuryLearn** ("the App", "we", "us") handles your data and the rules governing your use of our services. By using MercuryLearn, you agree to the practices and terms described herein.

---

### I. PRIVACY POLICY

#### 1. Introduction
At **MercuryLearn**, we are committed to protecting your personal information and your right to privacy. This policy applies to all information collected through our mobile application and related services.

#### 2. Detailed Data Collection
We collect information that you provide directly to us, as well as information generated through your use of the App.

**A. Personal Information:**
*   **Account Data:** If you register, we collect your email address, display name, and authentication identifiers provided by Google or Apple.
*   **Profile Data:** Optional information such as a profile picture or bio that you choose to upload.

**B. Learning & AI Data (Core Service):**
*   **Uploaded Documents:** Files (PDF, Word, TXT) and images containing text that you submit for analysis.
*   **AI Metadata:** Content extracted from your documents, including summaries, key concepts, and generated quiz questions.
*   **Learning Progress:** Your interaction with micro-lessons, quiz accuracy, Spaced Repetition (SM-2) history, and daily study streaks.

**C. Usage & Technical Data:**
*   **Device Identifiers:** Unique ID for your mobile device (UUID), operating system type and version.
*   **Log Data:** Access times, app crashes (via Firebase Crashlytics), and interaction logs.
*   **Environment Data:** Language settings, timezone (used solely for auto-localization), and IP address (anonymized).

**D. In-App Purchases:**
*   **Purchase Validation:** Handled by **RevenueCat** using encrypted receipt tokens only. 
*   **Secure Processing:** All financial transactions are processed securely by the **Apple App Store** (iOS) or **Google Play Store** (Android).
*   **No Sensitive Data Storage:** We do **not** store credit card numbers, banking information, or any other sensitive financial data. Our App only receives anonymized transaction IDs and entitlement status from the App Stores.

#### 3. How We Use Your Information (Legal Basis)
We process your data under the following legal grounds:
*   **Performance of a Contract:** To provide the AI document chunking and learning services you requested.
*   **Legitimate Interests:** To improve App performance, fix bugs, and ensure system security.
*   **Consent:** For sending push notifications and processing sensitive study materials.

#### 4. The "AI Agent" (Gemini 2.0 Flash)
*   **Processing:** Documents are processed by the Google Gemini API. This is necessary to convert raw text into structured lessons.
*   **Non-Training Guarantee:** We utilize professional enterprise API tiers. Google does **not** use the data processed through these APIs to train its public foundation models.
*   **Anonymization:** Wherever possible, we strip direct identifiers before sending document fragments for AI analysis.

#### 5. Data Retention & Deletion
*   **Active Data:** We retain your learning progress as long as your account is active.
*   **Inactivity:** Accounts inactive for more than 24 months may be flagged for deletion.
*   **User-Initiated Deletion:** You can delete specific documents or your entire account at any time within the App. Upon request, all associated data in Firestore and Firebase Storage is purged within 30 days.
*   **Backups:** Encrypted backups may persist for up to 60 days before being permanently overwritten.

#### 6. International Data Transfers
MercuryLearn is powered by **Google Firebase**. Your data is stored on servers located primarily in the United States and the European Union (depending on your region). By using the App, you consent to the transfer of information to these locations, which may have different data protection laws than your home country.

#### 7. Security Measures
*   **Tenant Isolation:** We use a Multi-Tenant architecture where your data is logically separated from other users' data at the database level.
*   **Encryption:** All data transfers use HTTPS (SSL/TLS). Databases are encrypted at rest.
*   **Access Control:** We implement strict Firebase Security Rules to ensure only you (or our authorized admins for support) can access your learning content.

#### 8. Cookies & Local Storage
We do not use traditional browser cookies. Instead, we use:
*   **MMKV/AsyncStorage:** To store your login session, UI preferences, and offline learning progress locally on your device.

#### 9. Advertising
**MercuryLearn contains zero advertisements.** We do not use AdMob, Unity Ads, or any other advertising network. The app is completely ad-free for all users, including those on the Free tier. We believe your focus should remain entirely on learning without distractions.

#### 10. Third-Party Sharing
We **never** sell your data. We only disclose data to:
*   **Service Providers:** Google (Firebase/Gemini), RevenueCat (Payments), and Sentry/Crashlytics (Error monitoring).
*   **Legal Compliance:** If required by law, subpoena, or to protect the safety of our users.

#### 11. Your Rights (GDPR/CCPA/PDPA)
Depending on your jurisdiction, you have the right to:
*   **Access:** Request a copy of your personal data.
*   **Rectify:** Correct inaccurate information.
*   **Object:** Oppose the processing of your data for specific purposes.
*   **Data Portability:** Receive your data in a structured, machine-readable format.

To exercise these rights, email: **teams.hi@icloud.com**

#### 12. Children's Privacy
We do not knowingly collect or solicit personal information from anyone under the age of 13. If we learn that we have collected personal information from a child without parental consent, we will delete that information as quickly as possible.

---

### II. TERMS OF SERVICE

#### 1. Subscription & Token Terms
MercuryLearn operates on a Freemium model with a Token-based credit system.
*   **Plans:** We offer Starter, Pro, and Pro Max tiers. These grant a monthly quota of "AI Tokens."
*   **Tokens:** Tokens are consumed when the AI Agent processes new documents. Unused tokens reset at the end of each billing cycle.
*   **Billing:** Payments are handled via the **Apple App Store** or **Google Play Store**. Subscriptions renew automatically unless canceled 24 hours prior to the period end.
*   **Refunds:** Refund requests must be directed to the respective App Store. We follow their standard refund policies.

#### 2. User-Uploaded Content
*   **Ownership:** You retain 100% ownership of the documents you upload.
*   **License:** You grant MercuryLearn a limited, non-exclusive license to host, parse, and display your content *only to you* for learning purposes.
*   **Responsibility:** You represent that you have the legal right to upload and process the documents provided. You may not upload content that is illegal, infringes on copyrights, or contains malware.

#### 3. AI Disclaimer & Accuracy
The content provided by the AI Agent (Micro-lessons, Summaries, Quizzes) is generated automatically.
*   **No Guarantee:** We strive for high quality, but we do not guarantee the 100% accuracy, completeness, or reliability of AI-generated content.
*   **Reference Only:** MercuryLearn is a study aid. It should not be used as the sole source for critical certifications, medical advice, or legal information without verifying against original sources.

#### 4. Prohibited Conduct
You agree not to:
*   Bypass or attempt to exploit the Token system.
*   Use automated scripts or "bots" to scrape content from the App.
*   Reverse engineer or decompile the App's native code.
*   Use the App to distribute harmful or offensive materials.

#### 5. Limitation of Liability
Mercury Labs Studio is not responsible for:
*   Data loss resulting from device failure, unauthorized modification (rooting/jailbreaking), or OS updates.
*   Temporary unavailability of Firebase services or third-party AI APIs affecting app functionality.
*   Loss of app progress if the app is uninstalled.
*   Direct or indirect damages resulting from your use of the App.
*   The accuracy or reliability of AI-generated summaries and quizzes.

#### 6. Governing Law
These terms are governed by the laws of the jurisdiction where Mercury Labs Studio is registered. Any disputes will be handled through good-faith negotiation before legal escalation.

---

### CONTACT US
For data requests, support, or legal inquiries:  
📧 **teams.hi@icloud.com**  

