---
layout: page
title: Architecture
subtitle: HMDSA Design and Architecture
---
![Image of HMDSA arch](resources/figs/hmdsa-arch.jpg){:width="720px"}{: .center-image}
#### Architectural Features: ####
* Platform independent infrastructure for common operations across facilities
* Scalable - Demonstrated in production over 4 years up to 27K nodes.
* Integrated streaming and historical analysis
* Strategy for long term storage and recall of data for trends

#### Components: ####
##### Data Collection: #####
* Lightweight Distributed Metric Service (LDMS) - data collection and transport. Run-time tunable fidelity (including subsecond) with no adverse  impact on application performance
* Collectors for application and platform data and integration of external collection (e.g. kokkos)

##### Analysis: #####
* Streaming analysis and active feedback capabilities
* Integrated System Console (ISC) - analytics database, retrieval and display
* LogDiver+Baler - event tagging and relationship discovery
* A variety of analysis tools including ML/AI based tools for identification

##### Actionable Intelligence: #####
* Assessments of System Conditions, Application Resource Utilization, and Performance provide actionable insights to be used to improve operations, performance, and system designs:
** Notifications
** Dashboards and Visualizations

##### Feedback and Control: #####
* Transport architecture includes flow of analysis results to humans and the system to enable action as a result of analyzed conditions. Examples include:
** Application rebalancing based on utilization imbalances
** System scheduler decisions based on congestion areas or application profiles
** System administrator decision support


![Image of ML-arch](resources/figs/ml.jpg){:width="720px"}{: .center-image}
