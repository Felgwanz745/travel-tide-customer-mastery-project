# Methodology (Technical Detail)

## 1. Cohort Construction
The analysis uses a January 2023 active-user cohort filtered by:
- session count ≥ 7 (removes one-off/noise users)
- ensures behavioral signals are stable

## 2. Feature Engineering
Key engineered dimensions:

**Frequency**
- sessions_count
- trips_count

**Monetary**
- base_fare + hotel_spend combined into value_score

**Elasticity / Price Sensitivity**
- discount_affinity = discounted bookings + discount browsing

**Flexibility**
- cancellation_count
- cancellation_rate

**Engagement**
- page_clicks
- average_session_duration

## 3. Clustering
Algorithm: Tableau built-in K-Means  
Distance: Euclidean, standardized

k determined via:
- silhouette proxy
- inertia elbow
- domain interpretability

k=3 yielded stable, interpretable personas

## 4. Persona Translation
Cluster → persona → perk mapping prioritizes:
- behavioral economics
- loyalty program mechanics
- churn risk vs. value tradeoffs
