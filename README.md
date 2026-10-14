# RetailPulse Business Analytics

A practical record of 10 hands-on labs for a Business Analytics course, built around a sample retail sales dataset called RetailPulse. Practicals 1-6 use IBM Cognos Analytics; Practicals 7-10 use Power BI.

Contents
## Practical	Tool	Key skills
* 1	Generate a First RetailPulse Report	Cognos	Navigating Cognos, building a basic list report
* 2	Build a Grouped RetailPulse Sales List Report	Cognos	Grouping (Region > Store), currency formatting, summaries, page header
* 3	Filter RetailPulse Sales by Region and Date	Cognos	Simple and advanced detail filters, prompted filters
* 4	Build a Region x Product Crosstab	Cognos	Crosstab layout, multiple measures, row and column totals
* 5	Build the RetailPulse Sales Prompt Report	Cognos	Value, date-range and cascading prompts linked to filters
* 6	Build the Customer Insights Dashboard	Cognos	KPI card, line and bar charts, cross-filtering selection control
* 7	Import and Transform RetailPulse Data	Power BI	Power Query, data types, cleaning, conditional columns
* 8	Model, Calculate, and Publish a Sales Report	Power BI	Star-schema relationships, basic DAX, visuals, publishing
* 9	Time Intelligence and Advanced DAX	Power BI	Date table, YTD, YoY growth, CALCULATE/ALL, Performance Analyzer
* 10	Interactive Dashboard, RLS, and Power Platform	Power BI	Drill-through, bookmarks, row-level security, Power Automate, Power Apps

The combined record of all ten practicals is in RetailPulse_Practicals_1-10.pdf.

### Dataset

RetailPulse is a sample retail dataset with four regions (East, North, South, West), several stores per region, and four product categories (Electronics, Apparel, Home & Garden, Grocery). It is split into Sales, Product and Store tables in the Power BI practicals, and covers customer data for the Cognos dashboard.

### Highlights
Cognos reporting: grouped list reports, crosstabs with reconciled totals, and a cascading prompt page (Region updates the Store list).
Power Query: cleaning blank, duplicate and null rows, and adding a Sale Size conditional column.
* DAX measures:
  * Total Sales, Total Quantity, Average Order Value
  * Sales YTD, Sales LY, YoY Growth %
  * Region Share % using CALCULATE and ALL
  * Security and automation: row-level security roles (North Manager, South Manager) and a data alert wired to Power Automate.
IBM Cognos Analytics access (Practicals 1-6)
Power BI Desktop (Practicals 7-10)
Power BI Pro or Premium Per User, plus a work or school account, for publishing, RLS assignment, Power Automate and Power Apps (Practical 10, steps 4-6)
Notes
Figures in the "Output" sections are illustrative and generated from a sample dataset. Replace them with your own screenshots and values when reproducing the labs.
Each practical lists its objective, materials, step-by-step procedure, expected output and result. Practicals 7-10 also include viva-voce answers.
