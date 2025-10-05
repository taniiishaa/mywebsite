# 🌿 Root2Rise: AI-Powered Decision Support System for FRA Implementation

[![Root2Rise Logo](https://img.shields.io/badge/Root2Rise-Government%20of%20India%20Initiative-004D40?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA1MTIgNTEyIj48IS0tISBGb250IEF3ZXNvbWUgUFJPIEZyZWUgLy8gZGVmYXVsdCByZXByZXNlbnRhdGlvbiBmb3IgZmEtc2VlZGxpbmcgLS0+PHBhdGggZmlsbD0iIzRhZjUwIiBkPSJNMzY4IDM5Ny45Yy01LjMtMS41LTguNy02LjctOC43LTEyVjI4NC40YzAtNS4zIDMuNC0xMC41IDguNy0xMlM0MDMgMjc2LjcgNDAzIDI4Mi45VjM4Ni41QzQwMyAzOTIuNyAzOTkuNiAzOTcuOSAzOTQuMyAzOTYuNFMyMDcgMTcuMSAxOTYuOSAxLjdzLTEwLTExLjIgMy0xN0wxNjAgMzIuNkMxNDcgMzkuMSAxMzggNDkuNSAxMzUgNjJjLTE1IDc4LjQgMTggMTQ5LjEgNTMgMjEyLjZjMi4xIDQuMSAyLjUgOSAyLjcgMTMuNkMxNTYuNSAzMjAuNSAxMzkgMzQ1LjIgMTE3IDM2OC41Yy01LjktNS41LTEzLjEtOC42LTIwLjYtOC43Yy0yLjQgMC00LjUgLjUtNS42IDIuNUwxMTQgMzYyYy02LjcgMTMuNS0xMCAyOC05LjggNDIuOGMwIDE5LjQgMTIgMzcuMyAzMS4yIDM5LjNDMjAwLjcgNDQ2LjggMjkxLjUgNDgxLjMgMjQ2LjggNDgzLjljLTMwLjMgMi40LTU3LjktMTUtNzMuNS00My41Yy05LjQtMTYuMy0yNS4xLTI0LjItNDIuMS0yNC4yYy0xOC40IDAtMzQuMiA5LjctNDUgMjcuMkM4Mi41IDQ5MS45IDAgNTEyIDAgNTEyVjM2NWMwLTIzLjYgMTcuNS00My42IDQwLjYtNDcuNmM3LjgtMS40IDE1LjcgMS40IDIxLjUgNy42Yy00LjQtMjEuMSAxLjgtNDIuOCAxOC41LTU1LjVsLTQ1LjktNDkuNWMtNi44LTYuNy0xMC41LTE1LjktMTAuNS0yNS42YzAtMTAuMyAzLjgtMjAuNSA3LjYtMjcuNmM1LjgtMTAuNyAxNi44LTE2LjcgMjcuNS0xNS45Yy0zLjQtMTguNyAxLjUtMzYuNSAxNC01MC44YzE1LjYtMTUgMzcuNS0yMi41IDU5LjgtMjEuMWMxOC42IDIgMzUuNyA4LjQgNDkuOSA1Ny43Yy01IDctMTIuNSAxMS41LTIyLjMgMTEuN2MtMTIuOCAwLTIzLjYtNC44LTMxLjgtMTIuM2MtMTEuMS0xMC0xNC0yNi02LjctNDAuMWwyOC41LTQ1LjljLTcuMS02LjgtMTEuMi0xNS41LTExLjItMjUuMWMwLTExLjEgNC4yLTIxLjUgMTIuMy0yOS40YzEyLjQtMTIuMSA3MS42LTY5LjkgOTMuOS0xMDMuNUM0NDQgNDIuMSAzNjggMzk3LjkgMzY4IDM5Ny45eiIvPjwvc3ZnPg==)](https://www.sih.gov.in)
[![Status](https://img.shields.io/badge/Status-Prototype%20&%20Demonstration-green?style=for-the-badge)](https://www.sih.gov.in)
[![Technology](https://img.shields.io/badge/Technology-WebGIS%20|%20AI%20|%20Cloud-orange?style=for-the-badge)]()

---

## 💡 The Problem: Unlocking Tribal Empowerment

The **Forest Rights Act (FRA), 2006** is a landmark piece of legislation designed to recognize and vest forest rights and tenure to Scheduled Tribes and other traditional forest dwellers. However, its implementation is hampered by:

1.  **Legacy Data:** Manual, dispersed, and non-standardized paper-based records.
2.  **Lack of Spatial Context:** Claims and titles are often not accurately mapped, leading to boundary disputes and difficulty in coordinating with other government schemes.
3.  **Inefficient Scheme Layering:** Inability to effectively link FRA beneficiaries and their recognized assets (land, forest resources) with crucial Central and State development schemes (e.g., PM-KISAN, MGNREGA).

## ✨ Our Solution: Root2Rise

**Root2Rise** is a comprehensive, centralized platform that leverages **Artificial Intelligence** and **Geospatial Technology (WebGIS)** to digitize the entire FRA process and provide a dynamic **Decision Support System (DSS)** for evidence-based policy making.

### Key Technology Stack

| Component | Technology | Role in Root2Rise |
| :--- | :--- | :--- |
| **Frontend** | HTML5, CSS3 (Custom), JavaScript, **Leaflet.js** | Interactive user interface, visualization of FRA Atlas and real-time data. |
| **Backend/Core Logic (Conceptual)** | Python (with libraries like **SpaCy** for NER, **TensorFlow/PyTorch** for Satellite Image ML), **PostgreSQL/PostGIS** | AI-powered data extraction, spatial querying, and DSS algorithm execution. |
| **Geospatial** | **WebGIS (Leaflet)**, **Remote Sensing Data** (Sentinel-2, Landsat) | Mapping of Individual/Community Rights, monitoring of forest cover and asset changes. |

## ⚙️ Core Features & Capabilities

The platform is structured around three high-impact modules:

### 1. AI-Powered Data Digitization Engine

* **Named Entity Recognition (NER):** Uses AI to automatically parse scanned copies of legacy FRA claims and titles, extracting key entities like name, village, area (in hectares), and GPS coordinates.
* **Data Standardization:** Converts unstructured text data into a standardized digital format, eliminating manual data entry errors and dramatically speeding up the processing pipeline.

### 2. Interactive FRA Atlas (WebGIS)

* **Real-time Visualization:** Displays recognized **Individual Forest Rights (IFR)**, **Community Rights (CR)**, and **Community Forest Resource (CFR)** areas on an interactive map.
* **Integrated Asset Mapping:** Overlays AI-mapped features (agricultural land, water bodies, forest types) derived from satellite imagery onto the FRA areas.
* **Multi-Layer Interface:** Allows stakeholders (Forest Dept., Tribal Dept., Gram Sabhas) to view and contribute different spatial layers.

### 3. Decision Support System (DSS)

* **AI Scheme Layering:** Automatically analyzes a beneficiary's recognized FRA assets (e.g., $1\text{ hectare}$ of agricultural land, proximity to a water body) against the criteria of various Government Schemes (PM-KISAN, MGNREGA, JJM).
* **Policy Recommendations:** Provides state/district-level insights, highlighting discrepancies, areas with high claim rejection rates, and regions ripe for targeted development projects.
* **KPI Dashboard:** Offers a single-view analytical dashboard (as seen in the mock-up) for monitoring the progress of FRA implementation metrics across the state.

## 💻 Prototype Walkthrough

The uploaded HTML/CSS/JS code demonstrates a functional front-end wireframe and initial integration points:

* **`fra-atlas` Section:** Shows the implementation of the **Leaflet.js** map with dummy markers for FRA locations in India, and interactive layer toggles (`ifr`, `cr`, `cfr`, `water`, `agriculture`).
* **`dss` Section:** Illustrates the **Scheme Layering** output, showing simulated eligibility status for major schemes like **Jal Jeevan Mission** and **PM-KISAN**, which would be generated by the backend AI.
* **Professional Design:** Adopts a 'Government-like' color palette (Deep Teal, Green) and typography for a polished, official appearance.

## 🤝 Contribution

This project was developed for the Smart India Hackathon 2025.

**Team Name:** \ JM_Root2Rise
**Team Leader:** \ Tanisha 
**Team Members:** \ Pulkit Arora , Riddhi , Nikhil , Sushant , Trisha 
**Problem Statement:** \ Development of AI-powered FRA Atlas and WebGIS-based Decision Support System (DSS) for Integrated Monitoring of Forest Rights Act (FRA) Implementation. (States to be concentrated: Madhya Pradesh, Tripura , Odisha, Telangana)
