# MediVerify AI

### AI-Powered Prescription & Pharmacy Bill Verification

MediVerify AI is a multimodal AI-powered application designed to help users cross-check medicines dispensed by pharmacies against a doctor's prescription and identify potential discrepancies in pharmacy bills.

Powered by **Google's Gemma 4 through the Gemini API**, the application analyzes prescription images, medicine slips, and bills to organize relevant information, compare medicine details, and highlight items that may require further verification.

By combining multimodal AI with rule-based validation, MediVerify AI aims to make prescription cross-checking and pharmacy bill review more accessible and transparent.

## Key Features

* **Prescription Analysis:** Extracts prescribed medicine names, strengths, dosages, and other available instructions.
* **Medicine Slip Verification:** Reads medicine details from pharmacy slips and compares them with the prescription.
* **Medicine Comparison:** Highlights potential mismatches in medicine names, strengths, formulations, or quantities.
* **Pharmacy Bill Analysis:** Extracts item descriptions, quantities, unit prices, and totals from pharmacy bills.
* **Billing Discrepancy Detection:** Checks arithmetic, compares listed quantities and prices, and flags potential inconsistencies.
* **Visual Document Understanding:** Uses Gemma 4 to interpret information from supported prescription, medicine slip, and bill images.
* **Transparent Results:** Presents identified discrepancies alongside the extracted information so users can review the original documents.

## Powered by Gemma 4

MediVerify AI uses Google's Gemma 4 through the Gemini API for multimodal document understanding and structured information extraction.

The application combines AI-generated extraction with conventional backend validation to make comparisons more predictable.

* **Gemma 4:** Interprets document content and extracts relevant medicine and billing information.
* **Backend validation:** Checks structured data, performs arithmetic, and compares available prescription and dispensing details.
* **Comparison engine:** Highlights possible mismatches and discrepancies for human review.

##  How It Works

1. **Upload Documents:** Provide a doctor's prescription, pharmacy medicine slip, and/or pharmacy bill.
2. **Extract Information:** Identify the available medicine names, strengths, quantities, instructions, and billing details.
3. **Compare Medicines:** Cross-check prescribed medicines against the medicines listed on the pharmacy slip.
4. **Validate the Bill:** Recalculate totals and compare quantities, prices, and line items where sufficient information is available.
5. **Identify Discrepancies:** Flag missing items, possible medicine mismatches, arithmetic errors, or unexplained differences.
6. **Review Results:** Display the findings and supporting extracted information so users can verify them against the original documents.

## Technology Stack

* **AI Model:** Google Gemma 4
* **AI Integration:** Gemini API
* **Frontend:** [Add the framework used]
* **Backend:** [Add the framework used]
* **Core Logic:** Structured extraction, medicine comparison, and billing validation

*Update the technology stack to reflect the actual implementation.*

## Project Objectives

* Help users cross-check dispensed medicines against their prescriptions.
* Improve the visibility of potential discrepancies between prescriptions and pharmacy slips.
* Detect arithmetic errors and inconsistencies in pharmacy bills.
* Demonstrate practical multimodal AI capabilities using Gemma 4.
* Combine AI-powered document understanding with deterministic validation.

##  Future Scope

* Improved support for handwritten prescriptions.
* Better handling of medicine brand names and generic equivalents.
* Comparison of pharmacy prices against independently verified pricing sources.
* Support for multiple regional languages.
* Downloadable verification reports with evidence for flagged discrepancies.

## Important Disclaimer

MediVerify AI is an informational verification aid, not a substitute for a pharmacist or qualified healthcare professional.

A flagged discrepancy does not automatically mean a pharmacy made an error. Brand names, generic equivalents, formulations, and packaging may differ while containing the same active ingredient, and some substitutions may require professional authorization.

Users should consult a qualified pharmacist or prescribing clinician to resolve suspected medicine discrepancies. The application must not independently recommend changing, stopping, or substituting prescribed medication.

Billing discrepancies should also be treated as potential issues until confirmed against the original bill and applicable pricing information.

## Built For

Developed as a hackathon project exploring the practical use of Google's Gemma 4 through the Gemini API to improve medicine and pharmacy bill transparency.

---

**MediVerify AI — Cross-check medicines. Verify bills. Make informed decisions.**
