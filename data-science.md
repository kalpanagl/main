---
title: What's new and planned for Synapse Data Science in Microsoft Fabric
description: See what's new and planned for Synapse Data Science in Microsoft Fabric. Fabric Data Science release plans or roadmap.
ms.reviewer: sngun
ms.author: sngun
author: snehagunda
ms.topic: conceptual
ms.date: 06/13/2023
---

# What's new and planned for Synapse Data Science in Microsoft Fabric

> [!Important]
> The release plans describe functionality that may or may not have been released yet. The delivery timelines and projected functionality may change or may not ship. Refer to [Microsoft policy](https://go.microsoft.com/fwlink/p/?linkid=2007332) for more information.

Synapse Data Science provides data scientists with an end-to-end workflow for building their machine learning models, from exploration to model scoring. From a data exploration perspective, data scientists can use R and Python in notebooks, and built-in tools like Data Wrangler for easy analysis. Users can track and compare their model experiments and runs with MLFlow. They can save the best performing model in the workspace as a new model item and easily use Predict for batch scoring at scale. Data science in Fabric is deeply integrated with the rest of the stack, meaning it's seamless to score data in a lakehouse, write back the predictions to OneLake, and visualize the data in reports using Direct Lake mode.

Synapse Data Science is in public preview. To learn more, see the [documentation](/fabric/data-science/) and visit the [announcement blog](https://blog.fabric.microsoft.com/blog/category/announcements).

## Investment areas

| Feature | Estimated release timeline |
| ---------- | ---------- |
| [Semantic Link GA](#semantic-link) | Q2 2024 |
| [ML Model endpoints](#model-endpoints) | Q2 2024 |
| [AutoML hyperparameter tuning with FLAML](#flaml) | Q1 2024 |
| [CI/CD support for data science items](#cicd) | Q2 2024 |
| [Monitoring hub integration](#monitoring-hub) | Q2 2024 |

### <a name="semantic-link"></a>Semantic Link GA

**Estimated release timelines: Q2 2024**

Semantic link bridges the gap between data science and BI by providing a Python library (SemPy) that enables data scientists to interact with Power BI datasets and measures. You can use SemPy to read, explore, query, and validate data in Power BI from Python notebooks, and use the library's features to detect and resolve data challenges. Users can also write back to the Power BI dataset through the lakehouse with Direct Lake mode.

### <a name="model-endpoints"></a>ML Model Endpoints
**Estimated release timelines: Q2 2024**

Model endpoints in Fabric enables users to perform real-time scoring of machine learning models, providing immediate predictive insights. With Model Endpoints, you will seamlessly integrate your machine learning models into your workflows for quicker and more effective decision-making based on real-time data analysis.

### <a name="flaml"></a>AutoML hyperparameter tuning with FLAML

**Estimated release timelines: Q1 2024**

You can automate the process of training and optimizing machine learning models with the flexibility of FLAML. You can use Spark to reduce costs by parallelizing hyperparameter trials and easily tune SparkML and SynapseML models. MLflow automatically captures AutoML runs and hyperparameter metrics.

### <a name="cicd"></a>CI/CD support for data science items

**Estimated release timeline: Q2 2024**

You can use the platform git integration and deployment pipelines to version your data science solutions and deploy them across dev, test, and production workspaces. You can use the UI experience or automate the process through Azure Pipelines.

### <a name="monitoring-hub"></a>Monitoring hub integration

**Estimated release timeline: Q2 2024**

Data science item runs are available to monitor inside the monitoring hub alongside all other Fabric items.

## Related content

- [Synapse Data Science documentation in Microsoft Fabric](/fabric/data-science/)
