<div align="center">
  <h1>Fineprint</h1>
  <p><strong>Know what you're actually signing.</strong></p>

  <img src="https://img.shields.io/badge/Hackathon-Winner%20Potential-FF3B5C?style=for-the-badge&logo=devpost" alt="Hackathon">
  <img src="https://img.shields.io/badge/AI-Claude_3.5-FF3B5C?style=for-the-badge&logo=anthropic" alt="Claude">
  <img src="https://img.shields.io/badge/UI-Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss" alt="Tailwind">
  <img src="https://img.shields.io/badge/PDF-pdf.js-4A90E2?style=for-the-badge" alt="PDF">

  <h3>Upload any contract → Get lawyer-style redlines, risk scores, and negotiation playbooks in seconds.</h3>

  [![Demo Video](https://img.shields.io/badge/Watch_2min_Demo-FF3B5C?style=for-the-badge&logo=youtube)](https://youtu.be/your-video-link)

  ![Fineprint Hero](https://via.placeholder.com/800x400/1f2937/ffffff?text=Fineprint+-+Redline+Your+Future)  
  *(Replace with actual GIF/screenshot below)*
</div>

## ✨ The Problem

Millions of students and young professionals blindly sign **leases, job offers, loans, NDAs, and T&Cs** — often with hidden traps that cost thousands or limit their future.

**Fineprint** changes that.

## 🎯 Live Demo

**[Try Fineprint Now →](https://fineprint-ai.vercel.app)**

*(Fully functional offline demo with two rich sample documents)*

## 🔥 Key Features

- **Multimodal AI Engine** — Handles PDF, scanned photos, screenshots, and raw text
- **Signature "Redline Margin" Aesthetic** — Authentic bond-paper + red-ink visual language
- **Structured Intelligence** — Risk score (0-10), ranked redlines, obligation split, key terms
- **Negotiation Playbook** — Specific counter-language for every high/medium risk
- **Interactive Experience** — Click redlines → highlight in original document
- **One-Click Export** — Professional PDF report with highlights and annotations
- **Student-First Samples** — Lease + Employment Offer baked in

### Animated Demo (GIF)

![Fineprint in Action](https://via.placeholder.com/800x500/1f2937/white?text=Demo+ GIF:+Upload+→+Redlines+Light+Up)

*(Record a short screen recording of your app and convert to GIF using https://gifcap.dev or ffmpeg)*

## 🛠️ How It Works (Advanced Pipeline)

```mermaid
graph LR
    A[Upload PDF / Photo] --> B[pdf.js Extraction + OCR Fallback]
    B --> C[Claude 3.5 Structured Analysis]
    C --> D[JSON Output Parsing]
    D --> E[Interactive Redline Margin UI]
    E --> F[PDF Report Export with html2canvas + jsPDF]
