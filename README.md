# 🚀 META-TRACKER MY: AI-Powered Competitor Ad-Intel Station

## 📌 Executive Summary
META-TRACKER MY is an end-to-end, zero-cost competitor intelligence workstation designed to track, extract, and visualize sponsorship advertising across the Malaysian technology media ecosystem. By deploying a multimodal Gemini LLM vision engine inside a custom React workstation, the system converts unstructured ad screenshots from the Meta Ads Library into standardized datasets to track competitor Share of Voice (SoV), campaign launch velocity, and market penetration gaps.



---

## 🖼️ System Workstation & Dashboard Overview

| Campaign Ingestion & Log (React Workstation) | Executive Insights Hub (Looker Studio) |

---

## 🛠️ Technical Architecture & Pipeline

```text
[Meta Ads Library] 
       │
       ▼ (Clipboard Screenshot / Ctrl+V)
[React Ad-Intel Workstation] ──► [Gemini Multimodal Vision Engine]
       │                          (OCR & Entity Normalization)
       ▼
[Client LocalStorage Cache] ──► [Google Sheets (Master Database)]
(Text-Only Anti-Crash Engine)            │
                                         ▼
                             [Looker Studio Analytics]
