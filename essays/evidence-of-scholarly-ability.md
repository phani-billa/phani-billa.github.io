---
layout: essay  
type: essay  
title: Evidence of Scholarly Ability  
date: 2016-08-29
labels:
  - PhD Portfolio
---

*This page presents evidence of my scholarly ability in computer science as required for the [ICS Ph.D. Portfolio](http://www.ics.hawaii.edu/academics/graduate-degree-programs/ph-d-in-ics/#phd-portfolio). This includes evidence of ability to identify, critically analyze, and research a problem, as well as written communication skills.*

## Literature Review

*Data Management for Distributed Sensor Networks: A Literature Review*
Anthony Christe. CSDL Tech Report CSDL-17-01.

Abstract: Sensor networks are spatially distributed autonomous sensors that monitor the physical world around them and often communicate those reading over a network to a server or servers. Sensor networks can benefit from the generally ``unlimited resources'' of the cloud, namely processing, storage, and network resources. This literature review surveys the major components of distributed data management, namely, cloud computing, distributed persistence models, and distributed analytics.

[Full Paper](http://csdl.ics.hawaii.edu/techreports/2017/17-01/17-01.pdf)

## Publications

*OPQ Version 2: An Architecture for Distributed, Real-Time, High Performance Power Data Acquisition, Analysis, and Visualization*. Anthony Christe, Sergey Negrashov, Philip Johnson, Dylan Nakahodo, David Badke and David Aghalarpour.
Accepted for publication at the 7th Annual IEEE International Confernce on CYBER Technology in Automation, Control, and Intelligent Systems (IEEE-CYBER 2017) (July 2017).

Abstract: OpenPowerQuality (OPQ) is a framework that supports end-to-end capture, analysis, and visualizations of distributed real-time power quality (PQ) data. Version 2 of OPQ builds on version 1 by providing higher sampling rates, optional battery backup, end-to-end security, GPS synchronization, pluggable analysis, and a real-time visualization framework. OPQ provides real-time distributed power measurements which allows users to see both local PQ events and grid-wide PQ events. The OPQ project has three principal components: back-end hardware for making power measurements, middleware for data acquisition and analysis, and a front-end providing visualizations. OPQBox2 is a hardware platform that takes PQ measurements, provides onboard analysis, and securely transfers data to our middleware. The OPQ middleware performs filtering on the OPQBox2 sensor data and performs high-level PQ analysis. The results of our PQ analysis and real-time state of the sensor network are displayed using OPQView. We've collected distributed PQ data from locations across Oahu, Hawaii and have demonstrated our ability to detect both local and grid-wide power quality events.

*OpenPowerQuality: An Open Source Framework for Power Quality Collection, Analysis, Visualization, and Privacy*.
Anthony Christe, Sergey Negrashov, Philip Johnson. 
In Proceedings of the Seventh Conference on Innovative Smart Grid Technologies (ISGT2016) (September 2016).

Abstract: As power grids transition from a centralized distribution model to a distributed model, maintaining grid stability 
requires real-time power quality (PQ) monitoring and visualization. As part of the Open Power Quality (OPQ) project, we 
designed and deployed a set of open source power quality monitors and an open source cloud-based aggregation and 
visualization system built with the utility customer in mind. Our aim is to leverage a flexible privacy model combined 
with inexpensive and easy to use PQ meters in order to deploy a high density power quality monitoring network across the
Hawaiian islands. In this paper we describe OPHub, a privacy focused open source PQ visualization along with results of 
a small scale deployment of our prototype PQ meter across the island of Oahu. Our results demonstrate that OPQ can 
provide useful power quality data at an order of magnitude less cost than prior approaches.

My specific contributions to this paper involve the discussions on privacy, visualizations, and sofwtware development.

[Full Paper](http://csdl.ics.hawaii.edu/techreports/2016/16-02/16-02.pdf)

## Technical Reports

*OPQ Cloud: A scalable software framework for the aggregation of distributed power quality data*
Anthony Christe.
April, 2014. CSDL Tech Report CSDL-14-04.

Abstract: Power quality issues can be caused in a variety of situations. Voltage fluctuations, frequency fluctuations, and 
harmonics are all power quality issues which can be caused by weather, high penetration of renewables, man-made issues, 
or other natural phenomena. We designed a software framework which can aggregate crowdsourced distributed power quality 
measurements in order to study power quality issues over a dense geographic area.

[Full Paper](https://github.com/csdl/techreports/raw/master/techreports/2014/14-04/14-04.pdf)
