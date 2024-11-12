---
title: "Zotcare"
description: >
  Zotcare is a service provider platform that helps researchers run their mobile health studies.
date: 2021-10-28T11:30:47-07:00
draft: false
featuredImage: images/zotcare-logo.png
toc: true
---
## About ZotCare
With ZotCare you can run your mobile health (mHealth) study:

- Zero to little programming knowledge
- Quick time to production
- No deployment or maintenance
- Utilize an AI-based approach for personalization and adaptation

{{< figure src="/images/zotcare-intuition.png" class="lg:w-4/5 mx-auto px-6 md:px-8 xl:px-12" caption="ZotCare Intuition" alt="zotcare-intuition" >}}


## Service Orchestration
Services in ZotCare offer what researchers need to run any type of study. 
Main components in ZotCare service architecture are:

- **Data Collection Services** facilitate the ingestion of data from diverse devices, applications, and services. Once collected, the data undergoes processing and is stored as a continuous stream within ZotCare.
- **Profile Services** assume responsibility for the storage and processing of data in the form of key-value pairs. This storage mechanism enables the creation of profiles for participants and groups, serving as a repository for personalized study-related data and models, as further elucidated subsequently. 
- Through **Real-time Processing, Intervention, and Integration (RPII) Services**, researchers possess the capability to incorporate adaptive, intelligent, and real-time components into their studies. These components are capable of triggering various actions based on the data obtained from the Profile and Collection services.

In conjunction with these services, ZotCare provides two interfaces: a customizable dashboard and a user-facing mobile application.


- **Customizable ZotCare dashboard** serves as a web application, offering researchers an interface for accessing and modifying ZotCare services pertinent to their respective studies. Researchers can employ the dashboard to manage collected data, recruit participants, and customize it for clinical purposes if desired.
- **ZotCare mobile application**, on the other hand, functions as a user-facing mobile application for participants. It allows them to interact with ZotCare services, enabling functionalities such as receiving reminders, engaging in ecological momentary assessments (EMAs), and benefiting from adaptive mobile health interventions. Moreover, ZotCare facilitates the integration of contextual and behavioral monitoring applications, commonly referred to as lifelogging applications.


{{< figure src="/images/zotcare-services.png" class="lg:w-4/5 mx-auto px-6 md:px-8 xl:px-12" caption="ZotCare Service Orchestration" alt="zotcare-services" >}}

## Read More
To read more about ZotCare, please read [this open-access paper](https://www.frontiersin.org/journals/digital-health/articles/10.3389/fdgth.2023.1253087/):

```Labbaf S, Abbasian M, Azimi I, Dutt N and Rahmani AM (2023) ZotCare: a flexible, personalizable, and affordable mhealth service provider. Front. Digit. Health 5:1253087. doi: 10.3389/fdgth.2023.1253087```

To find out how to use ZotCare in your future studies, please visit ZotCare website @ https://futurehealth.uci.edu/projects/zotcare/
