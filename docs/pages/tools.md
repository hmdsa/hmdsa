---
layout: page
title: Tools
subtitle: HMDSA tools
---

HMDSA Tools provide a variety of capabilities:

TODO: 
1) put high-level list of the tools and their capabilities to be put in here - 1 sentence or so
2) then put links to per-tool pages for more detail


Data Collection Tools:
* Lightweight Distributed Metric Service (LDMS) -- gathers numeric data and provides a variety of transport and storage options.
* Mike Showerman's Lustre probe -- periodically probes, stores, and displays, the latency involved in performing Lustre meta-data and storage operations for identification of problems.
* Physical plant?
* Baler -- aggregates log data and associated "patterns" into a distributed database 

Storage Tools:
* (NCSA suite of tools that do data management here - doc from Mike?)

Analysis Tools:
* A (on the particular pages, put an example of the analysis and what you get back. Can x-ref with the analysis and/or insights page)
* LogDiver -- identifies probabilistic relationships between log events
* Baler -- identifies and tags uniuqe patterns of "tokens" associated with log messages, discovers spatio-temporal correlative relationships between tagged events
* LDMS -- provides capability for performing a variety of analytics on data along the transport path
* Machine Learning (ML) based tools -- the HMDSA team has collaborative partnerships to develop ML based tools to perform a variety of runtime analyses. These include:
  * a team at Boston University (BU) working on developing ML based methods for runtime identification and diagnosis of a variety of performance degrading anomalies [cite papers here] using a variety of system monitoring data
  * The Blue Waters Project has an ongoing effort to architect and study ML models that process a system’s monitoring and usage data to create a mixture of descriptive, predictive, and prescriptive analysis to assist systems managers and performance experts with near real time monitoring and diagnostics.

Feedback and Visualization Tools:
* C (Any additional references to dashboards, torus viewers, mike's graphs etc)
* LDMS -- provides APIs and mechanisms for low latency feedback of information to system and application processes
* Baler -- enables exploration, and user tagging, of events and event-to-event relationships via both GUI and CLI interfaces, will be configurable to send alerts on "Conditions Of Interest" (COI) to subscribers
* LogDiver -- (what does interaction with this tool look like?)
  
