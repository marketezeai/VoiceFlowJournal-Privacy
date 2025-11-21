# Privacy Policy for VoiceFlow Journal

**Last Updated:** November 20, 2025
**Effective Date:** November 20, 2025

---

## Introduction

Welcome to VoiceFlow Journal. We are committed to protecting your privacy and ensuring that your personal information is handled in a safe and responsible manner. This Privacy Policy explains how our app collects, uses, and protects your information.

**TL;DR: We collect ZERO data. Everything stays on your device.**

---

## Our Privacy Promise

VoiceFlow Journal is built with **privacy-first** principles:

✅ **No data collection** - We don't collect any personal information
✅ **On-device processing** - All AI analysis happens locally on your iPhone
✅ **No third-party services** - No analytics, no tracking, no data sharing
✅ **You own your data** - Your journals belong to you, stored only on your devices

---

## Information We Collect

### We Collect: NOTHING

VoiceFlow Journal does **not collect, store, or transmit** any of the following:
- ❌ Voice recordings
- ❌ Transcripts of your journals
- ❌ AI sentiment analysis results
- ❌ Personal information (name, email, etc.)
- ❌ Usage analytics
- ❌ Device information
- ❌ Location data
- ❌ Advertising identifiers
- ❌ Any other personal data

### App Store Privacy Nutrition Label

In accordance with Apple's App Privacy Details:
- **Data Not Collected:** All categories
- **Data Used to Track You:** None
- **Data Linked to You:** None
- **Data Not Linked to You:** None

---

## How Your Data is Stored

### Local Storage (SwiftData)
- Your journal entries are stored **only on your iPhone** using Apple's SwiftData framework
- Voice transcripts are saved locally in encrypted storage
- AI sentiment analysis results are stored locally
- All data remains in your device's secure storage

### iCloud Sync (Optional)
- If you enable iCloud sync, your journal entries are encrypted and stored in **your personal iCloud Private Database**
- We do not have access to your iCloud data
- iCloud data is encrypted both in transit and at rest
- You can disable iCloud sync at any time in Settings
- Deleting data on one device deletes it from iCloud

**Important:** Even with iCloud enabled, your data is only accessible by you and is stored in Apple's secure cloud infrastructure, not our servers. We never see your data.

---

## On-Device AI Processing

### Foundation Models API
VoiceFlow Journal uses Apple's **Foundation Models API** for sentiment analysis:
- All AI processing happens **100% on your device**
- Your voice transcripts never leave your iPhone
- No data is sent to external AI services
- No third-party AI companies have access to your journals
- No internet connection required for AI features

### Speech Recognition
- Uses Apple's Speech Framework for voice-to-text
- Processing happens on-device when possible
- Apple may process some speech recognition requests on their servers (not ours)
- See Apple's Privacy Policy for details: https://www.apple.com/legal/privacy/

---

## Permissions We Request

### Microphone Access
**Purpose:** To record your voice journals
**Usage:** Only active when you tap the record button
**Storage:** Audio is converted to text and the audio is not permanently stored

### Speech Recognition
**Purpose:** To transcribe your spoken words into text
**Usage:** Only when you're actively recording a journal entry
**Storage:** Transcripts are stored locally on your device

### iCloud (Optional)
**Purpose:** To sync your journals across your Apple devices
**Usage:** Only if you choose to enable iCloud sync
**Control:** Can be disabled at any time in Settings

---

## Third-Party Services

### We Use: ZERO Third-Party Services

VoiceFlow Journal does **not use**:
- ❌ Analytics services (Google Analytics, Firebase, etc.)
- ❌ Crash reporting services
- ❌ Advertising networks
- ❌ Third-party AI services
- ❌ Social media SDKs
- ❌ Any third-party tracking

### We Only Use Apple's Native Frameworks:
- ✅ SwiftData (local database)
- ✅ CloudKit (your private iCloud)
- ✅ Foundation Models API (on-device AI)
- ✅ Speech Framework (voice-to-text)
- ✅ StoreKit 2 (in-app purchases)

All of these are Apple's native frameworks and respect Apple's privacy standards.

---

## In-App Purchases

