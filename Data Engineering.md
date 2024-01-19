assetId: b4f24a95-beb5-ee11-a569-000d3a33817b 
  # Data Engineering  Synapse Data Engineering empowers data engineers to be able to transform their data at scale using Spark and build out their lakehouse architecture. There are five key areas of Synapse Data Engineering that you can start using for your projects today:

Lakehouse for all your organizational data: The lakehouse is a new item in Fabric that combines the best of the data lake and the data warehouse in a single experience. It enables users to ingest, prepare, and share organizational data in an open format in the lake. Later you can access it through multiple engines such as Spark, T-SQL, and Power BI. It provides various data integration options such as dataflows and pipelines, shortcuts to external data sources, and data product sharing capabilities.

Performant Spark engine & runtime: Synapse Data engineering provides customers with an optimized Spark runtime with the latest versions of Spark (3.3.1), Delta (2.2), and Python (3.10). It uses Delta Lake as the common table format for all engines, enabling easy data sharing and reporting with no data movement. The runtime comes with Spark optimizations, enhancing your query performance without any configurations. It also offers starter pools and high-concurrency mode to speed up and reuse your Spark sessions, saving you time and cost.

Spark Admin & configurations: Workspace admins with appropriate permissions can create and configure custom pools to optimize the performance and cost of their Spark workloads. They can also install libraries, select the runtime version, and set Spark properties to customize the Spark environment. These settings will apply to all notebooks and Spark jobs in the workspace, unless otherwise specified.

Developer Experience: Developers can use notebooks, Spark jobs, or their preferred IDE to author and execute Spark code in Fabric. They can natively access the lakehouse data, collaborate with others, install libraries, track history, do in-line monitoring, and get recommendations from the Spark advisor. They can also use Data Wrangler to easily prepare data with a low-code UI.

Platform Integration: All Synapse data engineering items, including notebooks, Spark jobs, pipelines, and lakehouses, are integrated deeply into the Fabric platform (enterprise information management capabilities, lineage, sensitivity labels, and endorsements). This integration will continue to deepen this semester with many new investments.   |    Feature    ||:-------------||Schema support for Lakehouse   |** Schema support for Lakehouse   The lakehouse will support 3-part naming convention. It enables you to add
schemas to your lakehouses, which is consistent with the current warehouse
experience.
