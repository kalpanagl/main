---
title: "What's new and planned for Synapse Data Science in Microsoft Fabric"
description: See what's new and planned for Synapse Data Science in Microsoft Fabric. Fabric Data Science release plans or roadmap.
ms.reviewer: sngun
ms.author: sngun
author: snehagunda
ms.topic: conceptual
ms.date: 29-01-2024 
ms.assetId: 688800c2-c0b5-ee11-a569-000d3a33817b
---
# Data Science

Synapse Data Science provides data scientists with an end-to-end workflow for building their machine learning models, from exploration to model scoring. From a data exploration perspective, data scientists can use R and Python in notebooks, and built-in tools like Data Wrangler for easy analysis. Users can track and compare their model experiments and runs with MLFlow. They can save the best performing model in the workspace as a new model item and easily use Predict for batch scoring at scale. Data science in Fabric is deeply integrated with the rest of the stack, meaning it's seamless to score data in a lakehouse, write back the predictions to OneLake, and visualize the data in reports using Direct Lake mode
 ## Investment areas
 
|     **Feature**      | **Estimated release timeline** |  
|--------------------| ----------------------------------|
|[CI/CD support for data science items](#CI/CD-support)|Q2 2024|
|[Semantic Link GA](#Semantic-Link)|Q3 2024|
 
### <a name="CI/CD-support"></a>CI/CD support for data science items
**Estimated release timelines: Q2 2024**
<!-- CI/CD-support start -->
You can use the platform git integration and deployment pipelines to version
your data science solutions and deploy them across dev, test, and production
workspaces. You can use the UI experience or automate the process through Azure
Pipelines.


<!-- CI/CD-support end -->

### <a name="Semantic-Link"></a>Semantic Link GA
**Estimated release timelines: Q3 2024**
<!-- Semantic-Link start -->
Semantic link bridges the gap between data science and BI by providing a Python
library (SemPy) that enables data scientists to interact with Power BI datasets
and measures. You can use SemPy to read, explore, query, and validate data in
Power BI from Python notebooks, and use the library's features to detect and
resolve data challenges. Users can also write back to the Power BI dataset
through the lakehouse with Direct Lake mode.


<!-- Semantic-Link end -->
