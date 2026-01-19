# travel-tide-customer-mastery-project # # TravelTide Customer Mastery Project

### Objective
Apply customer segmentation to behavioral travel data to identify meaningful personas and assign perks that improve retention, conversions, and loyalty outcomes.

This project simulates work done in a travel rewards product team (e.g., Expedia, Booking, Hopper, or airline loyalty).

---

##  Dataset
Aggregated user-level features across:
- browsing sessions
- bookings (flight + hotel)
- cancellation behavior
- discount usage
- monetary value (base fare + hotel spend)

Single cohort: **users active Jan 2023**

---

##  Method Overview (Compressed)

1. **Exploration**
   - Distribution & skew checks
   - Cancellation patterns
   - Discount responsiveness
   - Browsing depth (clicks + duration)

2. **Feature Selection**
   Focused on interpretable, actionable marketing dimensions:
   - Frequency (sessions, trips)
   - Monetary (value score)
   - Price sensitivity (discount affinity)
   - Flexibility (cancellations)
   - Conversion signals (flight + hotel)

3. **Clustering**
   Tableau K-Means (auto k-selection → k=3) + qualitative validation

4. **Persona Translation**
   Clusters converted into business-facing segments

5. **Perk Mapping**
   Per persona → perk with clear economic logic

---

##  Final Personas (Compressed)

| Persona | Defining Traits | Behavior Logic


---

##  Business Value

Implementing segmentation enables:
- targeted perk allocation
- improved conversion
- reduced rebooking friction
- loyalty uplift for high-value travelers

---

##  Limitations (Compressed)

- single-month cohort
- trip purpose not modeled
- no unit economics on margin
- no seasonality / elasticity testing

---

## 🔜 Next Enhancements

- A/B testing of perk assignment
- revenue impact modeling
- sentiment + survey integration
- multi-month cohort trend analysis

