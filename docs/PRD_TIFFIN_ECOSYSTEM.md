# Product Requirements Document (PRD): Zomato Tiffin Ecosystem

**Project**: Zomato Tiffin Aggregation, NutriTiffin & Cloud Kitchen Network  
**Author**: Ayush Shah (Lead Product Strategist)  
**Team**: STRATELLERS — IIT (BHU) Varanasi (Ayush Shah, Aarya Pawar, Soumya Kumari, Hardik Goyal)  
**Platform**: Android & iOS (Consumer & Merchant Apps), Web  

---

## 1. Objective & Success Metrics
Enable seamless discovery, subscription, and delivery of hygienic, homemade-style meals by onboarding 8,000+ local tiffin service providers and establishing pre-certified cloud kitchen franchises.

### Key Metrics
- **North Star**: Total Tiffin Meals Delivered per Month.
- **Acquisition**: 20%–30% new consumer acquisition uplift.
- **Retention**: 70%+ month-over-month subscription renewal rate.
- **Hygiene Compliance**: 100% FSSAI-verified vendors.

---

## 2. Epics & User Stories

### Epic 1: NutriTiffin Goal-Based Subscription
- **US-1.1**: As a health-conscious corporate employee, I want to input my BMI, dietary preference (low carb, keto, high protein), and health goal so that I receive personalized weekly meal suggestions.
- **US-1.2**: As a subscriber, I want to view detailed macro breakdown (calories, protein, fats, carbs) for each daily tiffin delivery.
- **US-1.3**: As a Jain/Vegan consumer, I want strict dietary filters that ensure zero cross-contamination.

### Epic 2: Flexible Cancellation & Waste Recovery
- **US-2.1**: As a subscriber, I want to cancel a scheduled meal up to 12 hours in advance and receive a 100% wallet refund without vendor friction.
- **US-2.2**: As a subscriber canceling within 12 hours, I want a tiered partial refund with the option to list the meal as a "Last-Minute Deal" or donate it via Zomato Feeding India to an NGO.
- **US-2.3**: As a donor, I want a digital donation certificate and NGO acknowledgment receipt confirming my meal went to a person in need.

### Epic 3: VendorVision AI Business Co-Pilot
- **US-3.1**: As a tiffin cook, I want to speak or type questions in Hindi/English (e.g. *"Kal kitna lunch demand aayega?"*) and get predictive demand forecasts based on weather and historical data.
- **US-3.2**: As a vendor, I want automated menu optimization recommendations based on customer ratings and ingredient cost fluctuations.

### Epic 4: Hyperpure Supply Chain & Sustainable Packaging
- **US-4.1**: As a home cook, I want 1-click recurring raw material procurement delivered by 6:00 AM daily via Zomato Hyperpure at wholesale bulk rates.
- **US-4.2**: As a vendor, I want standardized biodegradable heat-retaining containers with alphanumeric customization stamps (e.g. `B +1`, `S`).

---

## 3. Non-Functional Requirements (NFR)
- **Temperature Maintenance**: Insulated transit must keep core meal temperatures above 60°C for up to 90 minutes.
- **Latency**: VendorVision LLM natural language queries must return formatted SQL response within < 1.8 seconds.
- **Scalability**: Capable of digesting 1.4 Million meal orders simultaneously across peak lunch windows (11:30 AM – 1:30 PM).
