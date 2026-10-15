# 🩺 MBBS College Explorer

**Your college preferences, in one clear view.**

A clean, responsive dashboard for comparing **47 MBBS colleges** by preference order, closing ranks, fees, service bonds, campus size, and more.

## 🌐 Live Website

### [Open MBBS College Explorer →](https://mbbscollegeexplorerupdated.vercel.app/)

Free to browse—no sign-in required.

## ✨ Features

- **Five cutoff lists:** 2026 Round 3, 2025 Round 3, 2025 Stray, 2024 Round 3, and 2024 Stray—with General and EWS ranks side by side.
- **Instant filters:** college/city search, state, college type, NEET rank, annual fees, service bond, NIRF rank, establishment year, and campus size.
- **Easy comparison:** sortable columns, sticky headers and college names, plus mobile-friendly horizontal scrolling.
- **College detail popups:** full fee, bond, campus, and location notes.
- **Personal preference panel:** editable notes for the current visit, with UCMS restored as preference #1.
- **Light and dark modes**, with no external libraries, tracking, or localStorage.

## 📊 Understanding the Data

The original 46-college dataset comes from the supplied Excel preference sheet. Cutoffs use **computed Excel values**, not formula text. UCMS was added from the supplied choice PDF, bringing the total to **47 colleges**; its unavailable figures remain **NA**.

| Marker | Meaning |
| :--- | :--- |
| **†** | Restricted quota—not an unrestricted All-India cutoff |
| **~** | Reported, approximate, or unverified source value |
| **–** | No cutoff value available |
| **NA** | Unavailable or not comparable |

Joining charges are **not** treated as annual fees. The NIRF year is **2025**; Aligarh's listed rank refers to parent AMU. UCMS's PDF choice uses **Delhi University Quota**, so eligibility must be checked.

> **Note:** This is a personal preference and comparison tool, not an official college ranking or an admission predictor. Verify current fees, bonds, campus arrangements, and quota eligibility with the relevant authorities.

## 🛠️ Run Locally

Download the project and open **`index.html`** in a modern browser. No installation or build step is needed.

```text
index.html    # Inline HTML, CSS, JavaScript, and embedded college data
vercel.json   # Static deployment configuration
README.md     # Project guide
```

**Built with:** vanilla HTML · CSS · JavaScript  
**Hosted on:** Vercel

## 🚀 Deploy

From the project folder, with Node.js installed:

```bash
npx vercel
npx vercel --prod
```

Choose **Other** as the framework, leave the build command disabled, and use **`.`** as the output directory if prompted. Alternatively, import the repository into Vercel using the same settings.

---

**[Explore the colleges →](https://mbbscollegeexplorerupdated.vercel.app/)**
