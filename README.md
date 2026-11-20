# Football Scouting and Performance Analysis Using SQL

## Project Overview

This project explores football player performance using PostgreSQL. The objective is to analyse player statistics, evaluate attacking contributions, compare club performance, and demonstrate SQL techniques used in football data analysis.

## Tools Used
- PostgreSQL
- pgAdmin 4
- SQL
- GitHub

## Database Overview

The database contains four main tables:

- `clubs` – club information.
- `players` – player information and club associations.
- `matches` – match information.
- `player_match_stats` – individual player match statistics, including goals and assists.

## Analysis Performed

### Basic Analysis
- Total goals and assists.
- Individual player goal contributions.
- Top players ranked by goal contributions.
- Club-level goal analysis.
- Match-level goal analysis.

### Advanced Analysis
- Player rankings using `RANK()`.
- Percentage contribution to total team goals.
- Identification of players performing above the average using Common Table Expressions (CTEs).

## Key Findings

Based on the sample dataset:

| Metric | Result |
|---|---:|
| Players | 7 |
| Clubs | 5 |
| Matches | 5 |
| Match-stat records | 10 |
| Total goals | 12 |
| Total assists | 7 |
| Goal contributions | 19 |

### Top Goal Contributors

| Player | Goals | Assists | Contributions |
|---|---:|---:|---:|
| James Carter | 3 | 2 | 5 |
| Kevin Adams | — | — | 4 |
| Lucas Garcia | — | — | 3 |

James Carter recorded the highest goal contribution with five contributions.

## SQL Skills Demonstrated

- SELECT statements
- Aggregate functions: SUM(), AVG(), COUNT()
- GROUP BY and ORDER BY
- INNER JOIN and LEFT JOIN
- Subqueries
- Common Table Expressions (CTEs)
- Window functions
- RANK()
- ROUND()
- LIMIT

## Project Structure

```text
football-scouting-sql-analysis/
├── 01_database_setup.sql
├── 02_data_exploration.sql
├── 03_basic_analysis.sql
├── 04_advanced_analysis.sql
└── README.md
```

## Limitations

This project uses a small sample dataset. The findings demonstrate SQL analysis techniques and should not be interpreted as real-world player performance assessments.

## Future Improvements

- Expand the dataset with real football statistics.
- Analyse defensive performance.
- Compare player performance across multiple seasons.
- Build interactive dashboards using Power BI.

