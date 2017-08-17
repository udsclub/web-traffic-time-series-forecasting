# Experiments and Results

Test dates: 10-09-2016 – 10-11-2016
Metrics: [SMAPE](https://en.wikipedia.org/wiki/Symmetric_mean_absolute_percentage_error)
***
## Last day prediction
**Test** – 54.44% <br>
[Source](https://github.com/udsclub/web-traffic-time-series-forecasting/blob/master/notebooks/baseline%20on%20new%20train.ipynb)
***
## Median (last 30 days)
**Test** – 50.54%
[Source](https://github.com/udsclub/web-traffic-time-series-forecasting/blob/master/notebooks/baseline%20on%20new%20train.ipynb)
***
## LightGBM
1. <br>
**Features:** 30 lags, month, day, day of week <br>
**Test (subset)** - 49.29% (49.26%)
[Source test](https://github.com/udsclub/web-traffic-time-series-forecasting/blob/master/notebooks/lightgbm%20baseline.ipynb), [Source test(subset)](https://github.com/udsclub/web-traffic-time-series-forecasting/blob/master/notebooks/lightgbm%20baseline%20on%20subset.ipynb)
***
2. <br>
**Features:** 30 lags, month, day, day of week, lang, Project, Access, Agent<br>
**Test (subset)** - 49.99%
(Source)[https://github.com/udsclub/web-traffic-time-series-forecasting/blob/master/notebooks/lightgbm%20baseline%20with%20page%20features.ipynb]
