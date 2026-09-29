# SunMind — Dementia Care Companion

**Live site: <https://wrwilliam.github.io/alzheimers-ai-web/>**

SunMind is a companion web app for dementia patients and their family
caregivers. It brings prevention knowledge, daily health journaling, and an
AI health assistant together in one place, so that early signs are recorded,
changes over time stay visible, and every doctor visit starts from an
organized record.

> SunMind is a health information and journaling tool, not a medical device.
> It never diagnoses or prescribes — medical decisions belong to your
> clinician. In an emergency, call emergency services.

## What you can do with SunMind

| Feature | What it does |
|---|---|
| **Health Q&A** | Ask anything — symptoms, medications, whether to see a doctor. Answers use the patient's own record, check allergies first, and escalate urgent warning signs. |
| **Patient Profile** | One structured record per patient: diagnosis, stage, medications, allergies, other conditions. Every field is optional and fills in over time. |
| **Care Diary (Timeline)** | Log symptoms, incidents, vitals, and medication changes by typing or voice. Decline or improvement becomes visible on one timeline. |
| **Medical Files** | Photograph a prescription, lab report, or diagnosis — the AI extracts the key facts, and nothing is saved until you review and accept it. |
| **Learn** | Evidence-based prevention tips (WHO / Lancet Commission risk factors) and a monthly plain-language digest of new dementia research from PubMed. |
| **Doctor-visit summary** | Export the profile and recent changes as a clean summary to bring to the next appointment. |

## Getting started

1. **Open the app** at <https://wrwilliam.github.io/alzheimers-ai-web/>.
2. On the landing page, click **“Start free · 30-day trial”**.
3. **Create an account**: enter your email, a password, and your full name,
   then choose your role — **Patient** or **Family caregiver**. No credit
   card is required for the trial.
4. You land on the **Home** tab. The bottom tabs are: Home, Health Q&A,
   Care Diary, Medical Files, Profile, Learn, and Settings.

### Ask a health question

Open the **Health Q&A** tab, type a question in your own words — for
example, *“Mom started taking donepezil last week and now sleeps badly.
Should we be worried?”* — and press **Send**. The assistant answers using
the patient's profile (medications and allergies are checked first). If the
conversation surfaces new facts worth keeping, they appear in **Medical
Files** for your confirmation before anything is saved.

### Fill in the patient profile

Open the **Profile** tab and press **Edit**. Add whatever you know —
diagnosis, stage, date of birth, blood type, medications (name, dose,
frequency), allergies, and other conditions. Blank fields are fine; the
profile is designed to fill in gradually. For safety, allergy records always
stay active in the assistant's checks and can only be amended by your
clinician.

### Keep the care diary

Open the **Care Diary** tab and record an observation the moment it
happens — type a line (*“Got lost outside the front door today, first
time”*), hold the microphone button to speak a voice note, or attach a
photo. Entries are tagged as symptom, incident, vitals, medication change,
or note, and can be filtered later.

### Upload medical documents

Open the **Medical Files** tab and press **Upload a document photo** (take
a photo or choose from the gallery), or paste the document text directly.
The AI extracts medications, diagnoses, and lab values, and lists them under
**Waiting for your confirmation** — press **Accept** to file each item into
the profile, or **Reject** to discard it.

### Prepare for a doctor visit

On the **Profile** tab, press **“Export summary for doctor visit”** to get
a clean, printable summary of the record and recent changes.

## Pricing

- **Free 30-day trial**, no credit card required.
- **$5 / month** afterwards, including 2M AI tokens per month.
- **Referrals**: invite a friend — you both get a free month.
- Cancel anytime; your records stay exportable.

## Languages

SunMind supports multiple languages. Change the app language (which also
controls the assistant's reply language) under **Settings → Language**.

## About this repository

This repository hosts the static web build of the SunMind client, served
via GitHub Pages. The application source code is maintained in a separate
private repository.
