# Bank Transaction & Financial Behavior Analytics (Power BI)

An end-to-end interactive **Power BI** reporting suite analyzing **13.31 million bank transactions** totaling **$571.84M** across **1,219 unique clients** (2010–2019). The dashboard provides executive-level visibility into customer demographics, card usage, merchant performance, geographic revenue distribution, and hourly transaction anomalies.

---

## 📊 Key Metrics at a Glance
* **Total Transaction Volume:** $571.84M
* **Total Transactions:** 13.31M
* **Active Clients:** 1,219
* **Timeframe:** 2010 – 2019 (Interactive Year & Month filtering)

---

## 🗂️ Dashboard Architecture (5 Report Pages)

1. **Analysis Bank Transaction (Executive Overview):**
   * **Annual Trend:** Area chart tracking transaction volume changes from 2010 to 2019.
   * **Demographic Breakdown:** Total spend segmented by Gender (Female: $293M, Male: $279M), Age Group (led by 45–54 at $153M), and Income Tier (led by $20K–$40K at $212M).
   * **Payment & Card Insights:** Spend distribution by Card Type (Debit: $326M, Credit: $226M, Prepaid: $20M) and Card Brand (Mastercard: $288M, Visa: $219M, Amex: $47M, Discover: $18M).
   * **Anomaly Tracking:** Hourly count of negative transactions/refunds, highlighting peak hours (e.g., 14:00 with 58K negative transactions).

2. **Top And Bottom Clients:**
   * Side-by-side tabular and horizontal bar chart rankings comparing the **Top 10 highest-spending clients** (led by Client ID `96` at $2.45M) against the **Bottom 10 clients** to support retention and VIP targeting strategies.

3. **Merchant City Summarize:**
   * Geographic performance ranking across merchant cities comparing **Total Amount** and **Number of Transactions**, identifying top-performing hubs such as **Houston ($6.62M / 146.9K transactions)**, **Miami ($3.55M)**, and **Louisville ($3.20M)**.

4. **Merchant Summarize:**
   * Granular merchant-level performance breakdown displaying **Total Amount** and **Transaction Count** per `Merchant ID` to identify high-volume and high-revenue partners.

5. **Client Summarize:**
   * Complete client-level lookup table and comparative bar chart displaying `Total Amount` and `Number of Transactions` per `Client ID` with interactive tooltips.

---

## 🛠️ Tools & Techniques Used
* **Power BI Desktop:** Data modeling, interactive cross-filtering, custom tooltips, and multi-page report navigation.
* **Power Query (M):** Data cleaning, type standardization, and preparation of multi-million-row transactional records.
* **DAX:** Custom measures for total transaction amount, transaction counts, negative transaction filtering, and dynamic ranking.

---

## 🚀 How to Use
1. Clone this repository or download the `.pbix` file.
2. Open the file in **Power BI Desktop**.
3. Use the **Year** and **Month** slicers on the main overview page to dynamically filter metrics across demographics, card types, and time periods.
