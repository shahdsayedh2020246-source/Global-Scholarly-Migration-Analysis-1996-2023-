# Global Scholarly Migration Analysis (1996–2023) 🌐📊

An end-to-end data engineering and analytics project investigating global academic and scientific talent mobility patterns over nearly three decades (1996–2023).

---

## 📌 Project Overview
The **Global Scholarly Migration Analysis** project explores how researchers and scholars migrate across borders, identifying key talent magnets, "brain drain" phenomena, and the systemic impacts of economic and infrastructural factors on global research distribution. 

---

## 📐 Data Modeling (Galaxy Schema Architecture)
The project implements a robust **Galaxy Schema (Fact Constellation Schema)** to ensure high query efficiency, eliminate data redundancy, and support advanced multi-dimensional analysis:

1. **Fact Tables:**
   * **Country-level Migration (`df2`):** Tracks annual metrics per country (e.g., `number_of_inmigrations`, `number_of_outmigrations`, `net_migration`, and migration rates).
   * **Bilateral Flows (`df3`):** Tracks direct country-to-country migration corridors (origin-to-destination pathways).
2. **Shared Dimension Tables:**
   * **World Bank Demographics & Economy (`df1`):** Serves as a shared dimension linking countries, income levels, and temporal data (Years) to both fact tables for deep socioeconomic correlation.

---

## 🔍 Key Insights & Findings
* **The U.S. Talent Magnet:** The United States absorbed a net positive migration of over **32,000 researchers**, capturing nearly 4x the volume of the closest runner-up nation[cite: 1].
* **The Brain Drain Phenomenon:** Developing economies—most notably **India**—experience significant net outflows of scientific talent toward high-income regions[cite: 1].
* **Economic Drivers:** High-income economies heavily dominate talent retention and attraction due to superior research funding, advanced laboratory infrastructure, and institutional capacity.
* **Temporal Acceleration:** Cross-border scholarly mobility experienced a sharp upward trajectory post-2010, heavily driven by international academic networks and global collaboration frameworks.

---

## 💡 Strategic Recommendations
1. **Boost Local Research Infrastructure:** Emerging economies should allocate competitive funding tiers and build advanced R&D centers to mitigate domestic talent drain.
2. **Brain Gain & Return Initiatives:** Establish national policies, fellowship grants, and virtual collaboration ecosystems to reconnect with diaspora researchers.
3. **Expand Academic Partnerships:** Scale international dual-degree programs and joint research funding between institutions in developing and developed nations.

---

## 🛠️ Tech Stack & Tools
* **Data Processing & Modeling:** Python (Pandas, NumPy)
* **Database & Architecture:** Relational Star/Galaxy Schema Design
* **Visualization:** Python (Matplotlip)
* **Data Sources:** World Bank & Global Scholarly Migration Datasets (1996–2023)

---
