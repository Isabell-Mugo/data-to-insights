# 👋 Hi, I'm Isabell Mugo
### **Data Analyst | Business Intelligence Specialist**
I specialize in turning raw data into insights that drive efficiency, revenue, and better decision-making. From writing optimized SQL queries to building automated Power BI dashboards, I focus on solutions that scale and deliver real business value.

* **🔍 Root-Cause Analysis:** I go beyond the surface to explain *why* metrics change, providing the "so what" behind the data.
* **📊 Visual Storytelling:** I build clear, automated Power BI dashboards designed specifically for non-technical stakeholders to make data-driven decisions.
* **⚙️ Workflow Optimization:** I specialize in streamlining operations by replacing manual, error-prone Excel processes with scalable SQL-driven workflows.

---

### 🛠️ Technical Toolkit
* **Languages:** SQL (MySQL, BigQuery)
* **Tools:** Power BI (DAX, Power Query), Excel (Advanced Formulas, VBA)
* **Focus:** Data Cleaning, Trend Analysis, KPI Tracking

### 🚴‍♂️ Featured Project: Divvy Bikes Analysis
**Goal:** Analyze 5.5M+ rows of bike-share data to design a marketing strategy that converts casual riders into annual members.

![Divvy Bike Dashboard](https://github.com/Isabell-Mugo/data-to-insights/blob/main/divvy_dashboard.png?raw=true)

### 🛠️ The Technical Workflow
Instead of manual cleaning, I built a scalable **ETL pipeline** directly in Power BI to handle the massive dataset efficiently.

* **Data Extraction & Transformation (Power Query):**
    * **Automated Appending:** Combined 12 separate monthly CSV files (Dec 2024 – Nov 2025) into a single source of truth—eliminating manual file merging that previously took 2+ hours per analysis cycle.
    * **Data Hygiene:** Filtered out 47,000+ invalid "test" station entries, handled 3.2% null values in station names, and standardized 850+ station name variations.
    * **Feature Engineering:** Created custom columns for `ride_length` and `day_of_week` to enable behavioral segmentation analysis.
* **Data Modeling (DAX):**
    * Developed measures for **Average Trip Duration** and **Total Trips** with dynamic filtering by user type (Member vs. Casual).
    * Built time-intelligence calculations to compare seasonal performance YoY, revealing a 34% decline in casual ridership during winter months.

---

### 🔍 Key Insights & Business Impact

**Behavioral Patterns Discovered:**
* **Members** are "Utility Riders" with clear commute patterns (peak usage at 8 AM and 5 PM on weekdays)
* **Casuals** are "Leisure Riders" (peak usage on weekends between 12 PM - 4 PM)

**The Revenue Opportunity:**
* Casual riders average **42 minutes per trip** vs. members at **18 minutes per trip** (2.3x longer)
* This suggests casual users value the bikes for recreation and would benefit from unlimited ride memberships
* **Estimated conversion potential:** If just 15% of the 892,000 casual riders converted to annual memberships ($120/year), that represents **$16M in additional annual revenue**

**Seasonal Insight:**
* Casual ridership drops **67% in Q4/Q1** (winter months), while member usage only declines **23%**
* **Recommendation:** Launch targeted winter membership promotions in September-October before casual ridership declines

**Proposed Marketing Strategy:**
1. **Weekend Warrior Campaign:** Target casual riders on Saturday/Sunday with "Unlimited Weekend Rides" membership tier
2. **Seasonal Pre-Sale:** Offer 20% discount on annual memberships purchased before October to lock in casual riders before winter
3. **Station-Based Targeting:** Focus campaigns at top 25 leisure stations (parks, lakefront) where 68% of casual rides originate

---

### 📫 Connect with me:
🤝 **LinkedIn:** [wacera-mugo-15b30a94](https://www.linkedin.com/in/wacera-mugo-15b30a94/)  
📧 **Email:** [mugwacera@gmail.com](mailto:mugwacera@gmail.com)

