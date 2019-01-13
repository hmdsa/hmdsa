---
layout: page
title: Tools
subtitle: HMDSA tools
---

------
* TOC 
{:toc} 
------

HMDSA Tools provide a variety of capabilities:

### Data Collection Tools ###
* Lightweight Distributed Metric Service ([LDMS](./tools/ldms.md)) -- gathers numeric data and provides a variety of transport and storage options.
* Mike Showerman's Lustre probe -- periodically probes, stores, and displays, the latency involved in performing Lustre meta-data and storage operations for identification of problems.
* Physical plant?
* Baler -- aggregates log data and associated "patterns" into a distributed database 

### Storage Tools ###
* (NCSA suite of tools that do data management here - doc from Mike?)

### Analysis Tools ###
(on the particular pages, put an example of the analysis and what you get back. Can x-ref with the analysis and/or insights page):
* Machine Learning (ML) based tools -- the HMDSA team has collaborative partnerships to develop ML based tools to perform a variety of runtime analyses. These include:
  * a team at Boston University (BU) working on developing ML based methods for runtime identification and diagnosis of a variety of performance degrading anomalies [cite papers here] using a variety of system monitoring data
  * The Blue Waters Project has an ongoing effort to architect and study ML models that process a system’s monitoring and usage data to create a mixture of descriptive, predictive, and prescriptive analysis to assist systems managers and performance experts with near real time monitoring and diagnostics.
* [LogDiver](./tools/logdiver.md) -- identifies probabilistic relationships between log events
* [Baler](./tools/baler.md) -- identifies and tags uniuqe patterns of "tokens" associated with log messages, discovers spatio-temporal correlative relationships between tagged events
* [LDMS](./tools/ldms.md) -- provides capability for performing a variety of analytics on data along the transport path

### Feedback and Visualization Tools ###
(Any additional references to dashboards, torus viewers, mike's graphs etc):

* Integrated System Console (ISC) provides a variety of dashboards and subsystem specific notifications
* [LDMS](./tools/ldms.md) -- provides APIs and mechanisms for low latency feedback of information to system and application processes
* [Baler](./tools/baler.md) -- enables user exploration, and user tagging, of events and event-to-event relationships via both GUI and CLI interfaces, will soon be configurable to send alerts on "Conditions Of Interest" (COI) to subscribers
* [LogDiver](./tools/logdiver.md) -- provides continous resiliency analysis for HPC systems, and capture the relationship between error events helping find error propagation 
  
