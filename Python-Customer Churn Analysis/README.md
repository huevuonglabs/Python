# 📊 Crypto User Growth Analysis

## 1. Business Problem & Objective

Crypto exchanges face high user churn driven by short-term speculative behavior and inconsistent engagement.
The objective of this project is to **identify behavioral differences between churned and retained users** and uncover **actionable signals that explain long-term retention**, using user-level activity and trading data.

---

## 2. Dataset Description

* ~15,000 users
* 30-day activity window
* One row per user
* ~5% missing churn labels (random, unbiased)

The dataset captures:

* **Engagement**: sessions, activity days, time spent
* **Trading behavior**: transactions, trade days, volume, fees
* **Product usage**: advanced features (staking, margin, futures)
* **Breadth of usage**: asset diversification
* **Platform**: iPhone vs Android

---

## 3. Key Insights

* **Consistency beats intensity**
  Churned users trade ~2.5× more volume per trade day, but retained users trade across more days and sessions. Retention is driven by habitual engagement, not aggressive trading bursts.

* **Frequency matters more than session length**
  Session duration is similar across groups, but retained users open the app more than twice as often.

* **Advanced features improve retention beyond the median**
  The median user is a spot trader, but advanced feature adoption is significantly higher among retained users, indicating stronger retention among highly engaged users.

* **Asset diversification is associated with retention**
  Retained users trade a broader set of assets, suggesting deeper platform exploration and commitment.

* **Device type does not impact churn**
  iPhone and Android users exhibit nearly identical churn patterns.
* **Device influences engagement, not retention**
  A/B testing shows iPhone users execute ~14% more transactions on average (statistically significant), suggesting platform differences impact engagement intensity and monetization potential, but not churn.
---

## 4. Recommendations

* Design for **frequent, low-friction engagement**, not high-intensity trading
* Encourage **safe asset exploration** through recommendations and watchlists
* Promote **advanced features** to already-engaged users, not at onboarding
* Optimize onboarding for **habit formation**, not immediate trading volume
* Run targeted **UX experiments on Android** (eg: reduce clicks, simplify tradeflow) to close the transaction gap and increase evenue per user

---
