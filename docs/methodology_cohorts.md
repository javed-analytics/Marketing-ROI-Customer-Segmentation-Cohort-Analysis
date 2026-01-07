# Methodology — Cohort Analysis

## Cohort Definition
Customers are grouped by acquisition month derived from `Dt_Customer`.

## Value Metrics
- New customers per cohort
- Cohort value (sum of MntTotal)
- Average value per customer
- Value index relative to overall average

## Engagement Metrics
Due to the absence of transaction timestamps, engagement is measured using recency:
- **Active Rate**: Recency ≤ 30 days
- **At-Risk Rate**: Recency ≥ 90 days

## Interpretation
Older cohorts accumulate higher lifetime value, while newer cohorts exhibit stronger short-term engagement.
