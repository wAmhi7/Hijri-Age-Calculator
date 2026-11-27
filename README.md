# Kalkulator Umur & Mukallaf (Masihi & Hijrah Malaysia)
### Gregorian & Malaysia Hijri Age Calculator

A bilingual (Bahasa Melayu & English) Progressive Web App (PWA) for calculating current age in Gregorian and Hijri calendars, target Hijri milestone dates (such as *baligh* / *mukallaf* age), and *mukallaf* duration, with offline support and separate day offsets for historical or local calendar alignment.

**Live App:** https://wamhi7.github.io/Hijri-Age-Calculator/

---

## Features

* **Current & Birth Dates:** Displays Gregorian dates (with weekday names in BM/EN) alongside converted Hijri dates.
* **Current Age:** Calculates age in years, months, and days for both Gregorian and Hijri calendars.
* **Target Hijri Milestone & Mukallaf Duration:** Defaults to **15** Hijri years (customizable), showing the target Hijri date, target Gregorian date with weekday, and elapsed *mukallaf* duration (in Y/M/D and total days) or remaining days if not yet reached.
* **Separate Day Offsets (`-1`, `0`, `+1`):** Independent **Birth Date Offset** and **Current Date Offset** toggles so you can adjust a historical birth date to match a printed calendar without changing today's Hijri date.
* **Customization & Copy:** Switch between **BM** and **EN**, **System / Dark / Light** modes, and four accent palettes (**Biru / Blue**, **Hijau / Green**, **Ungu / Purple**, **Ambar / Amber**), plus one-click result copying.
* **Offline Ready PWA:** Caches assets via Service Worker (`sw.js`) so it works offline once loaded.

---

## Install on Android (PWA)

1. Open `https://wamhi7.github.io/Hijri-Age-Calculator/` in your Android browser (such as Firefox or Chrome).
2. Tap the **three-dot menu (`⋮`)** in the top-right corner.
3. Select **Install app** or **Add to Home screen**.

---

## Calendar & Offset Note

Hijri conversions in the web app use the browser's Umm al-Qura calendar (`islamic-umalqura`). Because local sighting (*rukyah* / *imkanur rukyah*) and printed calendars can differ by a day across months or years, use the **Birth Date Offset** and **Current Date Offset** controls (`-1`, `0`, `+1`) when cross-checking against hardcopy calendars or official Malaysian references such as `e-solat.gov.my`.
