# Nightingale — App Store Review Response Notes

Copy the relevant sections below into App Store Connect (App Review notes / reply to the rejection message). Fill in the placeholder marked **[FILL IN]** before submitting.

---

## 1. Screen Recording — Demo Script (record on a physical device, latest iOS)

Record one continuous video covering the full typical user flow. Follow this order:

1. **Launch** the app from the home screen (cold start — swipe the app out of the app switcher first so it isn't running).
2. **Welcome screen** → tap **"I'm new"** → complete **account registration** (email + password, then the verification code step).
3. **Home dashboard** — swipe through the tabs: Focus (tasks), Heal, Restore, Reflect.
4. **Tasks:** add a task, tap it to mark it complete.
5. **Heal tab:** log a medication as taken; log a symptom with severity; log pain level.
6. **Restore tab:** log a glass of water; open the Daily Log and add a vitals reading (temperature, heart rate, blood pressure, oxygen).
7. **Daily Log page:** tap **"Share with provider (PDF)"** and show the generated PDF (share sheet is fine).
8. **User-generated content:** create a journal entry (private by default), and send a care-team invite or share a routine link (shows UGC creation and the app's sharing controls).
9. **Account deletion:** Settings → **Delete account** → show the confirmation dialog. You may cancel at the confirmation step — Apple just needs to see the flow exists.
10. **Logout** from Settings.

Recording tips:
- Use a physical iPhone on the latest iOS.
- Record via a second device or QuickTime on Mac (Settings → Control Center → Screen Recording adds on-device recording, but a clean external capture looks better).
- Keep it under ~5 minutes; move slowly enough for reviewers to read each screen.
- If anything loads slowly, pause rather than narrate over it.

---

## 2. App Purpose and Target Audience (paste into review notes)

Nightingale is a supportive care companion for people going through breast cancer treatment and recovery, and for the family members and friends helping them. It addresses a real gap: recovery involves managing many moving parts — medication schedules, chemo side effects, pain and symptom patterns, hydration, gentle movement, and emotional processing — and patients are often too exhausted to track any of it in one place, let alone summarize it for their care team at appointments.

Nightingale solves this with a single, gentle interface that:

- Organizes daily tasks around the user's energy level, so users can still feel productive on hard days.
- Tracks medications taken, symptoms, pain, and vitals, and turns them into a clean, provider-ready daily PDF report to share with doctors.
- Coaches hydration, including electrolyte reminders on chemo days.
- Guides gentle, rehab-safe movement and stretching with step-by-step instructions.
- Provides reflective journaling and calming exercises for emotional wellbeing.
- Coordinates care: patients can invite caregivers to share and complete tasks on their behalf, with attribution.

The value: patients and caregivers spend less energy on logistics, feel more in control, and walk into appointments with accurate records instead of recollection.

Target audience: adults (18+) in active breast cancer treatment or recovery, and their informal caregivers. Not intended for children. The app contains no public social feed and no third-party social media sharing; journal entries are private by default, and shared routines are only shared by link with people the user chooses.

---

## 3. Setup Instructions and Demo Access (paste into review notes)

The app requires no special setup, sample files, or configuration.

**Demo account credentials:**

> Email: **mynightingalecares@gmail.com**
> Password: **[FILL IN — enter the password only in App Review notes in App Store Connect; it is intentionally not stored in this file]**

The demo account is pre-populated with sample tasks, medications, and logs so every screen has representative content.

To see the main features:

- **Sign in** with the credentials above (or register a new account — registration sends a one-time verification code to the email address).
- **Focus tab:** daily task list; tap a task to complete it; tap the edit icon to modify it.
- **Heal tab:** medication reminders, one-tap "took it" logging, symptom and pain trackers, skin care routines.
- **Restore tab:** hydration tracking, gentle stretches and guided exercises, Daily Log (with PDF export for providers).
- **Reflect tab:** private journal with prompts and photo entries.
- **Settings (top-right/profile):** care team invites and account deletion.

All features are free — the app contains no subscriptions, paid upgrades, or in-app purchases.

---

## 4. External Services Used (paste into review notes)

The app uses the following external services to deliver core functionality:

| Service | Role |
|---|---|
| Base44 (platform) | App hosting, user authentication (email/password and Google sign-in), cloud database, file storage, push/email infrastructure |
| AI language models (via the Base44 platform's built-in AI integration — OpenAI, Anthropic, and Google models) | Optional generative features: hydration coaching chat, food and smoothie ideas, infusion-day theme suggestions, journal prompt drafting |
| Google OAuth | "Continue with Google" sign-in option |

The app integrates with no social media platforms and shares no user content to any third-party social network. No data brokers, ad networks, or tracking SDKs are used. The app contains no paid content, subscriptions, or in-app purchases of any kind.

---

## 5. Regional Differences (paste into review notes)

The app functions consistently across all regions. There are no region-specific features, content restrictions, or pricing tiers. All features are available to every user regardless of location. Pricing is displayed in USD via Stripe, which handles local payment methods and currency conversion automatically at checkout. The app is currently English-language only.

---

## 6. Regulated Industry / Protected Material Statement (paste into review notes)

Nightingale is a wellness and organizational support tool. It is **not** a medical device and does not provide medical advice, diagnosis, treatment, or telehealth services of any kind.

- All health-related data (medications, symptoms, vitals, pain) is **entered by the user themselves**; the app records and formats this information but does not interpret it or make recommendations.
- Exercise and stretching content is general wellness guidance (gentle mobility routines), with in-app cautions directing users to follow their surgeon's or physical therapist's advice.
- The app's generated provider report explicitly states it is "not a substitute for professional medical advice."
- No controlled, regulated, or protected third-party material is included: all content, copy, and imagery is original work created by the developer, or user-generated content created by the app's own users. No copyrighted media, licensed publications, or third-party trademarks are used.
- The developer does not dispense medication, sell drugs, or interface with pharmacies.

---

## Checklist before resubmitting

- [x] Demo account registered (see credentials above) and pre-populated with sample tasks, medications, and logs.
- [x] All paid content removed — every feature is free; no paywalls, checkout, or subscriptions remain in the app.
- [ ] Remove the "Nightingale Instagram" connector from Integrations in the dashboard (no longer used).
- [ ] Record the demo video per Section 1 on a physical device.
- [ ] Upload the video with the resubmission (App Store Connect → reply to the reviewer message → add attachment).
- [ ] Paste Sections 2–6 into the review notes / reviewer reply.