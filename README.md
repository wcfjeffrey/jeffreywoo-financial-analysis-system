## Financial Analysis System (for PRC Listed Companies by Python)

<img src="assets/JeffreyWooFinAnalysisSys.png" alt="JeffreyWooFinAnalysisSysBanner" width="1200" height="900" />

## 📝 Preface

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)
![Jupyter](https://img.shields.io/badge/Jupyter-ffffff?logo=Jupyter)
![SQLite](https://img.shields.io/badge/SQLite-%2307405e.svg?logo=sqlite&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-2CDE85?logo=Qt&logoColor=fff)
![Matplotlib](https://custom-icon-badges.demolab.com/badge/Matplotlib-71D291?logo=matplotlib&logoColor=fff)
![NumPy](https://img.shields.io/badge/NumPy-4DABCF?logo=numpy&logoColor=fff)
![Anaconda](https://img.shields.io/badge/Anaconda-44A833?logo=anaconda&logoColor=fff)

"Big data" has evolved from a catchphrase into the driving force behind modern financial intelligence. Advances in computing power and the advent of cloud computing have democratized data analysis, putting sophisticated insights within reach of firms of all sizes. In response, the accounting and finance industry is rapidly shifting toward data-driven optimization. Companies that leverage efficient technology solutions to analyze both structured and high-volume unstructured data can unlock competitive advantages and discover new market opportunities.

This project represents the starting point of my personal and professional journey into data-driven financial analysis. It serves as the logical and technical foundation for all my subsequent AI-powered financial applications, including advanced valuation models and risk simulations.

More than just a technical exercise, this system demonstrates how to transform enduring financial theories—including DCF (Discounted Cash Flow), DuPont Analysis, and Capital Structure Theory—into practical, executable analytical tools. Although technology stacks evolve (from this Python-based desktop application to modern web and AI integrations), the core analytical framework, valuation logic, and risk assessment mindset established here remain central to my financial work today. I regard this project as a "living methodological document," showcasing my mastery of financial fundamentals and my ability to systematize and engineer complex theories into scalable solutions.

By creating this analysis system for PRC listed companies using Python, I aimed to deepen my own expertise and build a tool that could also help investors formulate better, data-backed investment strategies.

If you are interested in it, please read the following information:

## 🎯 Purpose

Applying Python to establish a financial analysis system for PRC listed companies.

## 🤖 Tech Stack

- **Language** — Python 3.7, Jupyter Notebook  
- **Database** — SQLite3 (lightweight relational database for storing company financials)  
- **UI** — PyQt5 (desktop GUI, designed with Qt Designer)  
- **Visualization** — Matplotlib (charts, trend graphs), NumPy (numerical computations)  
- **Environment** — Anaconda  
- **Data Sources** — CSV imports of PRC-listed company financials, integrated into SQLite

## 💰 Financial Analysis Theories Applied

This system applies not just technical coding but also embeds core financial analysis theories—ratio analysis, DuPont decomposition, valuation models, and risk frameworks for professional finance/accounting:
- **Ratio Analysis Frameworks** — 
The app calculates liquidity (current ratio, quick ratio), profitability (ROA, ROE, gross margin), and leverage (debt-to-equity) ratios, directly aligning with textbook financial statement analysis.  
- **DuPont Analysis** — 
Integrated into ranking dashboards, ROE is decomposed into net profit margin, asset turnover, and equity multiplier, helping users identify the drivers of shareholder value.  
- **Trend & Comparative Analysis** — 
Using Matplotlib, the app visualizes multi-year trends and peer comparisons, reflecting horizontal and vertical analysis methods taught in accounting and finance.  
- **Discounted Cash Flow (DCF) & Net Present Value (NPV)** — 
Forecasting modules apply time value of money principles to evaluate investment projects and corporate valuation, supporting investor decision-making.  
- **Capital Structure & Risk Theories** — 
Debt-to-equity and asset-liability ratios are embedded into dashboards, reflecting Modigliani-Miller and trade-off theory considerations for financing decisions.  
- **Variance & Sensitivity Analysis** — 
Stochastic simulations test resilience of financial outcomes under different market conditions, aligning with actuarial-style stress testing and modern risk management.  
- **Corporate Governance & Compliance** — 
By modeling PRC-listed companies, the app implicitly applies controlled foreign corporation (CFC) regime awareness and compliance frameworks, ensuring group structures and intercompany transactions are correctly represented.

## 📈 System Outcome

1. Search Page (start.py)
<img src="assets/JeffreyWooFinAnalysisSys1.jpg" alt="JeffreyWooFinAnalysisSys1" width="1200" height="900" />

2. Main Window (main.py)
<img src="assets/JeffreyWooFinAnalysisSys2.jpg" alt="JeffreyWooFinAnalysisSys2" width="1200" height="900" />

3. Ranking of Company Rating (rank.py)
<img src="assets/JeffreyWooFinAnalysisSys3.jpg" alt="JeffreyWooFinAnalysisSys3" width="400" height="600" />

4. Selection of Company (selectfirm.py)
<img src="assets/JeffreyWooFinAnalysisSys4.jpg" alt="JeffreyWooFinAnalysisSys4" width="400" height="600" />

## 🛠️ Project Procedure

• **System Development Environment:**  
a. Integrated development environment: Anaconda  
b. Programming language: Python 3.7  
c. Database: SQLite3  
d. UI graphics library: PyQt5  
e. Other libraries: Matplotlib, Numpy

• **Description of Related Technology**  
I used the SQLite database, the front end UI PyQt5 image library and the preliminary UI interface design tool through Qt Designer.

• **Database Establishment**  
For database, I used SQLiteSpy as it was easy to use and did not require any complicated configuration for its installation. I imported the csv tables of each company's financial data calculated before into the database, please refer to createdatabase.py.

<img src="assets/JeffreyWooFinAnalysisSys5.jpg" alt="JeffreyWooFinAnalysisSys5" width="1200" height="900" />

After that, I used Qt Designer to preliminarily design the search page, and then further refined the platform to get start.py.

<img src="assets/JeffreyWooFinAnalysisSys6.jpg" alt="JeffreyWooFinAnalysisSys6" width="1200" height="900" />

The files start.py, main.py, rank.py, selectfirm.py, etc. corresponded to the respective pages, and the financial comments referred to the website [caibaoshuo.com](https://caibaoshuo.com/) (财报说). For example, the financial performance of the sample company Ping An Bank is as follows:

<img src="assets/JeffreyWooFinAnalysisSys7.jpg" alt="JeffreyWooFinAnalysisSys7" width="400" height="600" />
<img src="assets/JeffreyWooFinAnalysisSys8.jpg" alt="JeffreyWooFinAnalysisSys8" width="1200" height="1800" />

The evaluation was generated by the automatic judgment of various data machines.

But how to insert the legend of the data change trend in the table?

<img src="assets/JeffreyWooFinAnalysisSys9.jpg" alt="JeffreyWooFinAnalysisSys9" width="1200" height="1800" />

This data came from main.py. I applied Matplotlib to generate pictures, and then inserted Form Controls into the table.

## ⭐ Finance Skills Strengthened
• Full‑stack architecture for financial analytics applications.  
• Advanced Python programming for financial system data integration.  
• Secure handling of financial datasets & environment variables.  
• AI‑powered financial modeling & variance analysis workflows.  
• File parsing & structured data transformation (CSV, PDF, SQL) for automated reporting.  
• Data visualization with Matplotlib & interactive dashboards for decision support.  
• Database management & financial analytics — contributing to professional growth in finance transformation & investment strategy.
