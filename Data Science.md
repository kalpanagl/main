---
title: "What's new and planned for Synapse Data Engineering in Microsoft Fabric"
description: See what's new and planned for Synapse Data Engineeringin Microsoft Fabric. Fabric Data Engineering release plans or roadmap.
ms.reviewer: sngun
ms.author: sngun
author: snehagunda
ms.topic: conceptual
ms.date: 23-01-2024 
ms.assetId: b4f24a95-beb5-ee11-a569-000d3a33817b
---
# Data Engineering

Synapse Data Engineering empowers data engineers to be able to transform their data at scale using Spark and build out their lakehouse architecture. There are five key areas of Synapse Data Engineering that you can start using for your projects today:

Lakehouse for all your organizational data: The lakehouse is a new item in Fabric that combines the best of the data lake and the data warehouse in a single experience. It enables users to ingest, prepare, and share organizational data in an open format in the lake. Later you can access it through multiple engines such as Spark, T-SQL, and Power BI. It provides various data integration options such as dataflows and pipelines, shortcuts to external data sources, and data product sharing capabilities.

Performant Spark engine & runtime: Synapse Data engineering provides customers with an optimized Spark runtime with the latest versions of Spark (3.3.1), Delta (2.2), and Python (3.10). It uses Delta Lake as the common table format for all engines, enabling easy data sharing and reporting with no data movement. The runtime comes with Spark optimizations, enhancing your query performance without any configurations. It also offers starter pools and high-concurrency mode to speed up and reuse your Spark sessions, saving you time and cost.

Spark Admin & configurations: Workspace admins with appropriate permissions can create and configure custom pools to optimize the performance and cost of their Spark workloads. They can also install libraries, select the runtime version, and set Spark properties to customize the Spark environment. These settings will apply to all notebooks and Spark jobs in the workspace, unless otherwise specified.

Developer Experience: Developers can use notebooks, Spark jobs, or their preferred IDE to author and execute Spark code in Fabric. They can natively access the lakehouse data, collaborate with others, install libraries, track history, do in-line monitoring, and get recommendations from the Spark advisor. They can also use Data Wrangler to easily prepare data with a low-code UI.

Platform Integration: All Synapse data engineering items, including notebooks, Spark jobs, pipelines, and lakehouses, are integrated deeply into the Fabric platform (enterprise information management capabilities, lineage, sensitivity labels, and endorsements). This integration will continue to deepen this semester with many new investments.
## Investment areas

|     **Feature**      | **Estimated release timeline** |  

|:-------------------| :------------------------------:|
|[High concurrency in pipelines](#High-concurrency)|2024-09-24T18:30:00Z|
|[Schema support for Lakehouse](#Schema-support)|2024-08-06T18:30:00Z|

### <a name="High-concurrency"></a>High concurrency in pipelines
**High concurrency in pipelines:2024-09-24T18:30:00Z**



### <a name="Schema-support"></a>Schema support for Lakehouse
**Schema support for Lakehouse:2024-08-06T18:30:00Z**



title: "What's new and planned for Synapse Data Science in Microsoft Fabric"
description: See what's new and planned for Synapse Data Sciencein Microsoft Fabric. Fabric Data Science release plans or roadmap.
ms.reviewer: sngun
ms.author: sngun
author: snehagunda
ms.topic: conceptual
ms.date: 23-01-2024 
ms.assetId: 688800c2-c0b5-ee11-a569-000d3a33817b
---
# Data Science

Synapse Data Science provides data scientists with an end-to-end workflow for building their machine learning models, from exploration to model scoring. From a data exploration perspective, data scientists can use R and Python in notebooks, and built-in tools like Data Wrangler for easy analysis. Users can track and compare their model experiments and runs with MLFlow. They can save the best performing model in the workspace as a new model item and easily use Predict for batch scoring at scale. Data science in Fabric is deeply integrated with the rest of the stack, meaning it's seamless to score data in a lakehouse, write back the predictions to OneLake, and visualize the data in reports using Direct Lake mode
## Investment areas

|     **Feature**      | **Estimated release timeline** |  

|:-------------------| :------------------------------:|
|[High concurrency in pipelines](#High-concurrency)|2024-09-24T18:30:00Z|
|[Schema support for Lakehouse](#Schema-support)|2024-08-06T18:30:00Z|
|[Semantic Link GA](#Semantic-Link)|2024-09-26T18:30:00Z|

### <a name="High-concurrency"></a>High concurrency in pipelines
**High concurrency in pipelines:2024-09-24T18:30:00Z**



### <a name="Schema-support"></a>Schema support for Lakehouse
**Schema support for Lakehouse:2024-08-06T18:30:00Z**



### <a name="Semantic-Link"></a>Semantic Link GA
**Semantic Link GA:2024-09-26T18:30:00Z**


