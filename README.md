# 💳 UPI FinTech Transaction Analytics: End-to-End Power BI Pipeline

## 📌 Project Overview

This project delivers an end-to-end data analytics solution that models and visualizes digital wallet and UPI (Unified Payments Interface) transactions. Sourced from **Kaggle**, the raw transactional data was ingested, cleaned, and transformed into a highly interactive, dual-view operational report using **Power BI Desktop**, then deployed via **Power BI Service (Fabric)**.

To maximize user experience (UX) and allow stakeholders to seamlessly pivot between high-level macro trends and granular multi-currency metrics, the dashboard implements custom **bookmark-driven view switching**, **synchronized slicers**, and **cross-column conditional formatting**.

## 🚀 Advanced UI/UX & Technical Implementations

-   **Dynamic Visualization Toggling (Bookmarks):** Implemented custom bookmark navigation to allow users to switch dynamically between **Line Charts** (for trend trajectory) and **Column Charts** (for comparative volume) on the fly for both transaction amounts and remaining balances.
    
-   **Synchronized Cross-Report Slicers:** Configured multi-field synchronized slicers (including BankNameSent, BankNameReceived, City, DeviceType, Gender, Age Groups, MerchantName, PaymentMethod, Purpose, and TransactionType) ensuring state persistence across different analytical views.
    
-   **Multi-Currency Conditional Matrix Formatting:** Engineered a detailed matrix view that tracks transactions across multiple global currencies (EUR, USD, GBP, INR) mapped against major operational hubs (Bangalore, Delhi, Hyderabad, Mumbai), leveraging color-scale conditional formatting to instantly flag high-value volume and liquidity pools.
    

## 💡 Key Business Questions Answered

Based on the dashboard design and views, this project empowers FinTech stakeholders and banking executives to answer crucial operational questions:

### 1. Macro Transaction Trajectories & Seasonality

-   **When do transaction volumes peak?** Tracks the monthly timeline of UPI transaction counts across the calendar year to isolate peak spending months (e.g., identifying May as a peak activity period at 1,707K transactions).
    
-   **What are the cyclical low periods?** pinpoints operational troughs (such as the drop in transaction counts down to 1,599K in August) to help plan infrastructure maintenance or targeted marketing campaigns.
    

### 2. Demographic & Device Segments

-   **How do user parameters influence transaction trends?** By utilizing integrated filters for Age Groups, Gender, and DeviceType, stakeholders can immediately answer questions like: _"What do transaction trends look like specifically for the A2 Age Group segment?"_ or _"Are iOS users driving more transaction volume than Android users?"_
    

### 3. Banking Ecosystem & Liquidity Operations

-   **What is the remaining liquidity trend?** Answers how the total average or closing balance fluctuates month-by-month to assist partner banks in managing cash float and predicting fund settlement needs.
    
-   **How are interbank fund transfers performing?** Identifies potential friction points or transaction volume corridors by filtering specific sending and receiving bank combinations (`BankNameSent` vs. `BankNameReceived`).
    

### 4. Cross-Border & Regional Performance Matrix

-   **Which regional corridors generate the highest financial volume?** Highlights which specific city-currency pairings drive the largest market share (e.g., mapping Bangalore/EUR transactions directly against Mumbai/INR transactions).
    
-   **Where are the high-value transaction clusters located?** The conditional color gradient immediately exposes outlier months where specific regional nodes processed unusually high volumes (e.g., highlighting large asset movements in March for Bangalore and April/August for Hyderabad).
    

## 🏗️ Project Architecture & Repository Structure

1.  **Data Ingestion:** Sourced raw transactional profiles from **Kaggle**.
    
2.  **Data Modeling & DAX:** Star-schema development optimization, establishing relationship structures to gracefully handle deep filter criteria across multi-layered dimensions.
    
3.  **Report Development:** Built custom canvas templates with dark title elements and custom control buttons inside **Power BI Desktop**.
    
4.  **Cloud Deployment:** Published directly to a workspace in **Power BI Service (Fabric)** for stakeholder distribution.
    

## 📸 Dashboard Previews

### 1. Monthly Transaction Trend Analysis (Line View)
<img width="1359" height="760" alt="Screenshot 2026-06-17 164018" src="https://github.com/user-attachments/assets/cfedd399-2146-4d05-8d9f-2a90871be903" />


<img width="1339" height="753" alt="Screenshot 2026-06-17 164121" src="https://github.com/user-attachments/assets/a7117f6a-a1e2-4d63-add7-82e84a6cb1ff" />


### 2. Balance Volume Variations (Column View)

<img width="1341" height="750" alt="Screenshot 2026-06-17 164206" src="https://github.com/user-attachments/assets/00adab2e-0262-47a0-9c64-d728f45d5b9f" />

### 3. Regional Multi-Currency Performance Matrix
<img width="1331" height="748" alt="Screenshot 2026-06-17 164218" src="https://github.com/user-attachments/assets/b1a80840-d8dc-4e31-8de2-98b1f80bd73f" />


## 🛠️ Tech Stack & Skills Highlighted

-   **BI Tools:** Power BI Desktop, Power BI Service (Fabric)
    
-   **Dashboard Features:** Bookmarks, Selection Panes, Synchronized Slicers, Conditional Formatting Matrixes, Custom Slicers
    
-   **Analytical Skills:** FinTech KPI Tracking, Trend Seasonality Analysis, Demographic Filtering, Multi-Currency Aggregations
    

**Author:** Venkat Yalamanchili

**Contact:** yalamanchilivenkat56@gmail.com
