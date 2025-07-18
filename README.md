
# 📊 Flipkart_sales_data_analysis
\
## 🗂️ Overview

* **Background**: Why this dataset matters and what motivated the analysis.
* **Objective**: The key questions you aimed to answer.

---

## 🧮 Dataset

* **Source**: Where the data came from (e.g., scraped, downloaded from website, provided by client).
* **Description**: Summarize dataset structure (# of rows, columns).
* **Column glossary**:

  | Column Name                           | Description      | Units / Format |
  | ------------------------------------- | ---------------- | -------------- |
  | Name                                  | Phone model      | Text           |
  | MSP                                   | Discounted price | INR            |
  | Discount                              | % off            | Integer        |
  | *(continue for all relevant columns)* |                  |                |

---

## 🔍 Data Cleaning & Organization

* Describe steps taken:

  * Removed duplicates or irrelevant entries.
  * Standardized formats (e.g., ₹ removed, numeric sorting).
  * Created new columns, e.g., `Discount Amount = MRP - MSP`.
  * Used pivot tables to group by brand or RAM.

Include before/after snapshots or commentary on key transformations. ([data.research.cornell.edu][1], [datamanagement.hms.harvard.edu][2], [Reddit][3])

---

## 🧩 Analysis Workflow

* **Files**:

  * `flipkart_mobile.xlsx`: Original dataset
  * `cleaned_data.xlsx`: After preprocessing
  * `analysis.xlsx`: Pivot tables & charts reside here
* **Steps**:

  1. Filter to budget tier (<₹15 k)
  2. Pivot on `Brand` vs `Discount %` & `Ratings`
  3. Identify top value phones

---

## 📈 Visualizations & Insights

For each chart or pivot output:

1. **Chart name** (e.g., “Brand vs Average Discount”)

   * **What it shows**: e.g., "POCO and realme offer highest average discounts (\~33‑35%)".
   * **Why it matters**: Helps budget shoppers spot best deals.

2. **Chart name**

   * **What it shows** etc.

(Include screenshots if possible to enhance clarity.)

---

## ✅ Conclusions & Recommendations

* Budget buyers: **POCO C31 / Redmi 9i Sport** shine under ₹8 k with solid ratings.
* Mid‑range value: **realme 9i**, **POCO M4 Pro 5G** deliver best specs-to-price ratio.
* Premium pick (>₹20 k): **Realme 10 Pro+ 5G**, **iPhone 13**—choose for advanced features and warranty.

---

## 🛠️ How to Reproduce

1. Download **Excel 2016+** or equivalent.
2. Open `flipkart_mobile.xlsx`—it references `cleaned_data.xlsx`.
4. Refresh data/pivots if source data changes.
5. To add new models, update `raw_data.xlsx` and re-run cleaning steps.

---

## 📎 Files Included

* `flipkart_mobiles_data.xlsx`
* `README.md`

---

## 📅 Changelog

* **2025‑07‑18**: Initial commit with raw data, cleaned file, analysis workbook.
* *(Add version updates as you refine charts or data.)*

---

## 🧩 Contributing

Please fork and submit pull requests, especially if you add new models or apply the analysis to other categories (e.g., tablets).

## 📚 References & Resources

* README conventions for tabular data: Cornell Data Services ([Reddit][3], [data.research.cornell.edu][1])
* Scientific README template (Daniele Cook) ([Gist][4])
* Best practices on directory structure and clarity ([Gist][4])

---

### ✅ Why this README works

* Clearly documents dataset, transformation steps, and analytical logic.
* Helps hiring managers or collaborators quickly grasp your workflow.
* Follows recommended structure and metadata practices to boost reproducibility. ([Gist][4], [LinkedIn][5])

---

Feel free to customize sections, add visuals or scripts, and adjust formatting to match your project’s style. Need help generating Excel functions, charts or styling tips? Let me know!
