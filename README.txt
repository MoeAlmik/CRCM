Critical Care Billing Optimizer (Alberta)

App Description

The Critical Care Billing Optimizer is a point-and-click tool designed for physicians practicing critical care in Alberta. It streamlines and maximizes your AHS/SOMB fee-for-service or shadow billing by guiding you through all billable ICU encounters—consults, daily visits, return visits, procedures, and conferences—while automatically applying all relevant modifiers, after-hours codes, and block/unit caps.The app handles the complexity of time blocks, callback code limits, and ensures your billing stays compliant with Alberta’s unique rules, so you never under-bill or over-bill your shifts again.

Key Features

Guided Data Entry for all billable ICU services by time block

Automatic code selection (consults, repeat consults, ICU visits, callbacks, procedures, conferences, etc.)

Handles all after-hours and weekend/stat rules

Time block & unit cap enforcement (no over-billing)

Smart Optimizer: maximizes your billings by efficiently filling units in eligible blocks

Live summaries, warnings, and visual analytics

Exportable billing summaries (CSV)

Perfect for FFS, shadow billing, or for double-checking your own “paper” sheets

User Guide

1. Start the App

Launch the Streamlit app (usually: streamlit run ccm_app.py or similar).

The homepage will open in your browser.

2. Select If It’s a Weekend or Stat Holiday

Toggle “Is this a weekend or stat holiday?” at the top.

This sets the correct after-hours and callback rules for the shift.

3. Enter Patient Encounters by Time Block

The day is divided into four time blocks:

D: 2400–0659 (Night)

A: 0700–1695 (Day)

B: 1700–2159 (Evening)

C: 2200–2359 (Late Night)

For each block:

Click to expand the block (e.g., “⏱️ A: 0700–1695 Time Block”)

Enter what you did for each type of billable encounter:

Consults: New ICU admissions/consults (not the number of patients, but the number of new consults in that block)

Repeat Consults: Transfer of care/repeat consults (use rarely)

ICU Visits: Routine daily rounding visits on existing ICU patients (not new consults)

Short Return Visits (≤24 min): Brief, separate visits to ICU patients (first X visits per block are billed as callbacks; the rest as ICU visits)

Long Return Visits (≥25 min): Lengthy return visits (each is 2 units of ICU Visit)

Vents/CPAP/BiPAP, Resuscitations, Callbacks (extra), Intubations, Lines, Bronchoscopies, Conferences: Enter as applicable

Tip: You do not enter the number of “patients.”

For 6 ICU patients in the day: Enter 6 under ICU Visits (or adjust for consults as described above).

If entering consults/repeats in the overnight (D: 2400–0659) block, a reminder message appears:

“Remember to enter the number of calls (consults/repeats) manually for this block!The Optimizer does not add extra units to the overnight block (00:00–06:59), so only what you enter here will be billed.”

4. Calculate or Optimize

🧮 Calculate (No Optimization):

Click “Calculate Billing” to see exactly what you entered, the units, modifiers, block usage, and total billing.

⚙️ Efficiency Optimizer:

Enter your total hours worked for the day.

Click “Run Optimizer” to maximize your billings:

The app automatically fills any unused, eligible units in blocks where you saw patients (except overnight), ensuring you bill as much as allowed under SOMB rules.

5. Review Your Billing Summary

Check the tabular summary: All codes, modifiers, units, calls, time block, and amounts are listed.

Block limits and “units used” are shown; warnings pop up if you reach or exceed a block’s cap.

Visual analytics: Bar charts show your billing and efficiency by block, both pre- and post-optimization.

If you have hours that cannot be billed (due to block/unit caps), the app will warn you.

6. Download Your Billing

After calculation/optimization, you can download a CSV file of your billing summary for documentation or submission.

Frequently Asked Questions

Q: How do I enter “the number of patients”?A: Enter what you did for each patient, not the census. For six daily patients, enter 6 under ICU Visits in the day block (adjust if some are new consults).

Q: What about callbacks and returns?A:

Short returns (≤24 min): Enter the number in the relevant field. The app auto-bills up to the allowed callback cap per block and converts extra visits to ICU Visit units.

Long returns (≥25 min): Enter the number; each is billed as 2 units of ICU Visit.

Q: What if I enter more callbacks than allowed?A: The app caps them according to block/unit rules and warns you if you’re exceeding SOMB limits.

Q: Does the optimizer add visits to the 00:00–06:59 (03.05QB) block?A: No. The overnight block is not auto-filled by the optimizer; enter all billable calls in that block yourself.

Tips for Best Results

Use the “Short” and “Long Return Visits” fields for returns—the app does the callback/ICU split for you.

Don’t forget to enter procedures, conferences, and vents per patient.

Always double-check the block usage and warnings before submitting.

Ready to save time, maximize your billing, and never sweat the SOMB details again?Just start at the top and work your way down the page—this app keeps you efficient and compliant!

If you need a “quick start” card or a printable cheat sheet, just ask!

