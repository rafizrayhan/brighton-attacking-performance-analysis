# Brighton & Hove Albion | Attacking Performance Analysis (2024/25)

## Project Overview

This project explores Brighton & Hove Albion's attacking performance during the 2024/25 English Premier League season using Python-based data analysis and visualisation.

It was developed as an **independent practice exercise for the pre-master's Python module at Sports Data Campus**, as part of my MSc Data Analytics in Football learning journey.

The primary objective was to apply foundational Python, pandas, Matplotlib and Seaborn skills to real football data while developing my ability to interpret statistics from a football performance analysis perspective.

**Project type:** Educational / Independent Practice  
**Level:** Beginner  
**Tools:** Python, pandas, Matplotlib, Seaborn, Google Colab  
**Dataset:** FBref-derived Premier League 2024/25 player statistics

## Objectives

The project investigates three questions:

1. Who were Brighton's leading Premier League goalscorers during the 2024/25 season?
2. How were goals distributed across different playing positions?
3. How did Brighton's forwards compare with forwards from other Premier League clubs in terms of goals scored per 90 minutes?

## Methodology

The analysis was conducted using Python in Google Colab.

The workflow involved:

- Loading and exploring Premier League player statistics using pandas.
- Filtering Brighton players and selecting relevant performance metrics.
- Ranking players according to goals scored.
- Aggregating goals by playing position.
- Filtering forwards who played at least 900 minutes.
- Comparing Brighton forwards against forwards from other Premier League clubs.
- Creating bar charts, pie charts and box plots.
- Calculating descriptive statistics to support the visual findings.

## Visualisations

### 1. Top 10 Goalscorers

A horizontal bar chart displaying Brighton's ten leading Premier League goalscorers.

João Pedro, Kaoru Mitoma and Danny Welbeck were joint-leading goalscorers with 10 goals each.

### 2. Goals by Playing Position

A pie chart showing the distribution of Brighton's player-credited goals across positional groups.

- Forwards: 60.9%
- Midfielders: 29.7%
- Defenders: 9.4%

### 3. Goals per 90 — Brighton vs Other Premier League Forwards

A Seaborn box plot comparing the goals-per-90 distributions of Brighton forwards with forwards from other Premier League clubs.

Players with fewer than 900 minutes were excluded.

| Metric | Brighton | Other PL Clubs |
|---|---:|---:|
| Players | 5 | 72 |
| Mean goals per 90 | 0.338 | 0.317 |
| Median goals per 90 | 0.35 | 0.31 |
| Standard deviation | 0.120 | 0.184 |

## Key Findings

- Brighton's three leading goalscorers contributed 30 of the club's 64 player-credited league goals.
- Forwards accounted for approximately 61% of Brighton's player-credited goals.
- Brighton's qualifying forwards recorded a slightly higher median goals-per-90 rate than the comparison group (0.35 versus 0.31).
- Brighton's forward scoring rates showed less dispersion, although the small sample size limits the strength of this observation.
- Some forwards from other Premier League clubs achieved substantially higher individual scoring rates.

## Limitations

This is an introductory descriptive analysis, not a comprehensive assessment of Brighton's attacking tactics or player quality.

The study has several limitations:

- Only one Premier League season was analysed.
- The Brighton comparison group contained just five qualifying forwards.
- The 900-minute threshold excludes players with limited playing time.
- Positional classifications may not fully represent players' tactical roles.
- Goals per 90 does not account for chance quality, penalty responsibilities or tactical context.
- Player observations are equally weighted, regardless of minutes played above the threshold.
- The analysis does not establish statistical significance or causation.

## Learning Outcomes

Through this project, I practised:

- Data filtering and manipulation using pandas.
- Conditional grouping and aggregation.
- Descriptive statistical analysis.
- Horizontal bar chart creation with Matplotlib.
- Pie chart visualisation.
- Box plot creation with Seaborn.
- Interpreting football performance statistics.
- Communicating analytical findings and limitations.

## Future Improvements

As I progress through my MSc Data Analytics in Football, I intend to develop more advanced projects involving expected goals (xG), event data, tactical analysis, player recruitment and performance modelling.

## Acknowledgements

This project was developed independently as a practical application of concepts studied during the Sports Data Campus pre-master's Python module.

**Data source:** FBref-derived Premier League 2024/25 player statistics.

**Disclaimer:** This is an educational project and is not affiliated with Brighton & Hove Albion, the Premier League or Sports Data Campus.
