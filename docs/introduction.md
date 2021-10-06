---
sidebar_position: 1
---

# Introduction

## About Chaos Genius

Chaos Genius is an open-source business observability platform.Chaos Genius enables businesses to monitor thousands of KPIs, across multiple data sources, and perform automated root cause analysis for any deviation in the KPIs. 

Chaos Genius can help teams reduce their Mean-Time-To-Detect (MTTD) and Mean-Time-To-Resolve (MTTR) for any issues in their business and system KPIs. 

Standard BI dashboards enable data visualization to track how select metrics are trending. However, diagnosing why a particular metric or KPI has changed, remains a woefully manual process involving slicing & dicing the data, coordination with multiple teams in an organization to identify related events and monitoring externalities. 

With Chaos Genius, we aim to automate the diagnosis and root-cause-analysis for deviations in different business and system KPIs at scale. 


## Key Use-Cases

**Business KPI Observability**  - All important business KPIs such as Sign Ups, Payment Gateway Failures, Fraud Detection, Ad Spend, Campaign Performance, DAUs, Retention, Engagement and many others. 

**Data Quality KPI Observability** - Data quality metrics like Data Volume, Freshness, Max, Mean, Median, Min, Missing Data, Null Count and many others. 

**Systems KPI Observability** - System metrics like Cloud Costs, Cloud Failure, Infra performance and many others. 

**IOT/Device KPI Observability** - Device metrics like performance, data volumes, uptime and many others. 


## Key Features

**DeepDrills** - Multidimensional drill-downs & waterfall analysis to identify the top drivers of change in a KPI across multiple dimensions. 

**Anomaly Detection** - Modular anomaly detection toolkit for monitoring high-dimensional time series with ability to select from different models. Anomaly investigation across multiple dimensions and data quality metrics like volume, max, mean and missing data. 

**Smart Alerts** - No more alert fatigue from static alerts. Self-learning thresholds to reduce false positives. Configurations to setup alert frequency & severity. Choose from multiple destinations like Slack, Email and other channels for your team.

**Integrations** - Modular architecture to enable multiple data sources including databases, data warehouses and multiple third party connectors like Stripe, Shopify, Zendesk, Google Analytics, and many others.

[See more on our website. ](https://chaosgenius.io/)

## Architecture

![image](/img/cg-high-level-arch.png)

## Quick Install

```
git clone https://github.com/chaos-genius/chaos_genius

cd chaos_genius

docker-compose up
```

Visit[  http://localhost:8000](http://localhost:8000/)

Follow this [Quick Install guide](https://github.com/chaos-genius/.github)[  ](https://github.com/airbytehq/airbyte/tree/e378d40236b6a34e1c1cb481c8952735ec687d88/docs/quickstart/getting-started.md)showing you how to connect a data source, define your first KPI, configure Anomaly Detector on your local machine. 

If you want to schedule office hours with our team to help you get set up, please select [some time directly here.](https://calendly.com/pshrimal/30min)

## Community

Chaos Genius is a community driven initiative. For any help, discussions, suggestions feel free to reach out to the Chaos Genius team and the Community on either of the following channels. 

-   [GitHub](https://github.com/chaos-genius/.github) (report bugs, contribute, follow roadmap)

-   Slack (For discussion with the Community and Chaos Genius team)

-   Book Office Hours (Set Up time with Chaos Genius team for any questions or help with setup)

-   [Blog](https://chaosgenius.io/blog/) (Follow us on latest trends on Data, Machine Learning, Open Source and more)

## Contributing

Here's a shout out to all our contributors.

Want to contribute? Visit our Github repo and get started with:

-   Try Chaos Genius and share your feedback.

-   Submit an issue. 

-   Create a pull request. Here's a [list of issues](https://github.com/chaos-genius/chaos_genius/issues) to start with.

-   Share a part of the documentation that you find difficult to follow.

-   [Translate our Readme](https://github.com/chaos-genius/.github/blob/main/README.md).

-   Show us some love - Give us a star!



## Roadmap

Check out our Roadmap 

## License

Chaos Genius is licensed under the MIT license. See the LICENSE file for licensing information.