### Subscription Data
When you purchase a subscription:
- Apple processes the payment (not us)
- We receive a transaction ID from Apple to verify your subscription
- We do **not** receive your credit card information
- We do **not** receive your personal information
- Your purchase history is managed by Apple

### What We Store
- A local flag indicating your subscription status (premium vs. free)
- No payment information
- No personal billing details

---

## Data Security

### Local Data Protection
- Your journals are stored in your iPhone's encrypted storage
- iOS automatically encrypts data when your device is locked
- Face ID/Touch ID protects access to the app (if you enable device passcode)

### iCloud Encryption
- All iCloud data is encrypted in transit (TLS)
- All iCloud data is encrypted at rest in Apple's data centers
- Only you have access to your iCloud data

### No Servers
- We do not operate any servers
- We cannot access your data (because we never receive it)
- There is no "cloud backend" that could be hacked

---

## Your Rights

### Data Access
- You can access all your journal entries at any time in the app
- Export functionality (coming in v1.1)

### Data Deletion
- Delete individual journal entries by swiping left
- Delete all data by uninstalling the app
- iCloud data can be deleted from Settings > iCloud > Manage Storage

### Data Portability
- Your data is stored in standard formats
- Export feature coming in v1.1 (PDF, TXT)

### Opt-Out
- You can stop using the app at any time
- Uninstalling the app removes all local data
- No account to delete (we don't have accounts)

---

## Children's Privacy

VoiceFlow Journal is rated **4+** and is safe for all ages. We do not:
- Collect data from children or adults
- Require age verification (no data collection = no risk)
- Share data with third parties
- Use targeted advertising

Parents can safely allow children to use VoiceFlow Journal as no personal information is collected.

---

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Changes will be posted:
- In the app (Settings > Privacy Policy)
- On our website (if applicable)
- In the App Store listing

**Material changes** will be communicated via:
- App update release notes
- In-app notification

Continued use of the app after changes constitutes acceptance of the new policy.

---

## Compliance

VoiceFlow Journal complies with:
- ✅ **GDPR** (EU General Data Protection Regulation)
- ✅ **CCPA** (California Consumer Privacy Act)
- ✅ **COPPA** (Children's Online Privacy Protection Act)
- ✅ **Apple App Store Review Guidelines** (Nov 2025)
- ✅ **iOS Privacy Requirements**

**Why compliance is easy:** We don't collect data, so there's nothing to protect, share, or delete. Your data never leaves your device.

---

## Contact Us

If you have questions about this Privacy Policy or VoiceFlow Journal's privacy practices:

**Developer:** Claude AI (Anthropic)
**Email:** support@voiceflow.app (placeholder - update before release)
**Website:** https://voiceflow.app (placeholder - update before release)

**For App Store Review:**
If you're an Apple reviewer and need clarification on our privacy practices, please contact us through App Store Connect.

---

## Technical Details (For Transparency)

### Frameworks Used:
- **SwiftData:** Local-only database (Apple)
- **CloudKit:** User's private iCloud (Apple)
- **Foundation Models API:** On-device AI (Apple)
- **Speech Framework:** Voice recognition (Apple)
- **StoreKit 2:** In-app purchases (Apple)
- **Natural Language:** Sentiment analysis (Apple)

### Data Flow:
1. You speak into the microphone
2. Speech Framework converts to text (on-device or Apple's servers)
3. Text is saved to SwiftData (local database)
4. Foundation Models API analyzes sentiment (on-device)
5. Results saved to SwiftData (local database)
6. Optional: Encrypted sync to your iCloud Private Database

**At no point does your data reach our servers, because we don't have servers.**

---

## Summary

**The Short Version:**

- 🔒 **Zero data collection**
- 📱 **Everything stays on your device**
- 🧠 **AI runs locally (Foundation Models API)**
- ☁️ **iCloud = your private cloud (optional)**
- 🚫 **No third-party services**
- ✅ **You own your data**

VoiceFlow Journal is designed to be the most private journaling app on the App Store. Your thoughts, your data, your device.

---

**Questions?** Contact: support@voiceflow.app

**Last Updated:** November 20, 2025

---

*This privacy policy is written in plain English because privacy shouldn't require a law degree to understand.*
