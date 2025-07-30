# Access to Drinking Water – Part 2: Transforming the Data

This is Part 2 of a two-part data analytics project focused on **access to safe and affordable drinking water**, aligned with **United Nations Sustainable Development Goal 6 (Clean Water and Sanitation)**.

In this stage, we go beyond descriptive statistics and perform a longitudinal analysis of changes in water access from **2000 to 2020** using the WHO/UNICEF JMP dataset.

---

## Project Focus

We transformed and enriched the original dataset by:
- Adding time-based features to analyze change over time
- Calculating **Annual Rates of Change (ARC)** in access to basic water services
- Comparing changes by **area type** (national, rural, urban)
- Analyzing **differences across regions**
- Investigating the influence of **population size** on water access trends

---

## Key Analysis Tasks

### 1. Understanding Dataset Time Span
- Verified how many years are represented per country
- Calculated the **average year gap** in measurements

### 2. Computing Annual Rates of Change (ARC)
- Defined ARC for national, rural, and urban access
- Addressed errors from missing/null values

### 3. Exploring Access by Area
- Measured differences in ARC between rural and urban populations
- Identified countries with **100% access**, **no change**, **increase**, or **decline**

### 4. Comparing Regions
- Mapped countries to regions
- Calculated regional averages for ARC
- Created visualizations showing **ARC vs. population size** by region

---

## Notable Findings
- **Sub-Saharan Africa** lags significantly in water access and will likely not reach 100% coverage before 2080 if trends continue.
- **Rural areas** showed higher average improvements, but this is affected by low starting points and fewer countries having 100% coverage.
- Many countries showed **no significant change** or even **decline** in rural access.

---

## Files Included
- `transformed_drinking_water_data_2000_2020.xlsx` (or `.csv`): Cleaned and transformed dataset
- `README.md`: Project documentation
- Visualizations (optional)

---

## SDG Alignment

This project contributes to global understanding and analysis supporting **SDG 6 – Clean Water and Sanitation**, with focus on sustainability and equity across geographies.
