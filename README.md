# Doctor Proctor™

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24419500.svg)](https://doi.org/10.5281/zenodo.24419500)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)

**Doctor Proctor™** is a free, zero-cost, serverless web application built on Google Apps Script, Google Sheets, and Google Drive. Designed for educators, institutions, and behavioral researchers, it provides a lightweight, browser-based environment for administering proctored online examinations and conducting controlled experimental or survey data collection—without paid servers, external databases, or third-party subscriptions.

---

## Quick Start (No Coding Required)

You do not need to copy-paste any code manually. The entire application is bundled inside a Google Sheets template.

### 1. Copy the Template
1. Open the official template: **[Doctor Proctor™ Google Sheets Template](https://docs.google.com/spreadsheets/d/1doJCkRJXkhSKbsl_KVRuETSDzReZDpEwV-_Ss9Vv-FQ/template/preview)**
2. Click **Use Template** in the top-right corner to save a private copy (including all Apps Script code) to your own Google Drive.

### 2. Deploy as a Web App
1. In your copied Google Sheet, go to **Extensions → Apps Script**.
2. In the top-right corner of the script editor, click **Deploy → New deployment**.
3. Click the gear icon next to *Select type* and choose **Web app**.
4. Configure the deployment settings:
   * **Description:** `Initial deployment` (or any label you prefer)
   * **Execute as:** `Me`
   * **Who has access:** `Anyone`
5. Click **Deploy**, then complete the Google authorization prompt *(if you see an "App isn't verified" warning, click **Advanced → Go to [Project Name] (unsafe)**—this only grants your own copy permission to access your own Drive/Sheet)*.
6. Copy the generated **Web app URL** and share it with your students or research participants.

### Video Walkthrough
Watch the step-by-step setup and usage guide here:
* **[Watch the Setup & Usage Tutorial]([[PASTE_YOUR_VIDEO_LINK_HERE]](https://youtu.be/UoOlAqJmkEw))**
---

## Key Features

### Proctoring & Attention Controls
* **Fullscreen Enforcement:** Prompts and monitors fullscreen mode during active sessions.
* **Tab-Switching Detection:** Admin-configurable tab-switching limits that trigger on-screen warnings and/or automatic submission if participants leave the window.
* **Persistent Violation Tracking:** Logs focus loss across tab switches and fullscreen exits to safeguard exam and experimental data integrity.

### Assessment & Experimental Data Collection
* **Image-Based Stimuli & Visual Items:** Embed images directly within questions/items for visual stimuli, pictorial vignettes, diagrams, and cognitive or perceptual experiments.
* **Standard Item Types:** Supports Multiple-Choice Questions (MCQs) and fill-in-the-blank items for exams, psychometric scales, and surveys.
* **Participant Image Uploads:** Collect image responses from students or participants, automatically organized and stored in your Google Drive.
* **In-Browser R Coding (WebR):** Executes R code directly inside the browser with RStudio-style code suggestions and automated grading—no local R installation required.

### Admin Workspace & Data Ownership
* **Streamlined Workflow:** Downloadable item templates, an *Upload and Review* interface, and pre-launch validation checks.
* **Automated Data Export:** All responses are stored directly in your own Google Sheet with automated Excel export support for immediate statistical analysis.
* **Responsive, Accessible UI:** Clean light/dark theme support and real-time answer-saving confirmation.

---

## Citing Doctor Proctor™

If you use Doctor Proctor™ in academic research, experimental data collection, or institutional assessments, please cite the software using its permanent Zenodo DOI:

> Bagchi, D. (2026). *Doctor Proctor: Software for data collection* [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.24419500

### BibTeX
```bibtex
@software{bagchi_2026_doctor_proctor,
  author       = {Bagchi, Dipanjan},
  title        = {{Doctor Proctor: Software for data collection}},
  year         = 2026,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.24419500},
  url          = {[https://doi.org/10.5281/zenodo.24419500](https://doi.org/10.5281/zenodo.24419500)}
}
