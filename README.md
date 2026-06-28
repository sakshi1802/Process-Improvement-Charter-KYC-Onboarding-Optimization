# Process-Improvement-Charter-KYC-Onboarding-Optimization

## Project Goal
Re-engineer and automate the Know Your Customer (KYC) onboarding workflow to reduce average application processing time from 48 hours to under 5 minutes.

## 1. Problem Statement
Aura Financial is currently experiencing a 30% abandonment rate during the new customer onboarding process. The current "As-Is" workflow relies on manual intervention: customers upload identity documents, which are routed to a human compliance team for verification and manual watchlist checking. This manual queue creates a bottleneck, resulting in an average processing time of 48 hours per application. 

## 2. Business Impact
* **Revenue Loss:** The 30% drop-off rate translates to lost customer acquisition and lower initial deposit volumes.
* **Operational Inefficiency:** High Cost Per Acquisition (CPA) due to full-time employees (FTEs) spending an average of 15 minutes manually processing standard, low-risk applications.
* **Compliance Risk:** Manual data entry increases the risk of human error when checking applicant names against regulatory sanction lists (e.g., OFAC).

## 3. Proposed Technology Stack
* **Appian (BPMS):** To orchestrate the end-to-end workflow and manage exception handling (human-in-the-loop).
* **Automation Anywhere (RPA):** To automate the routine background checks against legacy public sanction databases.
* **DocuSign API:** To automate the generation and execution of the final customer account agreement.

## 5. Scope
* **In-Scope:** Identity document capture, OCR validation routing, sanction list verification, exception handling logic, and document signing.
* **Out-of-Scope:** Initial application funding, ongoing account monitoring, and post-onboarding marketing sequences.
