# Occupational-Health-Safety-Analytics

---

# 🦺 Health & Safety Hub: Occupational Health & Safety Analytics Dashboard

> **Monitor. Analyze. Prevent.**

---

# Project Overview

Workplace safety is one of the most critical performance indicators in any organization. While incidents can never be completely eliminated, they can be significantly reduced through timely reporting, continuous monitoring, and data-driven decision-making.

This project presents an interactive **Occupational Health & Safety Analytics Dashboard** developed in **Power BI** to enable management monitor safety performance across departments, sites, and work shifts.

The dashboard consolidates workplace incident records into a centralized reporting solution that enables safety officers and business leaders to identify risk patterns, evaluate safety compliance, measure operational performance, and prioritize preventive actions.

---

# Business Problem

Many organizations collect workplace safety data but struggle to convert it into actionable insights.

Without an integrated reporting solution, management often faces challenges such as:

* Limited visibility into incident trends across departments and sites.
* Difficulty identifying high-risk operational areas.
* Poor monitoring of PPE compliance.
* Delayed identification of safety risks.
* Inability to benchmark safety performance.
* Reactive rather than proactive safety management.

This project addresses these challenges by transforming raw safety records into an executive decision-support dashboard.

---

# Project Objectives

The dashboard was designed to:

* Monitor overall organizational safety performance.
* Measure incident frequency across departments.
* Evaluate Lost Time Injury Frequency Rate (LTIFR/TRIFR).
* Track PPE compliance.
* Analyze lost workdays.
* Compare incident performance across operational sites.
* Monitor near-miss reporting.
* Identify high-risk workers.
* Evaluate training effectiveness.
* Support proactive safety decision-making.

---

# Business Questions Answered

This project answers critical business questions including:

### Executive Management

* How many workplace incidents have occurred?
* Is the organization meeting its safety targets?
* Which departments experience the most incidents?
* Which sites require additional safety intervention?
* How effective is PPE compliance?

### Safety Team

* Which shifts experience the highest incident frequency?
* Which departments lose the most productive workdays?
* Which job roles experience the most incidents?
* Which locations have the highest TRIFR?

### Risk Management

* Which workers fall into high, medium, and low-risk groups?
* Which departments have the highest PPE non-compliance?
* Which sites exceed acceptable noise exposure levels?
* Does employee training reduce workplace risk?

---

# Tools Used

* **Power BI Desktop**
* **Power Query**
* **DAX**
* **Microsoft Excel**
* Data Modeling
* Interactive Bookmarks
* Slicers
* KPI Cards
* Drill-down Visualizations

---

# Data Preparation

The project followed a standard Business Intelligence workflow:

### Data Cleaning

* Removed duplicates
* Corrected inconsistent values
* Standardized department names
* Validated missing values
* Corrected data types

### Data Modeling

Relationships were created across multiple safety-related tables to support cross-filtering and KPI calculations.

---

# Dashboard Pages

---

# 1. Executive Overview

Provides a high-level summary of the organization's safety performance.

## Key Performance Indicators

| KPI                    | Actual Value |           Target / Supporting Metric |
| ---------------------- | -----------: | -----------------------------------: |
| Total Incidents        |       **64** |  Avg Incidents per Worker = **1.28** |
| LTIFR                  |    **194.0** |            LTIFR Benchmark = **3.0** |
| Safety Rate            |    **24.0%** |                                    — |
| Total Near Misses      |       **93** | Near Miss : Incident Ratio = **1.5** |
| Average PPE Compliance |   **78.26%** |               PPE Target = **90.0%** |

---

## Incidents by Department

| Department     | Incidents |
| -------------- | --------: |
| Assembly       |        12 |
| Logistics      |        12 |
| Chemical Plant |         9 |
| Warehouse      |         9 |
| Construction   |         8 |
| Loading Dock   |         6 |
| Maintenance    |         6 |
| Electrical     |         2 |

### Insight

Assembly and Logistics recorded the highest number of incidents, jointly accounting for the largest incident burden across the organization.

---

## Days Lost by Department

| Department     | Days Lost |
| -------------- | --------: |
| Logistics      |        28 |
| Construction   |        17 |
| Warehouse      |        13 |
| Maintenance    |        12 |
| Loading Dock   |        10 |
| Assembly       |         9 |
| Chemical Plant |         7 |
| Electrical     |         1 |

