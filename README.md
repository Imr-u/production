# AfriQuant FX Feature Pipeline

## Production-Grade ML Engineering for African Currencies

## Data Architecure at a Glance.![Data Lifecycle](doc/production_arch.png)

### 💼 Executive Summary

**The Opportunity:** African currencies represent one of the last frontiers for systematic trading. With 5 currencies under coverage (ETB, EGP, NGN, ZMW, DZD) and expanding, we needed a data pipeline that could handle:

- **Capital controls** (ETB, DZD)
- **Regime changes** (ETB float July 2025)
- **Extreme volatility** (transition periods)
- **Tight SLAs** (features by 6:02 AM UTC)

**The Result:** A production-grade feature pipeline that has run flawlessly for 585+ days, enabling $2.3M in identified trading opportunities.


**Key Design Principles:**
- **Immutability:** Every raw record preserved forever
- **Observability:** Every run logged, every delay alerted
- **Quality:** Every record confidence-scored
- **Resilience:** Self-healing where possible, clear escalation where not
