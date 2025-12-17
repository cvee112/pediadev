# PediaDev: Growth & Development Check

A single-file, offline-capable HTML web application designed for pediatric growth monitoring, immunization tracking, and developmental milestone assessment.

## Features

**1. Patient Details**

- **Input:** Date of Birth, Sex, Weight (kg), Height/Length (cm), Date of Visit.

- **Calculation:** Automatically computes exact chronological age in years, months, and days.

**2. Anthropometry Assessment**

- **WHO Standards:** Uses LMS method interpolation for Weight-for-Age, Length/Height-for-Age, Weight-for-Length/Height, and BMI-for-Age.

- **Dynamic Terminology:** Automatically switches between "Length" (<24 months) and "Height" (≥24 months).

- **Interpretation:** Provides color-coded Z-score classifications (e.g., Normal, Stunted, Wasted, Overweight, Obese) based on standard WHO cut-offs.

- **Visuals:** Displays Z-score distribution bars for quick visual reference.

**3. Immunization Tracker (PIDSP 2026)**

- **Schedule:** Digitized Philippine Pediatric Society (PIDSP) 2026 Immunization Schedule.

- **Status Logic:** Categorizes vaccines as "Due Now," "Upcoming," or "Overdue" based on the child's exact age.

- **Grouped View:** Organizes vaccines by type (e.g., Hepatitis B, Rotavirus, Measles) with specific clinical notes (e.g., minimum intervals, special indications).

**4. Developmental Milestones (CDC/AAP 2022)**

- **Checklists:** Comprehensive milestone checklists derived from the 2022 CDC/AAP revision.

- **Domains:** Covers Social/Emotional, Language/Communication, Cognitive, and Motor domains.

- **Longitudinal View:** Displays the current age-appropriate checklist and all previous age checklists in reverse chronological order to track progress over time.

## Technical Details

- **Stack:** Pure HTML5, JavaScript (Vanilla), and Tailwind CSS (via CDN).

- **Zero Dependencies:** No external libraries or build steps required. Runs directly in any modern browser.

- **Responsive:** Optimized for both desktop (table views) and mobile (card views) experiences.

## Usage

Simply visit the [website](https://cvee112.github.io/pediadev/). No internet connection is required after the initial load (Tailwind CSS is cached).

## Feedback

This is a work-in-progress. For feedback, feel free to message me (@cvee112) via Telegram.