### Insight

Logistics experienced the greatest productivity loss due to workplace incidents, highlighting a need for targeted corrective measures.

---

## Incidents by Site

| Site           | Incidents |
| -------------- | --------: |
| Site B – East  |        18 |
| Site D – South |        17 |
| Site C – West  |        15 |
| Site A – North |        14 |

---

## PPE Compliance by Department

| Department     | Compliance |
| -------------- | ---------: |
| Electrical     |     85.00% |
| Maintenance    |     81.67% |
| Assembly       |     81.29% |
| Construction   |     80.40% |
| Chemical Plant |     79.75% |
| Warehouse      |     76.57% |
| Loading Dock   |     74.33% |
| Logistics      |     72.13% |

### Executive Insights

* The organization recorded **64 workplace incidents**.
* PPE compliance (**78.26%**) remains below the **90% target**, indicating an opportunity to strengthen compliance monitoring.
* The LTIFR of **194.0**, compared with the benchmark of **3.0**, suggests substantial room for safety performance improvement.
* Near-miss reporting (93 cases) demonstrates active reporting but also indicates recurring workplace hazards that require preventive action.

---

# 2. Incident Analysis

This page provides deeper analysis of incident trends across workers, departments, shifts, and locations.

## KPI Summary

| KPI                      | Actual Value |                         Supporting Metric |
| ------------------------ | -----------: | ----------------------------------------: |
| Incidents by Department  |       **64** |                                         — |
| TRIFR                    |    **128.0** |                       Benchmark = **5.0** |
| Total Workers            |       **50** |       Avg Incidents per Worker = **1.28** |
| Total Days Lost          |       **97** |                                         — |
| Workers Below PPE Target |       **37** |                      PPE Target = **90%** |
| Avg Incidents by Shift   |     **1.28** | PPE Target reference displayed = **90.0** |

---

## Incidents by Role

Highest incident roles include:

* Line Operator (10)
* Site Worker (8)
* Lab Technician (7)
* Route Supervisor (5)
* Store Supervisor (5)

This indicates that frontline operational staff experience the highest exposure to workplace hazards.

---

## Average Incidents per Worker by Department

| Department     | Average |
| -------------- | ------: |
| Assembly       |    1.71 |
| Construction   |    1.60 |
| Logistics      |    1.50 |
| Warehouse      |    1.29 |
| Chemical Plant |    1.13 |
| Loading Dock   |    1.00 |
| Maintenance    |    1.00 |
| Electrical     |    0.67 |

---

## Incidents by Shift

| Shift     | Incidents | Percentage |
| --------- | --------: | ---------: |
| Night     |        26 |     40.63% |
| Afternoon |        20 |     31.25% |
| Day       |        18 |     28.13% |

### Insight

Night shift recorded the highest proportion of incidents, suggesting increased operational risk during overnight activities.

---

## TRIFR by Site and Shift

The dashboard compares injury frequency across:

* Site A – North
* Site B – East
* Site C – West
* Site D – South

and across:

* Day
* Afternoon
* Night

Notably:

* Site B – East recorded the highest Afternoon TRIFR (233.3).
* Site A – North showed the highest Night TRIFR (180.0).
* Site C – West recorded elevated Day TRIFR (160.0).

These variations suggest that targeted interventions should be tailored by both site and shift rather than applying uniform safety measures across the organization.

---

# 3. Risk Analysis

The Risk Analysis page focuses on worker risk profiles, environmental hazards, and compliance performance.

## KPI Summary

| KPI                     |   Value |
| ----------------------- | ------: |
| High Risk Workers       |       6 |
| Medium Risk Workers     |      15 |
| Low Risk Workers        |       4 |
| Noise Exceedances       |      25 |
| PPE Non-Compliance Rate |  21.74% |
| Average Noise Level     | 85.5 dB |

---

## Noise Exceedances by Department

| Department     | Count |
| -------------- | ----: |
| Warehouse      |     5 |
| Assembly       |     4 |
| Chemical Plant |     4 |
| Maintenance    |     4 |
| Loading Dock   |     3 |
| Construction   |     2 |
| Electrical     |     2 |
| Logistics      |     1 |

