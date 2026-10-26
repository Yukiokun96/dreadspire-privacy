# Privacy Policy for Dreadspire

**Last updated: October 26, 2026**

Dreadspire is an Android game published by **SheetBound Studio**. This policy describes the current Android release, including advertising and in-app purchases. For privacy questions or requests, contact **playstore.lystochok@gmail.com**.

**Account/data deletion:** [Request deletion of your Dreadspire account and associated data](#6-retention-and-deletion-requests). You can submit a request without reinstalling the game.

## 1. Gameplay data stored on your device

Progress, heroes, upgrades, achievements, currency balances, settings, checkpoints and purchase-entitlement flags are saved locally. Dreadspire does not back up or restore the full saved game through a cloud-save service. Optional Google Play Games sign-in can link a Firebase account to synchronise used promo-code history, as described below; it does not upload your saved game or wallet balances.

Clearing the app's storage removes local progress. Eligible non-consumable purchases can be checked through Google Play using the in-game Restore button; this does not restore all gameplay progress.

## 2. Advertising and technical information

The game integrates **Google AdMob (Google Mobile Ads SDK)** and **Google User Messaging Platform (UMP)**. These services may process IP addresses (including approximate location derived from them), advertising and other device identifiers, app/ad interactions and technical diagnostics. Google uses this information to provide and measure advertising, analyse service performance and prevent fraud.

The game also integrates **Unity In-App Purchasing 5.4** for store connectivity and purchase delivery. It may process installation/session identifiers, device and SDK diagnostics, country information and transaction information. The build sets Unity's developer-data advertising and analytics consent states to denied; this does not mean that all technical data needed by the services is disabled. Dreadspire does not integrate a separate Firebase Analytics or Firebase Crashlytics service.

Provider information:
- [Google Privacy Policy](https://policies.google.com/privacy)
- [How Google uses information from partner apps](https://policies.google.com/technologies/partner-sites)
- [Google Mobile Ads data disclosures](https://developers.google.com/admob/android/privacy/play-data-disclosure)
- [Unity Privacy Policy](https://unity.com/legal/privacy-policy)
- [Unity IAP privacy information](https://docs.unity.com/en-us/iap/privacy-and-consent/overview)

## 2.1 Google Play Games

Google Play Games provides platform authentication, achievements and the campaign leaderboard. When connected, Dreadspire uses the player display name for the connection status and sends achievement progress and completed-stage scores to Google. Native achievement and leaderboard views are provided by Google. Google processes Play Games profile and service information under its policies.

## 2.2 Promo codes and Firebase

Redeeming and synchronising promo-code history requires optional Play Games sign-in. Dreadspire requests a Play Games server authentication code and exchanges it through **Firebase Authentication**, which creates or identifies an account linked to your Play Games identity and assigns a Firebase account identifier (UID). This lets the same player retrieve their used-code history after reinstalling or changing devices. You can play without using promo-code synchronisation.

**Firebase Realtime Database** stores redemption records under that account identifier: a hashed promo code, the reward amounts and catalog version, a randomly generated installation identifier and a server-generated redemption timestamp. The installation identifier distinguishes the installation that claimed a reward. We use these records to deliver promo rewards, recover interrupted claims on the same installation, display used-code history and prevent repeated redemption by the same account. This database does not store your complete game save or current currency balances. Reinstalling does not grant historical promo rewards again or restore your previous wallet.

The game keeps authentication tokens in memory rather than writing them to the local save. Requests to Firebase use HTTPS. Database access rules restrict each player's redemption history to their authenticated Play Games-linked account; support administrators may access records to operate the service and handle requests. Firebase also processes authentication and technical service information, which may include linked provider information, IP addresses and user-agent information, as described in [Firebase's privacy information](https://firebase.google.com/support/privacy). Firebase Authentication and Realtime Database are used without Firebase Analytics or Firebase Crashlytics.

## 3. Purchases

Payments are handled by **Google Play Billing** through Unity IAP. The game uses purchase status, product and transaction information to deliver and restore purchased content. We do not receive your full payment-card details. Store transaction records and refund handling remain subject to Google's policies. No Dreadspire subscription is offered in the current release.

## 4. Advertising choices

Rewarded advertisements are optional. Interstitial advertisements may occasionally appear after completing a campaign stage; the Remove Ads purchase disables forced interstitials, while optional rewarded offers remain.

UMP checks consent requirements when the game starts. Where required by the provider, a privacy form is presented before advertising requests. You can revisit applicable choices through **Shop > Privacy Choices** when that option is available in your region. Android also provides controls for advertising identifiers and ad privacy. Restricting personalised advertising does not necessarily stop all advertising or technical processing.

## 5. Use, sharing and security

Information is used for game/store functionality, purchase fulfilment, promo-code synchronisation, advertising, service analytics, troubleshooting and fraud prevention. Promo account and redemption records are processed through Google Firebase to provide the promo service. Advertising-related information is collected and shared by Google as described in its disclosures. We do not operate a business selling player contact lists or saved games.

The integrated services use encrypted network transport. No storage or transmission method can be guaranteed completely secure. Providers may process information in countries other than yours under their policies and applicable safeguards.

## 6. Retention and deletion requests

**To request deletion of your Dreadspire account and its associated promo history:**
1. Email **playstore.lystochok@gmail.com** with the subject **Dreadspire data deletion**.
2. Explain what you want deleted and whether your request concerns a promo account, promo history, a support conversation or a purchase. Include only information needed to locate the relevant record. We may ask you to verify control of the relevant account. Do not send passwords, authentication tokens, full card numbers or Google login credentials.
3. We will use the reply address to clarify and handle the request. Where information is processed on our behalf by a provider, we will route the verified request to that provider. Information controlled independently by Google or Unity may require a request directly to that provider.

Local saves remain until app storage is cleared or the relevant local data is otherwise removed. We cannot remotely erase a local save. Support correspondence is kept while needed to resolve the request and any related dispute or legal obligation, then deleted when no longer needed.

Firebase account and promo-redemption records remain available across installations while needed to operate the promo service and prevent duplicate claims. Use the contact procedure above to request access, correction or deletion of account-related data. We review verified requests and explain any retention needed for fraud prevention or legal obligations. The in-game request link opens these instructions; it does not automatically erase data. Clearing app storage does not delete server-side promo history.

We do not maintain a central database of full saved games or purchases. Provider-held advertising, diagnostic and transaction records follow the provider's retention rules. Certain transaction/security records may be retained where needed for fraud prevention, refunds or legal obligations. Deleting game data does not cancel, refund or erase Google Play's purchase records.

Depending on your location, you may also request access, correction or restriction of information under our control using the same contact address.

## 7. Age audience

Dreadspire is intended for people aged **13 and over**, consistent with its current Google Play target-audience declaration. It is not directed at children under 13. If you believe a child under 13 has provided personal information to us, contact us so we can investigate and address the information under our control. Local laws may provide additional protections for young users.

## 8. Changes and contact

We will publish updates on this page and change the revision date when our practices change.

**Game:** Dreadspire  
**Developer:** SheetBound Studio  
**Privacy and support:** playstore.lystochok@gmail.com
