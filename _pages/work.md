---
layout: archive
title: ""
permalink: /work/
author_profile: true
---

**A Real-Time solution for TV Viewership collection and processing across India.**  
*Lead Software Engineer*  

<!---
TV Viewership information is necessary in generating the TRP index. A large scale IoT solution with population based sampling for collecting this information is the standard way.
Generalizing this sampled data quickly is the core challenge of the solution. This depends on multitude of components such as, reliability in viewership collection at the nodes, latency and throughput *across* nodes and cloud storage, efficient data processing pipelines for analytics, etc. Each of these components comes with unique set of challenges, for example, 1) nodes should be robust to network/power disruptions in tracking time since the data is time sensitive, 2) data processing pipelines should handle data at the scale of 5000 events/node 3) DB storage schemas should be optimized for both space and query-time considering the volume of data.
Meeting these criteria, we designed and developed a solution that can support upto a *million* of Viewership collection nodes with real-time processing. In addition, we developed several tools for managing and monitoring the assets (IoT nodes), deployment life-cycle of system. Our solution is currently deployed across India (under the Broadcast and Research Council (*BARC*) body) and is serving as a means for country's TRP measurement system.  
-->

Television rating point (TRP) index is measured by collecting Viewership information of consumers via population sampling. In general, an IoT solution is deployed across these sampled consumers, and information is sent to a central server, where necessary post-processing (TRP index) is done. But, recent growth in consumer base and digitization, demands for a large scale and quick generalization (of samples) solutions. 
Designing solutions to meet these demands require a careful understanding of the challenges that arise in large scale systems, which are specific to the application. For example (to name a few), (1) Nodes should be robust to network/power disruptions. Especially, in handling time, as the Real Time clock (RTC) management might go out of sync leading to misinterpretation of data. (2) Data communication and processing pipelines should handle data at the scale of ~ #nodes/4 messages per second. Considering this, DB schemas should be optimized for both space and query-time. (3) Node monitoring. Since, the data is of critical nature, any tampered (outlier) behaviour/node health issues should to be identified immediately for isolating them from analysis. etc.
Addressing such challenges\*, we designed and developed an end-end solution that can scale upto a *million* of these Viewership collection nodes and achieve real-time processing of data.
Our solution is currently deployed across India (under the Broadcast and Research Council (*BARC*) body) and is serving as a means for country's TRP measurement system.

*HONOR*: Received a certificate of appreciation from BARC for the developed system.


*Please refer to my [Resume](/files/resume.pdf) for detailed information.
