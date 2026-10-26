# Hertz-style Revenue Management EDA (Synthetic Data)

All records are fictional; not actual Hertz data. Pickup dates: 2025, five Florida airport markets.

## Exercises
1. Calculate completed rentals, transaction days, revenue, and RPD by month and location.
2. Identify months where rental count increases but revenue decreases. Explain the drivers.
3. Calculate daily fleet utilization from occupied_vehicle_days / available_vehicles. Investigate flagged over-capacity rows.
4. Calculate monthly RPU using revenue divided by average daily fleet size.
5. Compare revenue, rental duration, and discounts by vehicle category and segment.
6. Analyze cancellation and no-show rates by booking channel and lead time.
7. Identify seasonal patterns and build a rolling 7-day revenue trend.
8. Estimate contribution as total_revenue minus estimated_variable_cost.
9. Create a five-KPI dashboard for an airport manager.
10. Write a management recommendation supported by at least three findings.

## Caveats
Revenue is attributed to pickup date, not recognized daily. Canceled reservations have planned rental_days. Occupancy is counted on overlapping completed rentals; independent simulated supply can produce over-capacity rows (flagged), intentionally useful for data-quality checks. Observational pricing patterns do not establish causal price elasticity. RPD is simplified, not Hertz's externally adjusted metric. Costs are synthetic variable costs, not accounting profit.
