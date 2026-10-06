# Hi, I'm Ranjith 👋

### Google Ads Conversion Tracking Specialist
**GTM • GA4 • Meta Pixel • Conversion Tracking Audits**

I specialize in technical conversion tracking, tag architecture, attribution recovery, and data integrity audits across the marketing stack.

---

## 🚀 What I Do

- **Google Tag Manager (GTM)**: Enterprise container architecture, custom dataLayer event schemas, dynamic variables, and server-side tagging.
- **Google Analytics 4 (GA4)**: Key Event tracking, parameter mapping, custom dimension hygiene, cross-domain attribution, and real-time DebugView testing.
- **Google Ads Conversion Tracking**: Primary vs. secondary conversion goal configuration, click identifier persistence (GCLID/GBRAID/WBRAID), and Smart Bidding optimization alignment.
- **Meta Pixel & Conversions API (CAPI)**: Browser + server event deduplication (`event_id`), custom conversion parameters, and Match Quality optimization.
- **Enhanced Conversions & Consent Mode v2**: Privacy-compliant default states (`denied`), consent updates (`granted`), and hashed first-party user data handling without client-side PII leaks.
- **Lead & Form Tracking**: Robust form-submission validation, AJAX/fetch payload monitoring, honeypot protection, and multi-step SPA attribution retention.
- **Conversion Integrity Audits & Forensic QA**: Identifying phantom conversions (triggers on invalid submit), duplicate firing, schema drift, and CRM webhook mismappings.

---

## 🛠️ Featured Work & Implementation Demos

### 📌 [Tracking-Demos](https://github.com/RM292212/Tracking-Demos)
A complete, production-grade local training and demonstration workspace proving that **a form that works does not mean conversion data is trustworthy**.

- **12-Step Conversion Chain**: Full data pipeline trace from `Ad Click` &rarr; `Storage` &rarr; `Client Validation` &rarr; `API Mutex` &rarr; `CRM Store` &rarr; `dataLayer` &rarr; `GTM` &rarr; `GA4 Key Event`.
- **6 Reproducible Production Defect Scenarios**:
  1. *Premature Click Trigger*: False conversions firing on invalid form submissions.
  2. *Duplicate Conversion Event*: Legacy agency script + modern handler doubling conversion counts.
  3. *Silent Conversion Drop*: Typo in event constants (`demo_lead_sucess`) preventing tag matching.
  4. *DataLayer Schema Drift*: Missing `form_id` and mutated lead types breaking custom dimensions.
  5. *SPA Route Navigation Attribution Loss*: Multi-step routing stripping UTMs/GCLID before submit.
  6. *Server-Side CRM Mismapping*: Frontend conversion healthy while backend CRM records are corrupted.
- **Automated Verification Suite**: 32 Playwright E2E tests, 135 Vitest unit tests, and automated zero-PII scanners.

---

## 📬 Connect & Collaborate

- **GitHub**: [@RM292212](https://github.com/RM292212)
- **Specialization**: Tracking Audits • Google Ads Attribution • Tag Management • Analytics Implementation
