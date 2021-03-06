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
* Lightweight Distributed Metric Service ([LDMS](./tools/ldms.md)) -- gathers numeric data, including platform, [application](./tools/applicationdata.md), and facilities data, and provides a variety of transport and storage options.
* System probes -- periodically probes, stores, and displays performance and state information, such as the latency involved in performing Lustre meta-data and storage operations for identification of problems.
<!-- * Physical plant? -->
* [Baler](./tools/baler.md) -- aggregates log data and associated "patterns" into a distributed database 

### Storage Tools ###
<!-- * (NCSA suite of tools that do data management here - doc from Mike?) -->
* Short and long term data storage options. 

### Analysis Tools ###
* Machine Learning (ML) based tools for runtime analysis:
  * [Clustering and Classification techniques](./analysis.md) -- extracting regions of interest and characterizing them in terms of severity, extent, and duration
  * [Inferential techniques](./analysis.md) -- probabilitistic determination of root causes and relationships
  * [LogDiver](./tools/logdiver.md) -- identifies probabilistic relationships between log events
  * [Baler](./tools/baler.md) -- identifies and tags uniuqe patterns of "tokens" associated with log messages, discovers spatio-temporal correlative relationships between tagged events
  * [LDMS](./tools/ldms.md) -- provides capability for performing a variety of analytics on data along the transport path
<!-- -- the HMDSA team has collaborative partnerships to develop ML based tools to perform a variety of runtime analyses. These include: -->
* ML collaborative partnerships:
  * Collaboration with Boston University (BU) working on developing ML based methods for runtime identification and diagnosis of a variety of [performance degrading anomalies](./applicationdata.md) using a variety of system monitoring data
  * Collaborations with New Mexico State University (NMSU) and other SNL staff working on developing [application profiling metrics](./tools/applicationdata.md)
  * A multi-site collaborative effort that continuously determines and presents *[figures of merit](./insights.md)* for all system, subsystem, and performance metrics (e.g., network congestion state, communication performance) to enable comparison and diagnosis of job performance
  * The Blue Waters Project has an ongoing effort to architect and study ML models that process a system’s monitoring and usage data to create a mixture of [descriptive, predictive, and prescriptive analysis](./analysis.md) to assist systems managers and performance experts with near real time monitoring and diagnostics.



### Tools for Feedback and Visualization of Actionable Intelligence ###
* Integrated System Console ([ISC](./tools/ISC.md)) provides a variety of dashboards and subsystem specific notifications. The ISC operates on data in the short term store. 
* [LDMS](./tools/ldms.md) -- provides APIs and mechanisms for low latency feedback of information to system and application processes
* [Baler](./tools/baler.md) -- enables user exploration, and user tagging, of events and event-to-event relationships via both GUI and CLI interfaces, will soon be configurable to send alerts on "Conditions Of Interest" (COI) to subscribers
* [LogDiver](./tools/logdiver.md) -- provides continous resiliency analysis for HPC systems, and capture the relationship between error events helping find error propagation 
  
