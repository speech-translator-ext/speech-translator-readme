# Privacy Policy

**Last Updated:** July 17, 2026

## Disclosures

The following disclosures are required by the Chrome Web Store User Data Policy:

- We use personal or sensitive user data such as personally identifiable information (name, email address), audio data, websites data, display devices data, Chrome language settings data, and metadata (including IP address, user agent, and login session data) to provide and improve our Product’s functionality.
- We collect some metadata to provide and improve our Product’s functionality.
- We always encrypt using HTTPS all data we transfer over the Internet.
- We may share audio data, transcribed text, User-generated Extension settings, account information, and some metadata with Google Chrome, Microsoft Edge, Google (including Google Cloud, Google Identity Platform, and Firestore), Cloudflare, Naver Papago, Bing Microsoft Translator, Stripe, Patreon, Boosty, and Mailjet for processing, authentication, subscription management, and email communications. You can find their privacy policies here:
  + [Google & Google Chrome](https://policies.google.com/privacy)
  + [Microsoft Edge & Bing](https://privacy.microsoft.com/privacystatement)
  + [Cloudflare](https://www.cloudflare.com/privacypolicy/)
  + [Google Cloud & Firebase](https://cloud.google.com/terms/cloud-privacy-notice)
  + [Stripe](https://stripe.com/privacy)
  + [Patreon](https://privacy.patreon.com/)
  + [Boosty](https://boosty.to/app/offer/privacy-policy)
  + [Mailjet](https://www.mailjet.com/legal/privacy-policy/)
- We may share **pseudonymized transcribed text** with the third-party translation services listed below when the corresponding service is explicitly selected. We share this data to enable the functionality of our Product, such as translation.
  + [Naver Papago](https://policy.naver.com/policy/privacy_en.html)
  + [Youdao](https://c.youdao.com/dict/law/youdao_dict_privacy.html)
  + [Sogou](https://fanyi.sogou.com/app/privacyPC)
- We may share **transcribed text and metadata** with the third-party translation services listed below when the corresponding service is explicitly selected and used. We share this data to enable the functionality of our Product, such as translation.
  + [Naver Papago](https://policy.naver.com/policy/privacy_en.html)
  + [DeepL](https://www.deepl.com/en/privacy)
  + [Yandex](https://yandex.com/legal/confidential/en/)
  + [VolcTrans](https://www.volcengine.com/docs/6256/64902)
- The use of information received from Google APIs will adhere to the [Chrome Web Store User Data Policy](https://developer.chrome.com/docs/webstore/program-policies/), including the [Limited Use](https://developer.chrome.com/docs/webstore/program-policies/limited-use/) requirements.

You can also find these disclosures in our privacy policy below.

## Privacy Policy

This privacy policy explains how Kappaflow, operating as an independent developer ("we", "us", or "our"), collects, uses, and shares your personal and sensitive data when you use the Speech Translator extension ("Product"). Please read this policy carefully before using our Product.

## What data do we handle?

We handle the following types of data when you use our Product:

- **Account & Consent Information**: An account can be created directly by you using your email, or it may be automatically provisioned when you purchase a premium feature or subscribe via Stripe, Patreon, or Boosty (using the email address provided during that transaction). In either case, we collect and store your name, email address, locale, and user/extension settings using Firestore. Your login credentials are securely managed by Google Identity Platform (Firebase Authentication). Additionally, we record your IP address and user agent when you accept our Privacy Policy and Terms of Service, when you opt-in to receive information about important updates and offers, and to manage your active login sessions. 
- **Payment and Subscription Data**: If you purchase a premium feature or subscription, your payment is securely processed by third-party providers (Stripe, Patreon, or Boosty). We do not collect or store your credit card numbers. Through API integrations, we only receive and store unique IDs from these payment systems and your subscription status to grant you access to paid features. *Note: Canceling a subscription simply reverts your account to a free tier; it does not automatically delete your account or account data.*
- **Audio data**: Depending on your browser, we use Google Chrome or Microsoft Edge internal features to capture audio from your input audio devices (such as your microphone), your desktop, or specific browser tabs. Please note that while the browser's system and tab capture APIs may request permission to access your screen or video, our Product explicitly ignores and discards all video data, extracting only the audio track. This audio is processed locally within your browser to transcribe it into text. We do not store your raw audio data, nor do we transmit raw audio files to our own servers.
- **Transcribed text**: We use this data to provide translation features. We do not save this data ourselves, but we use it locally in your browser and may share it with third parties for translation. Additionally, if you enable the "Streaming Mode" feature, your live transcribed and translated text is temporarily routed through our servers to be displayed on your unique streaming URL.
- **Webpage data**: We use the information on the opened webpages locally on your device to provide translation and extension appearance on the webpage.
- **Display devices data & Language settings data**: We use your display device and Browser language settings locally via the Browser extension API to adjust layout and determine preferred translation languages.
- **User-generated Extension settings**: We store your extension preferences securely on your device using Extension Local Storage. To sync them across your devices, we also store them in our Firestore database. We may also use and share (as metadata in requests) specific settings, such as API keys, with third parties to enable Product functionality.
- **Metadata**: We and third parties may collect metadata, such as your IP address, when communicating with external APIs to ensure the security and performance of our Product.

## How do we use your data?

We process your data based on the following legal bases:

**Performance of a Contract** (To provide you with the Product):
- To create and manage your user account, authenticate your email sign-in, and manage login sessions.
- To sync your profile and extension settings across devices.
- To verify your premium subscription status via payment system IDs.
- To provide you with the core functionality of our Product, such as speech transcription, language detection, and translation.
- To send essential transactional emails regarding your account, security, or subscription status via our email provider, Mailjet.

**Legitimate Interest** (To keep the Product safe and functional):
- To collect minimal metadata (such as IP addresses and user agents) to prevent fraud, ensure security, and fix bugs.
- To record your consent to our Terms of Service and Privacy Policy.
- To improve our Product and services, such as by enhancing features and developing new products.
- To comply with legal obligations.

**Consent** (When you actively opt-in):
- To communicate with you by sending promotional offers or updates about new features via Mailjet. You can withdraw your consent for promotional emails at any time.

## How do we share your data?

We share your data with the following third parties strictly for the purposes described above:

- **Authentication & Database Providers**: We use **Google Cloud (Google Identity Platform / Firebase Authentication and Firestore)** to securely authenticate your email sign-in and store your account data (Name, Email, Locale, IP address, user agent, login sessions, and extension settings). 
- **Payment Processors**: If you make a purchase, your actual payment data is handled directly by **Stripe**, **Patreon**, or **Boosty**. We share and receive necessary account identifiers with them via API to verify your subscription status.
- **Translation Services (User-Initiated Transfers)**: Only registered users have the ability to select third-party translation providers other than Google Translate. Depending on the service you explicitly select and use, the data shared differs:
  - We may share **pseudonymized transcribed text** with **Naver Papago, Youdao, and Sogou**.
  - We may share **transcribed text and metadata** directly with **Naver Papago, DeepL, Yandex, and VolcTrans**.

  By explicitly selecting these services, you direct our Product to send your data to that specific provider. You acknowledge that your data may be transferred internationally (including to the US, China, or Russia) and that the processing of your data—including whether it is retained for AI training purposes—is governed entirely by the respective privacy policies of those third-party providers.
- **Email Communications**: We use **Mailjet** to send necessary transactional emails (required for account management) and promotional emails (if you have opted in).
- **Public Viewers (Streaming Mode):** If you voluntarily enable the Streaming Mode feature, your live transcribed and translated text is broadcasted to a unique web URL. Anyone who possesses this link can read your transcribed text in real-time. We do not permanently store this broadcasted text, but it is processed through our servers (Google Cloud/Cloudflare) to deliver the stream to your viewers. You are entirely responsible for who you share this link with.
- **Infrastructure**: We use **Cloudflare** and **Google Cloud** to route data securely and improve performance.

We do not sell, rent, or trade your personal data to any third parties for their own marketing purposes.

## Educational Institutions and University Users (USA)

Our Product is used by students and staff at various educational institutions. If you access our Product through an agreement established between us and your school, university, or educational district—including agreements established through the **Student Data Privacy Consortium (SDPC)** — please note:
- We act as a "School Official" under the Family Educational Rights and Privacy Act (FERPA) with a legitimate educational interest.
- We comply with the terms of the **SDPC National Data Privacy Agreement (NDPA)** and applicable state-specific student privacy laws.
- We will not sell student personal data, nor will we use it for targeted advertising or to build student profiles for non-educational purposes.
- **Third-Party Integrations:** Our Product offers users the ability to explicitly select various third-party translation providers (such as DeepL, Yandex, etc.). When used under an educational agreement, it is the institution's responsibility to dictate, configure, or restrict which third-party translation services are authorized for their students to use. By selecting these third-party services, the institution or user authorizes the direct transfer of transcribed text to those providers, which are governed by their own respective privacy policies.
- If there is any conflict between this Privacy Policy and a specific Data Processing Agreement (DPA), SDPC agreement, or Terms of Service signed with your educational institution, the terms of the specific agreement with your institution will take precedence.

## Children's Privacy

Our Product is not intended for unsupervised use by children under the age of 13 (or 16 in the EU). We do not knowingly collect personal data directly from children. If you are an educational institution relying on our Product for students under this age, the institution is responsible for obtaining the necessary parental consent under COPPA or relevant local laws. If we become aware that we have collected such data without adequate consent, we will take steps to delete it immediately.

## How do we protect your data?

We take reasonable measures to protect your data from unauthorized access, use, or disclosure. We always encrypt all data transferred over the Internet using HTTPS. Your account and consent data stored in Firestore is protected by strict database security rules. We also limit access to your data to authorized personnel who need it to operate the Product.

## How long do we keep your data?

We keep your account data, synced settings, consent logs (IP and user agent), and subscription status for as long as your account is active. If you choose to delete your account, we will delete your personal data from our databases. Temporary data like transcribed text is processed in real-time and is not retained on our servers. 

## What are your rights?

Depending on your location (e.g., under GDPR or CCPA), you have the following rights regarding your data:
- **Access and Portability**: You can request a copy of the personal data we hold about you.
- **Correction**: You can update your account information and settings at any time through your profile.
- **Deletion**: You can request the full deletion of your account and associated personal data by sending us an email at *contact@kappaflow.dev*.
- **Withdraw Consent**: You can opt out of receiving promotional emails by using the unsubscribe link provided in the emails. (Note: You cannot opt out of essential transactional emails while your account is active). You can also uninstall the Product at any time, which stops all local data collection. 
- **Lodge a Complaint**: You have the right to lodge a complaint with your local data protection authority if you believe your data privacy rights have been violated.

To exercise any of these rights, please contact us by email.

## How do we update this policy?

We may update this policy from time to time to reflect changes in our practices or legal requirements. We will notify you of any material changes by posting a notice on our website, updating the Chrome Web Store / Edge Add-ons listing, or sending you an email. Your continued use of our Product after such notice constitutes your acceptance of the updated policy.

## How can you contact us?

If you have any questions or concerns about this policy, your data rights, or our handling of your data, or if you wish to delete your account, please contact us at *contact@kappaflow.dev*.
