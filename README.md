# HR Analytics Dashboard — NorthPeak Solutions

## Problem

NorthPeak Solutions (a fictional company built on the IBM HR Analytics dataset — 1,470 employees, 35 variables) was losing 16.1% of its workforce annually, costing an estimated **$7M per year** in replacement costs. The data existed only as flat spreadsheet rows — no way to see which departments were most affected, whether pay or satisfaction was driving people out, or which employees were at the highest risk of leaving next.

## Approach & Thinking

I split the analysis into 4 focused dashboard pages instead of one crowded view — **Overview, Attrition, Compensation, and Satisfaction** — so each page answers one specific business question. I built DAX measures to calculate attrition rate, average tenure, and satisfaction scores dynamically, with cross-filtering by Department, Job Role, Gender, and Age Band so any slice of the workforce can be isolated instantly. I chose a dark neon theme to make the dashboard visually distinct as a portfolio piece.

## Result

A 4-page interactive Power BI dashboard with dynamic DAX measures, cross-page filtering, and a distinct dark neon visual identity — plus a data-driven recommendations panel translating the numbers into concrete actions.

## What We Found & Impact

- **Sales Representatives had the highest attrition of any role — 39.8%**, nearly 4x higher than most other roles, driven largely by a compensation gap
- Employees who left earned an average of **$4.79K/month vs $6.83K for those who stayed** — a ~30% pay gap that strongly correlates with attrition
- **Overtime employees left at 30.5% vs 10.4%** for those without overtime — one of the strongest predictors in the dataset
- **HR had the lowest job satisfaction score (2.60)** of any department — and the second-highest attrition rate (19%)
- Identified **97 high-risk employees** (short tenure + low satisfaction) who could cost the company 3x more if lost, compared to earlier retention

These findings turned a vague "why are people leaving" question into 4 specific, actionable recommendations for leadership — including a compensation review for Sales roles and a targeted retention plan for the 97 flagged employees.

## Tools & Methods

Power BI · DAX · Power Query · Data Modeling · IBM HR Analytics Dataset
