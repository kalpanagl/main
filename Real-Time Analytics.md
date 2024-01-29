---
title: "What's new and planned for Synapse Real-Time Analytics in Microsoft Fabric"
description: See what's new and planned for Synapse Real-Time Analytics in Microsoft Fabric. Fabric Real-Time Analytics release plans or roadmap.
ms.reviewer: sngun
ms.author: sngun
author: snehagunda
ms.topic: conceptual
ms.date: 29-01-2024 
ms.assetId: 72ce3a8e-4bbb-ee11-a568-6045bd0783f5
---
# Real-Time Analytics

Synapse Real-Time Analytics is a fully managed big data analytics platform optimized for streaming and time-series data. The services in Real-Time Analytics provide the capability to capture, transform, and route real-time events to and from different environments. You can even enable distinct endpoints where your custom application can directly produce or consume events from the Fabric Eventstream item. The dedicated Kusto Query Language (KQL) database can load data from any source in any data format, and run analytical queries directly on raw data without the need to build complex data models or create scripting to transform the data. Use either SQL or the native KQL to process massive amounts of data in real time with high performance and low latency.

Synapse Real-Time Analytics is useful for organizations that need high freshness from data ingestion for querying, require low query latency, or need to search or access data in different formats, including structured, semi-structured (such as JSON), or unstructured data (such as free text). You can scale your data needs with the service, to an unlimited amount of data (from gigabytes to petabytes) with unlimited scalability on concurrent queries and concurrent users. Real-Time Analytics is fully integrated with the entire suite of Fabric products to streamline your data analytics processes for data loading, data transformation, and advanced visualization scenarios.

For more information, see the Real-Time Analytics documentation and visit the announcement blog.

The items available in Real-Time Analytics are:

Eventstreams for capturing, transforming, and routing real-time events to various destinations with a no-code experience.

A KQL database for data storage, analytics, and management. Data loaded into a KQL database can be accessed in OneLake and is exposed to other Fabric experiences.

A KQL queryset to run queries, view, and customize query results on data. The KQL queryset allows you to save queries for future use, export, and share queries with others. It includes the option to generate a Power BI report.

A real-time dashboard, which contains a collection of tiles. Each tile has an underlying query and a visual representation perfect for data exploration, monitoring, and forensics.

Recent innovations include:

Mounting of Azure Data Explorer Database (follower) to Fabric; creating a database shortcut is now available (Announcement blog)

Sample gallery for Real-Time Analytics and KQL (Announcement blog)

Model and query data as graphs using Kusto Query Language (KQL) (Announcement blog)

Eventstreams support AMQP format connection string for data ingestion (Announcement blog)

Eventstreams support data ingestion from Azure IoT Hub (Announcement blog)
## Investment areas

|     **Feature**      | **Estimated release timeline** |  
|:-------------------| :------------------------------:|
|[Data streaming from Kafka to eventstreams](#Data-streaming)|Q2|


### <a name="Data-streaming"></a>Data streaming from Kafka to eventstreams
**Data streaming from Kafka to eventstreams:  2024-04-25T18:30:00Z**

Customers can subscribe to Azure resource events (like Blob storage events),
partner events (like SAP), custom events, or MQTT topics, and then have them
streamed to eventstreams.


