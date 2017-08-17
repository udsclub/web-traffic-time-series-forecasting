# Experiments and Results

Test dates: 10-09-2016 – 10-11-2016
Metrics: [SMAPE](https://en.wikipedia.org/wiki/Symmetric_mean_absolute_percentage_error)
***
## Last day prediction
**Test** – 54.44%
***
## Median (last 30 days)
**Test** – 50.54%
***
## LightGBM
1. <br>
**Features:** 30 lags, month, day, day of week <br>
**Test (subset)** - 49.29% (49.26%)
***
2. <br>
**Features:** 30 lags, month, day, day of week, lang, Project, Access, Agent
**Test (subset)** - 49.99%

