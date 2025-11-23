# Power BI Report Design Lab 
## 📝 Overview
This repository contains a Power BI report I designed during a guided Skillable virtual lab. As work inside the VM can’t be exported I’ve included a screenshot of the completed report.

While building the report I focused on understanding the reasoning behind each step but why certain visuals suit specific metrics also how slicers and filters shape the user experience and how page layout affects how clearly a report communicates its insights. This lab gave me hands on experience with visual design slicer syncing KPIs and structuring a report to support clear data driven decision making.
## 🎯 Purpose of the Lab
This project helped me develop the foundational skills expected of a junior data analyst including:  
📊 Designing multi page Power BI reports  
📊 Selecting visuals that clearly communicate the right insights  
📊 Applying slicers, filters, and hierarchy drill downs effectively  
📊 Considering the user experience (UX) to make reports intuitive and actionable  
📊 Publishing reports to the Power BI Service and interacting with them for exploration

## 📄 Page 1: Overview Why I Designed It This Way  

This page is all about giving a quick snapshot of sales performance for example if a department was on a deadline and needed the information quickly they’d still get the key story I wanted it to feel intuitive so anyone opening the report knows exactly where to start.  

### ✨ What I Did and Why
#### 💠 Year and Region slicers at the top These are the first thing you see because I wanted people to filter the report right away it makes it easy to focus on exactly what matters without getting lost in the data.
#### 💠 Dropdown for Year Keeps the page clean and saves space while still letting you pick the year it’s simple but practice.  
#### 💠 Line + Column Chart Sales + Profit Margin I paired these because seeing total sales alongside profit margin makes trends obvious immediately you can spot patterns month to month without hunting for details.  
#### 💠 Show months with no data Missing months can trick you into thinking nothing happened I made sure the timeline stays complete so the story is accurate.  
#### 💠 Stacked Column Chart by Region & Category Highlights which products are driving sales in each region it’s easy to compare categories and spot standout performers.  
#### 💠 Stacked Bar Chart for Quantities Horizontal bars just make reading category labels easier and give a quick sense of demand across products.  
Overall this page answers the question of how the team is doing overall and what needs to be seen first. 

## 📄 Page 2: Profit Why I Designed It This Way  

This page focuses on the financial side of the dataset my goal was to create a layout that makes it easy to break down profitability and understand how different parts of the business contribute over time.

### ✨ What I Did and Why  
💠 **Matrix with Fiscal Hierarchy**  I chose a matrix because it allows users to move naturally from year → quarter → month it gives a structured layered view of performance without crowding the page.  
💠 **Multiple measures Sales, Cost, Profit, Margin, Orders**  Profitability depends on more than revenue so I included the key measures needed to get a complete financial overview in one place.  
💠 **Page level Product Filters Category, Subcategory, Product, Colour**  I kept these off the main canvas to maintain a clean layout but they’re available for anyone who wants to drill into specific products or groups.  
💠 **Region slicer placed vertically** This positioning keeps the layout consistent and supports a logical top to bottom flow for filtering.  

Overall this page is designed to answer where are we generating profit and how does that change over time.

## 📄 Page 3: My Performance Why I Designed It This Way  

This page is designed to reflect what a salesperson would see in a real reporting environment using row level security the goal was to create a clear focused view of individual performance without distractions.

### ✨ What I Did and Why  
💠 Page level filter for a single salesperson this simulates how row level security works in real dashboards showing only the data that person is allowed to view it helps demonstrate how a personalised performance page would function in practice.  
💠 Multi Row Card for key KPIs Sales, Targets, Variance, Margin  These metrics needed strong visibility so I increased the font size and added a subtle background to make the KPIs stand out immediately.  
💠 Monthly Sales vs Target visuals Bar + Column I used two visual types to present the same information because people interpret data differently showing both makes it easier for users to spot gaps between performance and targets.  
💠 Dropdown slicer for Year Keeps the layout clean while allowing quick comparisons across different time periods.  

Overall this page is built to answer the question how are the team performing compared to their targets

## 🔄 Syncing Slicers Why This Matters  

Syncing the Year and Region slicers across pages was an important step in making the report feel consistent and reliable. If slicers aren’t synced users can end up comparing pages that are filtered differently without realising it which leads to confusion and inaccurate conclusions.

By syncing the slicers the entire report responds to the same selections it creates a smoother user experience and reduces the chance of misinterpretation but reflects the level of thoroughness expected in real world Power BI reporting.

## ☁️ Power BI Service Publishing & Interaction  

Once the report was complete I published it to the Power BI Service to see how it behaves from an end user perspective this step is important because a report can look great in Desktop but feel completely different once real users start interacting with it.

In the Service I tested how the report responds to:

💠 Cross filtering and visual interactions  
💠 Highlighting behaviour across charts  
💠 Focus Mode for inspecting visuals in detail  
💠 Tooltip insights and drill context  
💠 Full screen presentation mode  
💠 Page navigation and synced slicer behavior  

Working through this helped me understand how design decisions like layout filter placements and visual type directly impact usability in a real business environment it’s a practical step that connected the design process to the actual user experience.

## 🧩 Skills Demonstrated  

💠 Structured report layout and planning with a focus on usability  
💠 Selecting visuals that match the metric and the business question  
💠 Building and formatting KPIs including variance and margin analysis  
💠 Applying slicers filters hierarchies and synced logic for consistent reporting  
💠 Designing drill down paths and matrix views for multi level analysis  
💠 Publishing to the Power BI Service and validating the end user experience  
💠 Understanding how real users interact with dashboards and adjusting design accordingly  

These are core skills expected from a junior data analyst and this project helped me apply them in a practical hands on way that mirrors real reporting scenarios.

<img width="378" height="236" alt="image" src="https://github.com/user-attachments/assets/c2a02ce9-3d2c-4e2d-aa09-af4a35e4c8f3" />

<img width="378" height="236" alt="image" src="https://github.com/user-attachments/assets/6cd7bb82-ef2e-4873-87d7-12587df9e9a7" />






























