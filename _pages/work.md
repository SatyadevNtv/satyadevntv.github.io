---
layout: archive
title: ""
permalink: /work/
author_profile: true
---

**A Real-Time solution for TV Viewership collection and processing for India.**  
*Lead Software Engineer*  

Television rating point (TRP) index is measured by collecting Viewership information of consumers via population sampling. In general, an IoT solution is deployed across these sampled consumers to collect this information and communicate it to a central server where necessary post-processing (TRP index) is done. 
But, recent growth in consumer base and digitization, demands for a large scale and quick generalization (of samples) solutions. 
Designing solutions to meet these demands require a careful understanding of the challenges that arise in such large scale systems, which are specific to the application. For example, 
(1) Nodes should be robust to network/power disruptions. Especially, in handling time, as the Real Time clock (RTC) management can go out of sync leading to misinterpretation of data. 
(2) Data communication and processing pipelines should handle data that scales linearly (per second) with #nodes. Considering this, DB schemas should be optimized for both space and query-time. 
(3) Node monitoring. Since the data is of critical nature, any tampered (outlier) behaviour/node health issues should to be identified immediately for isolating them from analysis. etc.
Addressing such multitude of challenges\*, we designed and developed an end-end solution based on event-driven architecture. The solution can scale upto a *million* of these Viewership collection nodes and achieve real-time processing of data.
Our solution is currently deployed across India (under the Broadcast and Research Council (*BARC*) body) and is serving as a means for country's TRP measurement system.

*HONOR*: Received a certificate of appreciation from BARC for the developed system.


*Please refer to my [Resume](/files/resume.pdf) for detailed information.