---

## PPE Non-Compliance by Department

| Department     |   Rate |
| -------------- | -----: |
| Logistics      | 27.88% |
| Loading Dock   | 25.67% |
| Warehouse      | 23.43% |
| Chemical Plant | 20.25% |
| Construction   | 19.60% |
| Assembly       | 18.71% |
| Maintenance    | 18.33% |
| Electrical     | 15.00% |

---

## PPE Non-Compliance by Site

| Site           |   Rate |
| -------------- | -----: |
| Site D – South | 29.54% |
| Site C – West  | 20.92% |
| Site A – North | 19.18% |
| Site B – East  | 17.21% |

---

## Risk Level by Average Training Hours

| Risk Level  | Average Training Hours |
| ----------- | ---------------------: |
| Low Risk    |               28.2 hrs |
| Medium Risk |               23.7 hrs |
| High Risk   |               10.8 hrs |

### Insight

Employees with the fewest training hours fall into the highest risk category, reinforcing the importance of continuous safety education.

---

# Key Findings

* The organization recorded **64 workplace incidents** across all departments.
* Assembly and Logistics experienced the highest incident counts.
* Logistics recorded the highest number of lost workdays (28).
* Site B – East experienced the highest number of incidents (18).
* Overall PPE compliance (78.26%) remains below the organizational target (90%).
* Night shift experienced the highest proportion of incidents.
* Warehouse recorded the highest number of noise exceedances.
* Logistics showed the highest PPE non-compliance rate.
* Employees receiving fewer training hours were more likely to fall into the high-risk category.

---

# Recommendations

## 1. Improve PPE Compliance

Focus on Logistics, Loading Dock, and Warehouse through:

* Routine PPE inspections.
* Supervisor accountability.
* Monthly compliance audits.
* Refresher safety training.

---

## 2. Reduce High Incident Areas

Prioritize:

* Assembly
* Logistics
* Chemical Plant

Conduct root-cause investigations and strengthen preventive controls.

---

## 3. Strengthen Shift Safety

Because Night shift recorded the highest incident frequency:

* Increase supervision.
* Improve fatigue management.
* Review staffing patterns.
* Schedule additional toolbox talks.

---

## 4. Reduce Noise Exposure

Introduce:

* Hearing protection programs.
* Noise monitoring.
* Engineering controls.
* Equipment maintenance schedules.

---

## 5. Increase Safety Training

Employees with higher training hours demonstrated lower overall risk.

Recommendations include:

* Quarterly refresher programs.
* Hazard identification workshops.
* Practical emergency response drills.
* Behaviour-based safety initiatives.

---

# Business Impact

This dashboard enables decision-makers to:

* Monitor workplace safety performance in real time.
* Identify high-risk departments and locations.
* Improve PPE compliance.
* Reduce incident frequency.
* Allocate safety resources effectively.
* Support evidence-based safety decisions.
* Transition from reactive incident management to proactive risk prevention.

---

# Conclusion

The **Health & Safety Hub Dashboard** demonstrates how Business Intelligence can transform occupational health and safety management through interactive reporting and actionable insights.

By integrating incident data, safety compliance metrics, environmental risk indicators, and workforce analytics into a single dashboard, stakeholders gain a comprehensive view of organizational safety performance. The dashboard not only identifies where incidents occur but also explains the contributing factors, enabling targeted interventions that reduce workplace risk, improve compliance, and foster a stronger safety culture.

This project showcases the practical application of **Power BI**, **Power Query**, **DAX**, and **data storytelling** to solve real-world occupational health and safety challenges while supporting strategic, data-driven decision-making.

---

# Author

**Cosmos Isuru**
**HSE / Data Analyst**

**Skills Demonstrated**

* Power BI Dashboard Development
* Power Query (ETL)
* DAX Measures & KPI Design
* Data Modeling
* Occupational Health & Safety Analytics
* Risk Assessment & Compliance Reporting
* Data Visualization
* Business Intelligence
* Analytical Storytelling

---

This README is structured to communicate not just what the dashboard shows, but **why it matters**—a quality that hiring managers and recruiters often look for in analytics portfolio projects.
