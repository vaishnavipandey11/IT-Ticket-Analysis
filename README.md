# 🎯 IT Ticket Analysis 
https://github.com/user-attachments/assets/3dd6f5f5-e520-45e0-94c8-81be6ba00f24

# [IT Ticket Analysis Drive Link](https://drive.google.com/drive/folders/1YD2kHOpOA9RCgwAgXJfdI_ZXa28Nl2CV?usp=drive_link)

This repository showcases a complete data analytics project built entirely in Microsoft Excel. It explores 97,498 IT helpdesk tickets spanning five years (2016–2020) to assess service performance, monitor agent efficiency, and generate insights for continuous improvement.
The final output is a fully interactive, multi-sheet Excel dashboard tailored for management to track KPIs, analyze performance trends, and make informed decisions.
  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---
# 📘 Project Summary:

The goal of this project is to perform an in-depth analysis of IT support operations to highlight efficiency patterns, recurring issues, and optimization opportunities.

# Core Objectives

. Evaluate helpdesk performance by studying ticket volumes and resolution times.

. Compare and rank agent performance to highlight top achievers and identify training needs.

. Detect patterns in workload, severity, and categories to understand business impact.

. Identify mismatches between ticket severity and assigned priority.

. Recommend improvements in automation, staffing, and workflow.

. Deliver an interactive dashboard for real-time monitoring and management insights.
  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---
# 📂 Datasets Used:

Tickets Dataset (97,498 records):
Includes details such as Ticket ID, Request Category, Issue Type, Severity, Priority, Resolution Time (days), Satisfaction Score, and Date.

IT Agents Dataset (50 agents):
Covers agent-level details including Agent ID, Name, Email, and Date of Birth.
  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---
# 🧩 Methodology

The analysis followed a systematic Excel-based workflow:

# 1️⃣ Data Cleaning

. Corrected over 50,000 inconsistent text entries (e.g., “Mayor” → “Major”, “Unassiged” → “Unassigned”).

. Verified integrity to ensure no missing values in key columns.

# 2️⃣ Feature Engineering

. Calculated Agent Age from Date of Birth using Excel date functions.

. Extracted Email Domains using text formulas (LEFT, RIGHT, LEN, FIND).

. Added helper columns to simplify later analysis.

# 3️⃣ Data Analysis

. Used Pivot Tables to summarize data by time, category, and agent.

. Combined datasets using VLOOKUP and INDEX-MATCH.

. Conducted correlation analysis (CORREL) between Severity and Resolution Time.

. Identified temporal trends through daily, monthly, and quarterly breakdowns.

# 4️⃣ Visualization & Dashboard

. Built a dynamic, dark-themed dashboard with multiple tabs.

. Used Slicers and Timelines for interactive filtering.

. Created Bar, Line, Pie, and Combo Charts to display KPIs effectively.
  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---
# 📊 Key Insights:

. Priority Mismatch: 82% of tickets showed inconsistency between severity and priority, with 32K “Normal” tickets incorrectly marked “High.”

. Category Delays: Hardware (7.63 days) and System (6.62 days) issues took 25× longer than Login-related tickets (0.31 days).

. Static Performance: Ticket volumes rose 123%, but average resolution time (4.55 days) remained unchanged — signaling a need for smarter processes, not just more staff.

. Positive User Sentiment: Despite delays, satisfaction ratings improved steadily, reaching an average of 4.10/5.

. Performance Gaps: Agents like Diana Rojo and Jesus Grajeda were top performers, while others such as Lorena and Elena Velez need targeted training.
  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---
# 🚀 Recommendations

Automation: Configure automatic ticket prioritization to fix the 82% mismatch and reduce manual workload.

Skill Enhancement: Conduct focused training for underperforming agents based on data insights.

Process Optimization: Automate repetitive requests (e.g., Login Access) to allow agents to focus on high-impact categories like Hardware and System issues.

# ⚙️ Tools & Techniques

Tool Used: Microsoft Excel

Key Functions: VLOOKUP, INDEX/MATCH, IF (Array), DATE, TODAY, INT, TEXT, LEFT/RIGHT/FIND/LEN, CORREL, AVERAGE.

Excel Features: Pivot Tables, Pivot Charts, Slicers, Timelines, Interactive Dashboards.

Concepts Applied: Data Cleaning, Feature Engineering, Trend & Correlation Analysis, KPI Visualization.
  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---
# 📦 Repository Contents

IT Ticket Analysis.xlsx → Final interactive Excel dashboard

DOc Task.docx → Supporting documentation with analysis breakdown

Project Presentation.pptx → Presentation summary of findings

Dashboard MP4.mp4 → Dashboard demo video

Dashboard 1,2,3,4 → Snapshot of final dashboard
  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---  ---
# 👩‍💻 Author
Vaishnavi Pandey
