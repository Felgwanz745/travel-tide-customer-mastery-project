
# TravelTide Customer Segmentation — Mastery Project

This project explores how a travel platform could allocate the **right perks to the right customers** by translating behavioral data into **personas** and then into **reward strategies**.

It acts as a hybrid between a **product case study** and a **data segmentation notebook**, combining:
- behavioral analytics
- clustering
- persona design
- loyalty & perk strategy

---

##  Business Objective

TravelTide wants to answer a core business question:

> *"Which perk should we offer to each customer to increase retention, bookings, and loyalty?"*

This implies a need to:
1. understand user behavior
2. segment the cohort
3. translate clusters into personas
4. assign perks that change behavior

---

##  Analytical Approach

The data pipeline followed this sequence:

1. **Feature Engineering**  
   (frequency, spend, cancellations, discount affinity)

2. **User Aggregation**  
   session → user-level dataset for segmentation

3. **Clustering**  
   Tableau’s built-in K-Means clustering used to find natural groups

4. **Persona Mapping**  
   Clusters → Personas → Perk Fit

5. **Marketing / Loyalty Layer**  
   Output expressed in business vs. technical language

Full technical details documented here:  
 `docs/methodology.md`

---

##  Personas Identified (Hybrid Output)

The segmentation revealed **three meaningful personas**:

### **1. Frequent Traveler**
- High spend, repeat bookings
- Predictable patterns, low elasticity  
**Perk Fit:** Priority perks / tiers / upgrades  
*Behavior Change Goal:* Retain & reward

---

### **2. Deal Seeker**
- High discount engagement
- Flexible; browses deeply before converting  
**Perk Fit:** Discounts / alerts / promos  
*Behavior Change Goal:* Lift conversion

---

### **3. Canceller**
- High cancellation rates
- Uncertain travel intent / plan volatility  
**Perk Fit:** Flexible cancellation / rebook perks  
*Behavior Change Goal:* Reduce churn

Full persona notes:  
 `docs/personas.md`

---

## Perk Recommendation Mapping

| Persona | Proposed Perk | Expected Impact |
|---|---|---|
| Frequent Traveler | Priority / Loyalty | Retention |
| Deal Seeker | Discounts / Alerts | Conversion |
| Canceller | Flexible Rebooking | Churn Reduction |

---

## Tableau Dashboard

Interactive segmentation dashboard & mapping:

 `/tableau/`  
Includes:
- `TravelTide_Segmentation.twbx` (interactive)
- screenshot for static view

Dashboard lets stakeholders:
✔ explore clusters  
✔ inspect personas  
✔ test perk fits  
✔ view behavior → strategy mapping  

---

##  Repository Structure



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

##  Next Enhancements

- A/B testing of perk assignment
- revenue impact modeling
- sentiment + survey integration
- multi-month cohort trend analysis
  
---

##  Data Summary

Dataset includes user-level behavioral metrics:
- booking frequency & spend
- cancellations
- discount usage
- engagement depth
- travel activity

---

##  Next Steps (Business & Technical)

**Business**
- integrate seasonality
- test perk elasticity
- measure uplift via A/B test

**Technical**
- experiment with DBSCAN / GMM
- add trip-purpose feature
- rerun on larger cohorts

---

##  Takeaways (Hybrid Messaging)

This project demonstrates the ability to:
> *convert raw behavioral data into actionable commercial strategy*

Useful for roles in:
- Product / Growth
- Loyalty / Pricing
- Data & Analytics
- Strategy

---


