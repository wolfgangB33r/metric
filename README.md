# Problem Pattern

# How to start the transparent proxy problem pattern

- Increase proxy.metric.range.low to 90% and proxy.metric.range.high to 99
- After 5 minutes increase proxydelayms and servicedelayms metrics to 4000

# How to start the failing proxy problem pattern

- Increase proxy.metric.range.low to 90% and proxy.metric.range.high to 99
- After 5 minutes set the proxyresponse from "200" to "500"
