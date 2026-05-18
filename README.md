# 📚 Personal Study Analytics Dashboard

A 30-day personal study habit analysis using data visualization and basic analytics techniques.

## Overview

This project explores patterns in personal productivity by analyzing study sessions across subjects, locations, and devices. The goal is to understand how various factors influence focus and study efficiency.

## Dataset

The dataset covers 30 days of study sessions with the following fields:

| Column | Description |
|---|---|
| `Date` | Date of study session |
| `Start Time` | Session start time |
| `End Time` | Session end time |
| `Subject` | Subject studied (Chemistry, Computer Science, Mathematics, Physics) |
| `Study Hours` | Total study duration |
| `Break Time Minutes` | Break duration between sessions |
| `Focus Score` | Self-evaluated focus level (1–10) |
| `Study Location` | Room, LRC, or Swadhyay |
| `Device Used` | Laptop or iPad |

## Visualizations

The following charts were created for analysis:

1. **Total Study Hours by Subject** – Bar chart comparing time spent per subject
2. **Time vs Focus Score Heatmap** – Daily study hours mapped against focus scores
3. **Focus Score Trend Over Time** – Line chart tracking focus across 30 days
4. **Location vs Focus Score Heatmap** – Average focus score per subject per location
5. **Device vs Average Focus Score** – Comparison of laptop vs iPad focus scores
6. **Study Hours Distribution by Location** – Pie chart of time spent at each location

## Key Findings

- **Best location:** LRC produced the highest average focus scores (8.8 for Mathematics)
- **Most studied subject:** Mathematics and Physics required the most total hours
- **Best device:** Laptop sessions yielded slightly higher focus scores than iPad sessions
- **Focus pattern:** Longer study sessions correlated positively with higher focus scores
- **Location split:** Room accounted for 54.6% of study time, LRC for 31.7%, and Swadhyay for 13.7%

## Recommendations

Based on the analysis:
- Prioritize **LRC or Swadhyay** over Room for focused study sessions
- Use a **laptop** for longer, concentration-heavy sessions
- Maintain **moderate session lengths** with controlled breaks to sustain productivity

## Tools Used

- Python (pandas, matplotlib, seaborn)
- Data visualization and analytics techniques
