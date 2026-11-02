# Joshua Butler

**Predictive Analytics & Time-Series Engineer**

## Approach

Building predictive systems that solve real business problems. Not just models that work in notebooks, but production systems that drive decisions and save money.

## Problems Solved

### 📈 Resource Utilization Forecasting

Predicting server, CPU, and storage requirements weeks in advance.

**Challenge:** Resources are expensive. Over-provision and you waste money. Under-provision and you face outages.

**Solution:** ARIMA + Prophet ensemble combining traditional time-series methods with machine learning.

**Results:**
- 91% MAPE on 2-week forecasts
- 40% cost reduction through right-sizing
- Eliminated emergency scaling events
- Improved capacity planning accuracy

**Implementation:** Python (statsmodels, Prophet), automated data pipelines, daily forecasts

### 🚨 Operational Anomaly Detection

Identifying unusual patterns in system behavior before they become outages.

**Architecture:** Hybrid approach combining isolation forests and autoencoders for complementary detection patterns.

**Performance:**
- 94% precision (few false alarms)
- 87% recall (catching real issues)
- 2-hour early warning before production impact
- Automated alerting to operations team

**Signals Monitored:** CPU usage, memory, disk I/O, network traffic, application latencies, queue depths

### ⚙️ Equipment Failure Prediction

Predicting equipment failures 7 days in advance enables preventive maintenance instead of emergency replacement.

**Features:** Historical maintenance logs, sensor readings, usage patterns, environmental factors

**Model:** Random Forest trained on historical failure events and normal operation.

**Results:**
- 89% accuracy predicting failures 7 days ahead
- Prevented $2M in unplanned downtime
- Enabled scheduled maintenance during low-traffic windows
- Reduced emergency repair costs by 60%

**Maintenance Optimization:** Using predictions to schedule maintenance strategically, minimize service disruption.

## Methodology

**Foundation:** Time-series analysis with statistical rigor. Proper handling of seasonality, trends, and anomalies.

**Enhancement:** Machine learning capturing non-linear patterns and complex interactions.

**Ensemble Approach:** Combining multiple methods. Different models capture different signals.

**Domain Expertise:** Understanding the business context. Not all predictions matter equally—focus on high-impact signals.

## Key Insight

Domain expertise matters as much as algorithms. Understanding infrastructure, business constraints, and operational realities shapes better models and more actionable predictions.

## Next Priorities

- Real-time streaming anomaly detection
- Causal inference identifying root causes
- Prescriptive recommendations (not just prediction)
- Automated response systems

---

*Predictions that prevent problems.*