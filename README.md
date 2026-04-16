# Order-to-Cash (O2C): Complete Sales Cycle — SAP SD Project

**KIIT SAP Capstone Project Report**

---

## Student Details

| Field | Details |
|-------|---------|
| **Name** | Shibang Maity |
| **Roll Number** | 2305161 |
| **Program** | B.Tech CSE (6th Semester) |
| **Course** | SAP Data/Analytics Engineer |
| **Certification** | C_BCBDC — SAP Certified Associate: SAP Business Data Cloud |
| **Institution** | KIIT University |
| **Submission Deadline** | April 21, 2026 |

---

## Project Overview

This project documents the complete **Order-to-Cash (O2C)** end-to-end business process implemented in **SAP S/4HANA Sales & Distribution (SD)** module for a fictitious Retail/FMCG company — **RetailNova Pvt Ltd**.

The project also integrates **SAP Business Data Cloud (BDC)** as the analytics layer to provide real-time KPI dashboards and reporting on the O2C cycle.

---

## Fictitious Company

**RetailNova Pvt Ltd**
- Industry: Retail / FMCG (Fast-Moving Consumer Goods)
- Company Code: RN01
- Location: Mumbai, India
- Currency: INR

---


## 📊 Features
- End-to-End O2C Process
- SAP SD + FI Integration
- Business Data Cloud (BDC) Analytics
- KPI Tracking (DSO, Order Cycle Time, Revenue)

---

## O2C Process Flow

```
Inquiry (VA11) → Quotation (VA21) → Sales Order (VA01) → Delivery (VL01N)
     → Goods Issue (VL02N) → Billing (VF01) → Payment Receipt (F-28)
                          ↑
          SAP Business Data Cloud (BDC) — Analytics Layer
```

---

## Key SAP Transactions Covered

| Step | Process | T-Code |
|------|---------|--------|
| 1 | Customer Inquiry | VA11 |
| 2 | Quotation Creation | VA21 |
| 3 | Sales Order | VA01 |
| 4 | Outbound Delivery | VL01N |
| 5 | Post Goods Issue | VL02N |
| 6 | Billing / Invoice | VF01 |
| 7 | Payment Receipt | F-28 |

---

## Technology Stack

- **SAP S/4HANA** — Core ERP
- **SAP SD** (Sales & Distribution) — O2C transactions
- **SAP FI** (Financial Accounting) — Accounting entries & AR
- **SAP MM** (Materials Management) — Inventory / Goods Issue
- **SAP Business Data Cloud (BDC)** — Analytics & KPI dashboards
- **SAP Analytics Cloud (SAC)** — Visualization
- **SAP HANA** — In-memory database

---

## BDC Analytics KPIs

| KPI | Target |
|-----|--------|
| Order Fulfillment Rate | >= 95% |
| Order Cycle Time | <= 2 days |
| Days Sales Outstanding (DSO) | <= 30 days |
| Invoice Processing Time | <= 1 day |
| Return Rate | <= 2% |

---

## Files in This Repository

```
├── README.md                           # This file
└── O2C_Project_ShibangMaity_v2.docx   # Full project report (editable Word)
```

---

## References

- SAP S/4HANA SD Documentation — [help.sap.com](https://help.sap.com)
- SAP Business Data Cloud — [sap.com](https://www.sap.com/products/business-data-cloud.html)
- SAP Learning Hub — C_BCBDC Study Guide
- KIIT SAP Project Guidance Document
- GST India — [gst.gov.in](https://www.gst.gov.in)
