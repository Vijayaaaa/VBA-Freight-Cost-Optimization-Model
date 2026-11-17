# VBA-Driven Freight Cost Optimization & Logistics Network Model

## 📌 Executive Summary
This project showcases an advanced Excel macro-based logistics network optimization model developed using **Visual Basic for Applications (VBA)**. The decision-support tool was engineered to analyze complex distribution networks, clean large-scale shipment datasets from SAP-TMS using Python, and identify strategic cost-saving opportunities through route and contract optimization.

## 🏢 Business Problem
Large-scale manufacturing and distribution networks often suffer from unoptimized routing, fragmented transportation contracts, and hidden freight cost drivers. Without an automated evaluation tool, identifying the exact variables contributing to excess freight expenditure across distribution routes remains difficult and time-consuming.

## ⚙️ Solution Architecture & Technical Logic

Data was ingested from enterprise systems (SAP-TMS), cleaned and processed, and fed into an interactive VBA-powered decision support framework.

```mermaid
flowchart TD
    A[Raw Shipment Datasets from SAP-TMS] -->|Data Cleaning & Integration| B[Python Processing & Pandas]
    B --> C[Excel Data Backend & Pivot Analysis]
    C --> D[VBA Macro-Based Optimization Engine]
    D --> E[Route Efficiency & Contract Rules Evaluation]
    E --> F[Interactive Power BI Freight Dashboards]
    F --> G[Identified 15+ Cost Drivers & 30% Cost Reduction]
